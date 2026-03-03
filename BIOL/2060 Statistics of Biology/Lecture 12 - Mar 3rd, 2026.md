### Hypothesis testing with continuous response variable that normal distribution
- Main focus for remainder of the course: 
	- t-tests
	- Analysis of Variance (ANOVA)
	- Correlation
	- Regression

The distribution of means, Y for A is normal distribution

### Z-standardization can be performed on the distribution of Y to calculate ?
So we have to substitute SE_Y, the standard error estimate (=S/root(n)), for sd, the , statistic is called

t = y - u \ SE_Y

- t has a slightly different distribution from Z ( which is normally distriuted)
- It is fatter in the tails because it is more variable
- SE_Y varies from sample to sample because of s (unlike sd)

### The shape of the T-distribution varies with the sample
- Degrees of freedom = n - 1
- Smaller n -> greater deviation from normal distribution

### The number of df determines the 95% critical value of T
- Notation: $t_{0.05(2), 9}$ = 2.262 = the critical value of t

### While exact P values for a given value of T can be calculated 
eg., for t = 2.5 with 9 df, 2-tailed P
Excel: 2*(1-T.DIST(ABS(2.5)9,True))
R: 2*(1-pt(q=abs(2.5), df=9))

# Using T to calculate Confidence Intervals

### The T distribution can be used to calculate a more accurate 
$$-t_{0.05(2),df} < \frac{\overline{Y}-\micro}{SE_\overline{Y}} < t_{0.05(2),df}$$
$\micro = \overline{Y} \pm (SE_\overline{Y})(t_{0.05(2),df}$

### A one-sample T-test is used to test the hypothesis that a sample is from a population with a specified mean, $\micro _0$
- $H_0$ the true mean is $\micro_0$
- $H_A$ the true mean is not $\micro_0$

$$SE_{\overline{Y}} = \frac{\sigma}{\sqrt{n}}$$



 
