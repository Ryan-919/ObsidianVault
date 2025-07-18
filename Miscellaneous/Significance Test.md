##### State
###### Procedure
2 sample t test for $\mu_{D} - \mu_{R}$
- $\mu_{D}$ = the true mean age of Democratic Congress members in the 117th and 118th Congress
- $\mu_{R}$ = the true mean age of Republican Congress members in the 117th and 118th Congress.

###### Significance Level
$\alpha=0.03$
###### Hypotheses
- $H_{0}$: $\mu_{D} - \mu_{R} = 0$
- $H_{a}$: $\mu_{D} - \mu_{R} ≠ 0$
##### Plan
- ###### Random Condition:
	- We are taking a random sample of 40 for both parties' Congress members in the 117th and 118th Congress.
- ###### 10% Condition
	- $40 \leq 0.1(539 \ Democrat \ Congress \ Members \ in \ 117th \ a n d \ 118th \ Congress)$
	- $40 \leq 0.1(545 \ Republican \ Congress \ Members \ in \ 117th \ a n d \ 118th \ Congress)$
	- We can assume independence since 10% condition is met.
- ###### Approximately Normal
	- Since the sample size of 40 for both samples is greater than 30, the Central Limit Theorem applies and both sampling distributions of the mean are approximately normal.

##### Do
$\bar{x}_{D} = 61.9856$
$S_{D} = 10.9610$
$n_{D} = 40$

$\bar{x}_{R} = 58.1749$
$S_{R} = 11.5830$
$n_{R} = 40$

$$
t = \frac{\bar{x}_{D} - \bar{x}_{R}}{\sqrt{ \frac{S_{D}^2}{n_{D}} + \frac{S_{R}^2}{n_{R}} }} = \frac{61.9856-58.1749}{\sqrt{ \frac{10.961^2}{40} + \frac{11.5830^2}{40} }} = 1.5113
$$
$df = 77.7636$
$$
p-value = 2(tcdf(lower: 1.5113,\ upper: 10^{99},\ df: 77.7636)) = 0.1348
$$

##### Conclude
Since the p-value of 0.1348 is greater than the $\alpha$ of 0.03, we fail to reject $H_{0}$. There is not convincing statistical evidence that the difference in the true mean age of Democratic Congress members and Republican Congress members in the 117th and 118th Congress is not 0.
