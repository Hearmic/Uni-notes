### The two-sample t-test is used to compare the means of two independent samples

If the original variable is normally distributed, the distribution of sample means will also be normal.
If we take pairs of randomly- generated samples and calculate the difference between their means
...the sampling distribution of those differences will also be normal.
![t-test : Two Independent Samples > Matistics](https://matistics.com/wp-content/uploads/2022/03/13-Hypothesis-t-test-2-independent-sample.jpg)

### Pooled sample variance
where, df1 and df2 are the degrees of freedom of Samples 1 and 2; df1 = n1 -1; df2 = n2 - 2
s1^2 and s^2 are 
$$s_p^2 = \frac{df_1s_1^2+df_2s_2^2}{df_1 + df_2}$$
### And then the standard error of the difference between means, $SE_{\overline{Y_1}-\overline{Y_2}}$

### 1. Formulate hypothesis
$$SE_{\overline{Y_1}-\overline{Y_2}} = \sqrt{s_p^2(\frac{1}{n_1}+\frac{1}{n_2})}$$
- Hypotheses for a two sample t-test
- H0 = u1 = u2 
- H_A = u1 =/= u2
- Two-sample t-test calculates a t statictics based on the differnece between observed sampled means
$$t = \frac{\overline{Y_1}-\overline{Y_2}}{SE_{\overline{Y_1}-\overline{Y_2}}}$$
### 2. Calculate $s_p^2 = \frac{df_1s_1^2+df_2s_2^2}{df_1 + df_2}$

### 3. Calculate $SE_{\overline{Y_1}-\overline{Y_2}} = \sqrt{s_p^2(\frac{1}{n_1}+\frac{1}{n_2})}$

### 4. Determine Critical Value and P-value
$df = df_1 + df_2 = n_1 + n_2 - 2$

### 5. Draw the appropriate conclusions



### Calculating a Confidence Interval for the differnece between two means
$$(\overline{Y_1}-\overline{Y_2})-SE_{Y_1-Y_2}*t_{0.05(2).df} < \micro_1 - \micro_2 < (\overline{Y_1}-\overline{Y_2})+SE_{Y_1-Y_2}*t_{0.05(2).df}$$


## Lecture 14 - Two-sample t-test assumptions
1. random sample
2. Homogeneity of variance
	- A requirement of the two sample t-test is that s and s^2 are the same in the populations being compared
	- Two-sample t-test is robust up to a 3-fold difference in s if 
		- Sample sizes are similar
		- Sample size are > 30
	- If difference is greater than 3-fold and /or sample sizes are not similar and/or are < 30, two-sample t-test is unreliable
3. Independent samples
4. Normal distribution

### The F-test can be used to compare the variances of two samples
- H_0 : $\sigma_1^2 = \sigma_2^2$

- Test statistic = F (aka an "F ratio") = s1^2/s_2^2, where s1^2 is the larger sample variance
- Critical values

### Larger variance is in numerator -> F-test is one-tailed 
Below: Table D - critical value

ex) if n1 = 7, n2 = 9
and s1^2 > s2^2
df1 = 6, df2.= 8
$F_{0.05(2)df1,df2}$

### The F-test can be 

### As can Levene's test for homogeneity of variance
- Can be applied to more than two groups: 
- H_0 = $\sigma_0^2 =\sigma_1^2 = \sigma_2^2 = ... etc$
- H_A = at least one of $\sigma^2$ is different from the others
- More robust to deviations from normality
- Test statistic = W = 


### Welch's approximate T-test can be used if variance are not similar
$$t = \frac{(Y_1 - Y_2) - (\micro_1 - \micro_2)}{\sqrt{\frac{s_1^2}{n_1} + \frac{s_2^2}{n_2}}}$$

Welch's confidence interval: ()


### T-test assumptions 3) Independent samples
1. Every individual in the population being sampled must have an equal chance of being sampled
2. Sampled individuals must be independent

If units are not independent, pseudoreplication will occcur
- Fish in the same river are not independent 
	- Survival of salmon is affected by many factors that could vary in each river
- Rivers (not individual salmon) are the independent sampling units
- Conduct two-sample t-test using proportion of salmon surviving (n=6 in each treatment) 

### Indirect comparisons between samples should be avoided
Do babies resemble their fathers more than their mothers/
asked volunteers to idenify parents of babies from a choice of three photos
H_0: correct identifications made 33% of the time
results: Mean % correct for fathers > 33% (P < 0.05)
Mean for mothers not different from 33% (P < 0.05)

Concluded babies' resemblance to their fathers is greater than that to their mothers

Problem: means for fathers and mothers not significantly different in direct comparison (overlap of each confidence intervals)

### Confidence intervals can sometimes be used in Lieu of hypothesis tests, but not always.



