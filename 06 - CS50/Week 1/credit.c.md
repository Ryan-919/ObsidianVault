---
date: 2025-06-23
language: C
tags:
  - programming
  - C
  - documentation
---
#### Code
##### Source code
```c title:"credit.c"
#include <stdio.h>
#include <cs50.h>

int sumOfDigits(int num);

int main(void)
{

    long num = get_long("Number: ");
    long temp1 = num;
    long temp2 = num;
    long temp3 = num;

    int digits = 0;

    while (temp1 > 0)
    {
        temp1 /= 10;
        digits++;
    }

    int sum = 0;
    for (int i = 0; i < digits; i++)
    {
        if (i % 2 != 0)
        {
            sum += sumOfDigits((temp2 % 10) * 2);
        }
        temp2 /= 10;
    }

    for (int i = 0; i < digits; i++)
    {
        if (i % 2 == 0)
        {
            sum += temp3 % 10;
        }
        temp3 /= 10;
    }

    string conclusion = "INVALID";

    if ((sum % 10 == 0))
    {
        if (digits == 15)
        {
            int firstTwoDigits = num / 10000000000000;
            if (firstTwoDigits == 34 || firstTwoDigits == 37)
            {
                conclusion = "AMEX";
            }
        }
        else if (digits == 13)
        {
            int firstDigit = num / 1000000000000;
            if (firstDigit == 4)
            {
                conclusion = "VISA";
            }
        }
        else if (digits == 16)
        {
            int firstDigit = num / 1000000000000000;
            if (firstDigit == 4)
            {
                conclusion = "VISA";
            }
            int firstTwoDigits = num / 100000000000000;
            if (firstTwoDigits == 51 || firstTwoDigits == 52 || firstTwoDigits == 53 ||
                firstTwoDigits == 54 || firstTwoDigits == 55)
            {
                conclusion = "MASTERCARD";
            }
        }
    }

    printf("%s\n", conclusion);
}

int sumOfDigits(int num)
{
    int temp = num;
    int digits = 0;

    while (temp > 0)
    {
        temp /= 10;
        digits++;
    }

    int sumOfDigits = 0;
    for (int i = 0; i < digits; i++)
    {
        sumOfDigits += num % 10;
        num /= 10;
    }
    return sumOfDigits;
}
```
##### Explanation
- Determines whether any given credit card number is syntactically valid using **Luhn's Algorithm** 
	1. Multiply every other digit by 2, starting with the number’s second-to-last digit, and then add those products’ digits together.
	2. Add the sum to the sum of the digits that weren’t multiplied by 2.
	3. If the total’s last digit is 0 (or, put more formally, if the total modulo 10 is congruent to 0), the number is valid!
- If the number is valid, the program will also **output the company** it belongs to, American Express, Mastercard, or Visa
- The program iterates over each digit of the given number using `{c}%10`
- Uses a function to return the sum of digits of an `{c}int` parameter

#### Content
##### Previously Covered Syntax:
- [[helloWorld.c]] 
	- `{c}#include <stdio.h>` 
	- `{c}int main(void) {}`
	- `{c}printf("#");` 
- [[mario.c]]
	- `{C} int function(void);`
	- `{c} do {} while (bool);` 
	- `{c} for(int i = 0; bool; i++) {}` 
- 
##### Code Explanations:



##### New Syntax
- `{C} while(bool) {}`
	- While loop
	- Simplest loop which runs code in `{}` as long as `{c}bool` statement is true
- `{c} if(bool) {}`
	- If statement
	- Runs code in `{}` if `{c}bool`statement  is true
- `{c}else if(bool) {}`
	- Else if statement
	- Runs code in `{}`only when the preceding if statement's condition is false `{c} bool` statement is true
- `{c} else {}`
	- Else statement
	- Runs code in `{}` only when the preceding `{c}if` and `{c}else if` statements' conditions are **all** false
### Sources
[Problem](https://cs50.harvard.edu/x/2025/psets/1/credit/)

