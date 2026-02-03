### The four basic steps of hypothesis testing
- $H_0$ 
	- No difference between a parameter and some other value
	- Any difference due to random sampling
- $H_A$
	- The parameter has any value other or > or < than that stated in $H_0$

### 1. State the hypothesis
### 2. Compute a test statistic
### 3. Determined the P-value
### 4. Draw the appropriate conclusions

e.g., "Handedness" in toads.
- Bisazza et al. 1996: 18 common toads (Bufo bufo) captured and tested: 
- Which limb did they most often use to remove a balloon tied to their head
- 14 out of 18 tended to use right hand more often.
- Is right-handedness predominant

- In this case, the parameter of interest = a proportion, p
- H_0: the proportion of right-handed and left-handed toads is the same
- Alternate hypothesis is two-sided
  
- A test statistic is a number calculated from the data that is used to evaluate the null hypothesis
- H_0 predicts 0.5 (1.8) or 9 out of 18, toads will be right-handed
- Actual number = 14 $\to$ This is the test statisitic to be compared with the prediction of 9
- Even if H_0 is true, we could sample 14 right-handed toads purely by chance,
- How likely would that be?

### Null Distribution
- Distribution of possible outcomes for a test statistic, if the null hypothesis is True
- Most statistical tests require that this distribution is known (or assume it to be known)
- If H_0 is true, then each random pick has a 0.5 chance of picking a right-handed toad
- Can create a null distribution by simulating 18 picks thousands of times, and making a frequency histogram of the results:


### P-value:
- The probability of obtaining a test statistic that is as different, or more different, from the predicted result if H_0 is true.

If p is small, we can justify 

1. The value of the test statistic
2. The sample size
3. The P value

### Hypothesis testing based on probability is not immute to error
- If p = 0.03,,,,, we would reject the null hypothesis...
- but there is still a 3% chance that a difference beteen treatments as large, or larger, than the one obsserved could arise due to random sampling alone.
- Rejecting a null hypothesis when it is true (i.e., no real difference between treatments) = a Type I Error
	- A "false positive" result
	- Probability if null hypothesis is true = $\alpha$
- Failing to reject a false null hypothesis = a Type II Error
	- A "false negative" result

### Can reduce likelihood of a Type I Error by selecting a smaller $\alpha$.. but doing so incresases the risk of Type II Error
Unlike Type I Error, risk of Type II Error is difficult to quantify
- Depends on how big the differnce between treatments is, relative to the spread of the data
- Smaller diference and/or more spread -> higher risk of Type II Error
- The power of a statistical test is inversely related to its Type II Erorr risk
- More power -> more ability to reject a false null hypothesis when differences a 


| Type I Error                | Type II Error                    |
| --------------------------- | -------------------------------- |
| Rejecting a null hypothesis | Failing to reject false positive |
|                             |                                  |
|                             |                                  |

|                                |              | $H_0$ is True                      | $H_0$ is False                      |
| ------------------------------ | ------------ | ---------------------------------- | ----------------------------------- |
| Decision about null hypothesis | Don't Reject | Correct inference<br>true positive | Type II Error<br>false negative     |
|                                | Reject       | Type I Error<br>true positive      | Correct inference<br>false negative |
|                                |              |                                    |                                     |
A null hypothesis isn't necessarily True if it isn't rejected
- If P > 0.05, H_0 is consistant with result
- Alternate hypothesis is consistant if P < 0.05


- One/two-sided test: H_0 rejected if test statistic falls within the most extreame 5% of its distribution in one/both "tail" (most extreme 2.5% of any one tail)
- Two-sided test requires that the deviation from H_0 be larger for rejection

### Example of a one-tailed test
- Scientific hypothesis: newborn babies resemble their faters more than other men with similar withnic backgrounds
- Test: show pictures of 1) a newborn baby, 2) its father, and 3) another man, to test subjects and ask the subject to identify the father:
- H_0: no father -child resemblance (prediction 50% correct)
- H_A: yes father -child resemblance(more than 50% correct)
- Even though <50%, null hypothesis cannot be rejected

The decision ot conduct a one- or 