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
Are they really different, or is it observed?
The magnitude of the difference is unimportant

Example: Salk vaccine trial, 1954
401,974 elementary-school students in a double-blind trial
- Half received an experimental polio vaccine
- The other half received saline
Paralytic polio developed:
- in 0.016% of the vaccinated group = 32 students
- in 0.057% of the saline group = 115 students

What is the probability of seeing this difference due to a random sample alone?
	- Less than 1 in 100,000
Conclusion: it works - i.e., reduces the incidence of disease

In statistical hypothesis testing therea re just two hypothesis: "Null" and "Alternative"
- Null hypothesis: there is no real difference between treatment groups (i.e., between population parameters)
- Alternate hypothesis: there is a real difference between groups
	- i.e., population parameters, such as mean, are different

Scientific vs Statistical Hypthesis
- S are statements about the existence and possible causes of phenomena
- will usually have multiple alternative hypotheses
	- Rejection of one does not support one specific alternative
	- Each hypothesis has to be tested independently, using experiment and/or observation

#### A statistical null hypothesis, H_0 states there is no difference between a parameter and some other value
- could be another parameter
- H_0: The infection rate in vaccinated children is the same as the infection rate in non- vaccinated children
	- Param 1: the "true" infection rate of all children that will ever be vaccinated
	- Param 2: the "true" infection rate of all children who were never vaccinated
- Could be a specific number, based on expectation or theory

H_A: The infection rate in vaccinated children is different from the infection rate in non-vaccinated children
H_A: The mean body temperature of healthy humans is not 37˚C

Note that alternate hypothesis is non-specific
- The direction of the difference is specified


Null hypothesis
- 
Alternate hypothesis
- The parameter has nay value other or > or < than that stated in H_0

### Quiz:
Pr[DS] = 0.001
Pr[+ result | DS] = 0.60
Pr[+ result | no DS] = 0.05
Pr[+ result] = Pr[DS] Pr[+results | DS] + Pr[no DS] Pr[+result | no DS] = 0.001*0.6 + (1-0.001)*0.05 = 0.05055
$$Pr[DS\ |- result] = \frac{Pr[DS]\ Pr[-result | DS]}{Pr[-result]} = \frac{0.001 * (0.001 * (1 - 0.05055))}{1 - 0.05055}$$