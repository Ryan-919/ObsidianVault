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
```c title:"mario.c"
#include <stdio.h>
#include <cs50.h>

int getIntInRange(void);

int main(void) {
	// Prompt user for height of pyramids
    int height = getIntInRange() + 1;
	
    for (int i = 1; i < height; i++)
    {
        // Left part of pyramid
        for (int j = height; j > i + 1; j--)
        {
            printf(" ");
        }
        for (int k = 0; k < i; k++)
        {
            printf("#");
        }
		
        printf("  ");
		
        // Right part of pyramid
        for (int k = 0; k < i; k++)
        {
            printf("#");
        }
		
        printf("\n");
    }
}

int getIntInRange(void)
{
    int num;
    do
    {
        num = get_int("Height: ");
    }
    while (num < 1 || num > 8);
	
    return num;
}
```

##### Explanation
- Will continually prompt the user until a valid integer (one from 1 - 8 inclusive) is inputted
- Outputs a pyramid made of hashes into the terminal wtih a space between the left and right halves:
- Ex: `3` is inputted will yield:
```
  # #
 ## ## 
### ###
```

#### content

##### New Content

###### `{c}int getIntInRange(void)` 

```c
int getIntInRange(void)
{
    int num;
    do
    {
        num = get_int("Height: ");
    }
    while (num < 1 || num > 8);
    return num;
}
```

- Declares an integer variable `{c} num`
- Updates `{c} num` based on user input
- If `{c}num` is not in the range of 1 and 8 inclusive, prompts the user again
- Once `{c}num` is in the valid range, return `{c}num`

##### New syntax
- `{C} int function(void);`
	- Declares a function which can be defined later in the program
	- First word is return type
	- Variables in `{c}()` are parameters
- `{c} do {} while (bool);` 
	- do while loop
	- Runs code in `{}` at least once and while `{c}bool` is true
- `{c} for(int i = 0; bool; i++) {}` 
	- for loop
	- Runs code in `{}` while `{c}bool` is true
	- **First statement** runs once before the loop starts
		- usually initialization of a new `{c}int` variable
	- **Second statement** is the condition that keeps the loop running
	- **Last statement** runs once after each iteration of the loop

##### Previously Covered Syntax:
- [[helloWorld.c]] 
	- `{c}#include <stdio.h>` 
	- `{c}int main(void) {}`
	- `{c}printf("#");` 
### Sources
[Problem](https://cs50.harvard.edu/x/2025/psets/1/mario/more/)

