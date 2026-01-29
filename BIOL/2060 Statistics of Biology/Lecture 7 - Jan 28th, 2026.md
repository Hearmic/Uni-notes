### Review

- Addition Rule 
-  General Addition Rule
- Rule of Multiplication (independent)
- General Rule of Multiplication (dependent events both occur)
- Law of total probability

### Bayes' Theorem 
$$PR[A|B] = \frac{Pr[B|A]\ Pr[A]}{Pr[B]}$$
Example: Down syndrome (DS) is a chromosomal condition that occurs in ~1 in 100 pregancies
- A previously common test used to identify down tyndrome in a fetus is called the triple test, which screens for levels of three hormones in maternal blood at around 16w weeks of pregnancy.
- Probability that a fetus with DS will be correctly identified as having DS is 0.60 (sensitivity or true positive)
- Probability of incorrectly identifying a normal fetus as having DS is 0.05 (false positive)
- What is the probability that a fetus identified as having DS actually has DS?

$$Pr[DS\ |+ result]\frac{[Pr[+ result\ |\ DS\ ]\ Pr[DS]}{Pr[+ result]} = \frac{0.60 * 0.001}{?}$$

$$Pr[+ result] = Pr[DS] Pr[+results | DS] + Pr[no DS] Pr[+result | no DS] = 0.001*0.6 + (1-0.001)*0.05 = 0.05055$$
### Noninvasive prenatal screening (NIPS)
- Tests using sequencing of cell-free fetal DNA sequences isolated from a maternal blood sample

#### Random requires to criteria
- 1. Every individual in the population being sampled must have an equal chance of being sampled
- 2. Sample individuals are all independent

### Green Lacewings, Chrysoperla spp., were at one time considered to be a single species
- Now > 15 different species rcognized, all physically similar but with different mating songs
- Songs distinguished by: Length of standard repeating unit (SRU)
- Volley period
- Remales recognize the songs of. males of their own species -> prevents hybridization

#### Sonograms of 7 lacewing species
- Hypothesis: more complex songs are easier for females to recognize
- Prediction: in species with more complex songs, females should make fewer mistakes
- Experiment: compare the "choosiness" of females of Species D, which has a "complex" song (long SRU) with females of Species E that has a "simple" song (short SRU)

- Treatment 1: 30 females of Species D offered a choice between a male of their own and a male of a third, random species
- Treatment 2: 30 females of Species E offered same choice
- Female choice = the response variable
- Results
	- Species D females chose their own species 29/30 times (97%) whereas Species E females chose their own species 16/30 times (53%)
	- Conclusion: species with more complex songs are less likely to hybridize with other species than those with simple songs
### Pseudoreplication
- When individual measurements that are not independent are analyzed as if they were independent.
- The conclusion was that there is a difference between two different types of species (long SRU vs short SRU)
- Even though there were a lot of replicates, there was only one female of each type in the experiment
- The conclusion about long- vs short -SRU species is based on a sample size 1 of each, not 30
	- It might be justified to conclude that Species D is more discriminating than Species E, but that could be due to any number of factors (not necessarily SRU)

### Hypothesis testing in statistics

Does a parameter (estimated from a sample) differ from some null expectation?
Are they really different, or is the observed?
The magnitude of difference is unimportant

Example: Salk vaccine trial, 1954
401,974 elemntary-school students in double-blind trial
- Half received an experiemtnal polio vaccine
- Other half received saline

