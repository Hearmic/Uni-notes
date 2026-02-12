
Genetic model
Poisson model


### The Poisson distribution
- Clumped, Random, Dispersed (uniform)
$$Expected\ frequency = \frac{e^{\micro} \micro X}{X!} * n$$
- One degree of freedom is lost for each estimated category
- Need to include the expected frequency of everything equal to 

- Contingency analysis tests for an association between two or more categorical variables


### Relative risk
- the probability of an outcome in a treatment group divided by its probability in a control
- Use when you have a cohort study or randomized controlled trial (known total population/incidence).
$$RR = \frac{Risk\ in\ exposed}{Risk\ in\ unexposed} = \frac{a/(a+b)}{c/(c+d)}$$
### Case control
- A sample of individuals that have a condition of interest is compared with a sample of individuals that don't
- Individuals are selected based on the response variable (not explanatory)

### Odds ratio 
- As an alternative to relative risk
- Odds: ratio of successes: failures (or Pr[A] / Pr[not A])
- Odds ratio, OR = odds in the "treatment" group / odds in the "control" group
- Use you have a case-control study (starting with outcomes) or in logistic regression analysis.
$$OR = \frac{Odds\ in\ exposed}{Odds\ in\ unexposed} = \frac{a/b}{c/d} = \frac{ad}{bc}$$

### Chi-square contingency test
- Used to determine if an association between two or more categorical variables is due to chance
- Degrees of freedom: (# Rows  - 1)(# Columns - 1)
$$X^2 = \sum \frac{(O-E)^2}{E}$$
- Assumption of the $X^2$ contingency test
	- No more than 20% of cells can have an expected frequency < 5
	- No cell can have expected frequency < 1

### Fisher's exact test
- used when a 2x2 contingency table has row expected frequencies
- The probabilities of all table as or more extreme than the one observed are calculated
$$P = 2 * \sum \frac{R_1!\ R_2!\ C_1!\ C_2!}{a!\ b!\ c!\ d!\ n!}$$
where: R and C are row and column totals, a, b, c and d 

### Normal Distribution
- Centered on a mean
- Symmetrical shape

$$f(Y) = \frac{1}{√ 2 \pi \sigma } e^{- \frac{(x-\micro)^2}{2 \sigma ^2}}$$
The number of standard deviations around the mean (on X axis) is known as Z axis, or Z value

#### Sample Mean
- if the population has a normal distribution and mean $\micro$, then the distribution of sample means Y 
- The SEM is the equivalent of calculating standard deviation for a sample mean
- SE gets smaller with larger n
- The probabiity of drawing a sample mean 