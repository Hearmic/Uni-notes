### Review

Random Sample
1. Every individual/object ahs an equal chance of being sample
2. Sampled individuals are independent

- Ideal procedure for ensuring a sample is random
- Sample of convenience
  
Categorical Variables: Data fall into distinct groups
- Nominal: categories have no inherent order
- Ordinal: categories ordered along a gradient, but without exact values
- Numerical: Data are quantitative and have magnitude
- Discrete: indivisible numerical units

Biased Sampling: under/overrepresentable (ex: dogs brought to clinics)
A larger sample size is beneficial for achieving high precision of results.

Explanatory (Independent) vs Responsive (Dependent) Variables
Common goal: relate one variable to another
Usually, an explanatory variable (treatment variable in an experiment) affects a response variable.
e.g., radiation dose affects survival probability
Radiation dose = explanatory
Survival = response

In observational studies with no experiment, variables may be assumed (sometimes incorrectly) to be explanatory or response
- e.g., blood pressure (explanatory) affects heart attack rate (response)
There can be more than one explanatory and/or response variable
- e.g., sun exposure and skin pigmentation may affect both skin cancer risk and vitamin D deficiency risk

Observational Study: no experimental manipulation
- Variables are measured and data recorded on already available subjects/units
- Treatments of the explanatory variable "self-assigned."
- Can show association but not cause/effect relationships (often used in "exploratory" research) 

Experiemental Study: individuals are ssigned to treatment groups
- Random assignement ensures that differences between groups are due to the experimental treatment
- Can show cause/effect
- Treatments of the explanatory variable assigned by researchers

Frequency distributions: show the relative or absolute number of times a variable has a given value

- The distribution of a variable in the whole population is its probability distribution
- Almost never known
- Theoretical distributions are used as approximations
- For continuous data: the normal distribution ("bell curve")

If we can approximate the distribution of a variable, we can calculate the odds of measuring a value within a certain range
- Often the basis of statistical hypothesis testing

## Graphing Data
Effective data visualization can portray complex data in an intuitive and easily interpretable way.
### 1. Use the right type of graph
- Single variable: frequency distribution
	- The number (or proportion/percentage) of occurences of each value in the data
- Showing data for a single variable
- For numerical data: use histogram
- Data values split into "bins" of equal width
- Histograms have properties that describe the shape of a frequency distribution
- (Uniform, Bell-shaped, Asymmetric (with -ve skew, Bimodal (also asymmetric with +ve skew)
	- Symmetry (stymmetric as asymmetric)
	- Skew = One "tail" is longer than the other
		- Towards left = negative skew; towards right = positiev
	- Peak = bin surrounded by lower values
	- Mode = Highest Peak
- Outliers are observations well outside the range of values of other observations
	- Should be removed only if investigation reveals them to be errors

- The number of bins can influence a viewer's interpretation of a histogram
	- Bins too small; too much individual data obscures trends
	- Bins too large; loss of information and a distorted 
	- Sturges' "rule of thumb" (a rough guideline):
		- \#bins = 1 + ln(n) / ln(2), rounded up
		- $k = 1 + log_2(n)$
		- Often more bins are needed than Sturges' predicts
		- Use Judgement
		- Use readable numbers
- Left vs Right Closed Bins
	- Data values split into "bins" of equal width but...
	- What do you do with values that are exactly at bin boundaries?
	- e.g., bins 0-10, 10-20, 20-30...where does a 10 go
	- Left closed (right open)-the left of the interval includes the endpoint: 10-20
	- Left closed bins: \[0-10), \[1-20)
- Single variable: Frequency Distribution
- Categorical variable: Bar graph
  
- Showing an association between two variables: the best graph for showing an association between two variables depends on the types of variables involved
	- 1. Categorical explanatory and categorical response
- Contingency table, Grouped bar graphs, Mosaic Plots (width is proportional to sample size), Scatter plot, Strip chart (or dot plot)
- Stacked bars are used to display the proportional, or relative, frequency of occurrence

1. Strip chart 
	- Dots on a graph that have a numerical value on one axis and a categorical value on the other
	- Points are jittered (horizontally spread)
	- Good for smaller data sets because it shows all data points
2. Box plot
	- Uses lines and a box to display the median, quartiles, range, and extreame measurements of the data
	- shows most important features of data set; good for larger data sets where the distributions are unimodal (at least not changing modality)
3. Violin plot
	- Approximates the frequency distribution for each group like a histogram, but the distribution is smoothed and is shown with its mirror image
	- Particularly useful when the distribution is multimodal (more than one peak)
	- Better than box plot in most ways, especially for multimodal distributions
4. Multiple Histograms:
	- Should be stacked vertically for easy comparison
	- Scale shown on the bottom axis
	- Allows easier comparison 

Single variable: Numerical variable: histogram. Categorical variable bar graph

Association between two variables
Two Categorical: Group bar graph or mosaic plot
Two Numerical: Scatter plot

### 2. Show the data
Reveals the distribution of data points (as well as the average)
Can spot extreme values

### 3. Make patterns easy to see
Try different types of graphs to see which reveal patterns most clearly
- Avoid 3-D
- Don't put too much info into one graph

### 4. Report magnitudes honestly
- Baseline for a bar graph should always be zero

### 5. Draw graphical elements clearly
- Label axes: include units
- Unadorned, simple typeface
- Text as large as possible
- Avoid red and green as a distinguishing colour pair
- Use clearly distinguishable graphical symbols

[[Uni-notes/BIOL/2060 Statistics of Biology/Lecture 3 - Jan 13th, 2026]]