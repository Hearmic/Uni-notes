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
$\micro = \overline{Y} \pm (SE_\overline{Y})(t_{0.05(2),df})$

### A one-sample T-test is used to test the hypothesis that a sample is from a population with a specified mean, $\micro _0$
- $H_0$ the true mean $\micro$ =  $\micro_0$
- $H_A$ the true mean ($\micro$) =/= $\micro_0$
- Test statistic = t = Y - u_0 / SE_Y, with df = n - 1
- 95% CI: 

$$SE_{\overline{Y}} = \frac{\sigma}{\sqrt{n}}$$
### Larger sample reduces the risk of type II error
- Larger sample -> greater ability to reject H_0 when there is a small, but real, difference between $\overline{Y}$ and $\micro$ 

### Assumptions of the one-sample test
- Data are a random ample
- Variable has a normal distribtion
	- t-test is robust (remains accurate) with variables that show moderate deviations from normality

### When to use Z vs T
1. You are given a population mean ($\micro$) and population standard deviaton ($\sigma$) and asked to calculate the probability of one or more values and/or a range of values: 
	- Z = (x-$\micro$)/$\sigma$
2. You are given a population mean ($\micro$) and population stand deviation and asked to calculate the probability of a sample 
	- Z = (Y-)

### Paired vs Two sample T-test are used to compare the means of two different samples
- Two-sample (unpaired) test: each sampled unit is assigned to one of two treatments
- Paired test: each sample unit has both treatments applied to it
- e.g., two different medical studies testing the effect of a drug on blood pressure: 

Individuals are recruited and randomly assigned to one of two groups: drug or placebo

Pairs of siblings are recruited; within each pair, one is assigned to the drug treatment, the other to the placebo
Increases power by reducing variations unrelated to treatment.

## Paired T-test
In a paired design, sampling units may be individuals or non-
- If individuals may be sampled before and after treatment;
	- Patients were measured before and after hospitalization
	- Water quality of lakes measured before and after the introduction of a pollutant
- Or, different parts of the same individual may be treated

### In a paired T-test, the null hypothesis is that the mean difference between paired measurements is a specific value (not necessarily zero)


