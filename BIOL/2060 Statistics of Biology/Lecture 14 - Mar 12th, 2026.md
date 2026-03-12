### Mann-Whitney U-test
1. Order and rank the data:
2. adf
3. Calculate $U_1 = n_1n_2 + \frac{n_1 (n_1+1)}{2} - R_1$
4. $U_2 = n_1n_2 - U_1$
5. $U_1 > U_2 -> U_1 = U$ (test statistic)
6. Critical value 

### Two-sample test is to test the means of two independent grops
- If there are more than two groups?
- We could conduct three separate t-test:
	- Placebo vs old drug
	- Placebo vs new drug
	- New drug vs old drug
- Problem: Inflation of Type I error rate
- If $\alpha$ = 0.05, each test has a 1 in 20 (5%) chance of Type I Error (rejection of null hypothesis when there s no difference between treatments; i.e, a "false positive" result)


### The Bonferroni adjuctment meaintains the type I error rate, at the cost of a loss of power
- Procedure: keep overall Type I error rate at $\alpha$ by adjusting P needed to reject $H_0$ for each test
- For three tests: (1-$\alpha$)^3 = 0.95, $\alpha$ = 0.017
- Recall: Lower $\alpha$ = higher Type II error rate, lower power

### Analysis of variance (ANOVA)
- allows comparison of 3 or more groups without inflating the type I or type II error rate
- Recall: $\micro$ = population mean 9i.e., the "real" mean if we could measure every individual)
- In ANOVA,
	- $H_0$: