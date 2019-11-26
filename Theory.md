# Statistics Background
## Measures of Center
### Arithmetic Mean
= Mean = Average  
= ∑x/N

#### Advantages
Most accurate measure of center in a dataset without outliers.

#### Disadvantages
Influenced by outliers.

### Outlier
A data value that is either much greater than or much less than the rest of the data and not representative of the rest of the data being considered.

### Median
- Middle value in the sorted list of data values.  
= (N+1)/2  
  - N = number of items in the list
  - If no single middle exists, find the mean between the two middle items.

#### Advantages
Not influenced by outliers.

#### Disadvantages
In a dataset without outliers, a less accurate measure of center.

### Mode
- The most frequently occurring value.
- Much less commonly used than mean and median.
*e.g. The mode of 1, 4, 4, 8, 8, 8, 9 is 8, because 8 appears more times than any other value.*

## Measures of Spread
### Minimum, Maximum, Range
- Measures of Center **does not** indicate the **spread** of data values.
- A simple measure of spread is to report the **minimum** and **maximum** values as well as the **range**.
### Mean Absolute Deviation (MAD)
- The mean of the absolute difference between each value and the value's mean.
- Absolute values (magnitudes) are used to avoid negative distances.
### Variance and Standard Deviation
- **Variance**: Squares the difference between each value and value's mean.
- **Standard deviation**: The square root of the variance.

## Histograms
### Histogram with evenly-sized bins
#### Frequency Distribution
A table that displays how often an outcome occurs for a sample.
- **Construction**: The data set is divided into mutally exclusive classes.
- **Class**: A value of a categorical variable OR an interval of a continuous variable.
- **Frequency**: The number of events or values that fall under each class.
#### Histogram
The most common graphical representation of a frequency distribution.
- **Bin** Splits a continuous variable into a number of class intervals.
  - Includes value equal to or greater than the lower boundary, but less than the upper boundary (**lower <= value < upper**).
### Histogram bin size
#### Goal of Histogram
Estimate the probability density function of the continuous variable on the x-axis, i.e. to be able to **fit a smooth curve over the most rectangles**, while **minimizing the white space under the curve**.
- Multiple bin sizes should be attempted to determine the best distribution of the data.
- Start with a bin size so that the number of bins = +- √N where N is the nubmer of values.
  - E.g. Officer Smith has 15 tickets -> √15 = 3.9 ≈ 4 bins. Since the maximum ticket speed is 28 mph over the limit, a good initial bin size would be 28/(4 bins) = 7 mph bins.
### Distribution Patterns
- **Unimodal**: standard bell curve; one prevalent peak (mode) in histogram.
- **Bimodal**: two prevalent modes.
- **Multimodal**: multiple prevalent mode.
- **Skewed Left**: contains a mode on the right with a tail of low-frequency bins to the left.
- **Skewed Right**: contains a mode on the left with a tail of low-frequency bins to the right.
### Histograms with unevenly-sized bins
- **Unit Area Histograms** should be used to compare likelihoods of two unequally-sized bins.
  - Rectable heights are equal to the bin/frequency/bin size.
## Experiments and Events
### Experiments, outcomes, and sample spaces
- **Experiment**: a procedure that results in one out of a number of possible outcomes.
- **Outcome**: the result of an experiment.
- **Sample Space**: the set of all possible outcomes (e.g for dice: 1, 2, 3, 4, 5, 6).
### Events
- **Events**: Subset of a sample space. E.g. for a dice roll, the event A is rolling an even number.  The event A occurs when a 2, 4, or 6 is rolled.
  - **Compound Event**: Subset of the sample space consisting of more than one outcome. E.g. The event A is compound event since rolling an even number consists of three otucomes.
  - **Simple Event**: Subset with a single outcome. E.g. The event C is rolling a 5 on the die. C is a simple event with a single outcome.
## Discrete Random Variable and their Distributions
### Random Variables
A rule that assigns a number to every outcome in the sample space of an experiment. E.g. in the experiment of a coin toss, a random variable may assign 1 to Heads or 0 to Tails. A random variable is typically defined using a capital letter, such as X = 1 (H) amd X = 0 (T).  
  
Random variables can be **discrete** or **continuous**.
- **Discrete random variable**: take on a countable number of distinct values like the integers between 0 and 100.
- **Continuous random variable**: take on any value within a range of values like the real numbers between 0 and 100.
### Discrete Probability Distributions: Probability Mass Functions
**Probability Mass Function (pmf)**: the probability that a discrete random variable is exactly equal to some value (typically depicted as a table, plot, or equation).
- The notation p(X=x) or p(x) us typically used or the pmf of X.
- The probabilities assigned in a pmf are between 0 and 1, and the total probability must sum 1.
### Probability Distribution: Cumulative Distribtution Function
**Cumulative Distribution Function (cdf)**: of a discrete random variable is the probability that x will fit in a **range** of values.
- Cdf sums each of the pmf values as you go along the table. The last entry should equal 1.
- Notation: F(x) where p(X ≤ x). 
## Properties of discrete probability distributions
### Mean or expected value of a discrete random variable
Mean (≡ Expected Value): the sum of the possible values of X multiplied by the probability of the value.
-	µ = E(X) = ∑▒〖x*p(x)〗
- center of the distribution
### Variance and Standard Deviation of a discrete random variable
- Mean of discrete random variable = center of the distribution.
- Variance of a discrete random variable = spread of the distribution.
  - 	σ^2=V(X)= ∑▒〖(x-μ^2 )*p(x).〗
  - Is a weighted average with probabilities as the weights.
  - units are in *unⅈts^2*.
- Standard deviation of a discrete random variable = measure of the spread in the units of the orginal random variable. It is the square root of the variance.
  - 	σ= √(σ^2 )
## Continuous probability distributions and properties
### Population density function (pdf)
Describes the relative likelihood of all values for a continuous random variable.
*Ex. The amount of time for Casey to do his chores is a random variable, X, where all values between 1 hour and 2 hours are equally likely.*
- **Notation**: f(x)
- The area under portions of the curve given by the pdf provide the probabilities.
- Must be non-negative (+).
- Total area under curve must = 1
### Continuous distribution function (cdf) for continuous random variable
The probability that for any number x, the observed value of the random variable will be at most x or p(X ≤ x).
*Ex. When Casey does the housework, the cdf describes the probability of Casey finishing in time less than or equal to any value x, such as the probability X is less than or equal to 1.5.*
- The notation F(x) is typically used for the cdf.
### Mean, variance, and standard deviation for continuous random variables
-	The mean or expected value E(X), µ, of a continuous random variable X is a measure of the center of the distribution. The mean is a weighted average of the possible values of the random variable, with the pdf providing the weights. Graphically, the mean is where a pivot is placed so that the pdf balances.
-	The variance, σ^2, of a continuous random variable X is a measure of the spread of a distribution. The variance, like the mean, is a weighted average. The variance averages the squared distance of each possible value of X from the mean, with weights provided by the pdf. The units of the variance are the units of X squared. Ex: If X is money, in dollars, the variance of X is measured in dollars squared.
-	The standard deviation, σ, is a measure of the spread of the distribution in the units of the original random variable. The standard deviation is the square root of the variance, σ=√(σ^2 ).
## Specific Distributions
### Binomial Distribution
Models how many times an event occurs in a certain number of trials, with the important assumption that the probability of the event occurs is the same for each trial.
-	*Ex. A basketball player is fouled on a 3 point shot attempt and awarded 3 free throws. A binomial distribution models the number of free throws the player makes out of three. The probability the player is successful on each attempt, based on his season average, is 0.75.*
- **Models**: number of times an event occurs in a certain number of trials.
- **Notation**: X  ~ Bin(n,p)
  - **Bernoulli distribution**: binomial distribution with n=1
  - **Parameters**: 
    - n= number of trials
    - p= probability of the event occurring on each trial; the probability is assumed the same on each trial, and trials are independent.
- **Possible values**: x= 0, 1...n. 
- **Key quantities**
  - **Mean**: n * p
  - **Variance**: n * p(1-p)
### Discrete distributions
Used when binomial distribution is not a good choice. Includes Poisson, negative binomial, and hypergeometric distributions.
#### Poisson distribution
- **Models**: The number of events that occurs in an interval; counts. *Ex. The number of emails received each day*.
- **Notation**: X ~ Poisson(µ)
- **Parameters**:
  -**µ**: Mean(average) number of events per interval.
- **Assumptions**:
  - The average in each interval is the same.
  - The count in one interval is independent of the count in other intervals.
- **Possible values**: x = 0, 1, ...
- **Key quantities**:
  - **Mean**: E(X) = µ.
  - **Variance**: σ^2 = Var(X) = µ.
#### Negative binomial distribution
- **Models**: The number of failures in a sequence of trials before an even occurs a specified number of times. *Ex. The number of non-junk emails received before 10 junk emails are received.*
- **Notation**: X ~ NB(s,p)  
The NB distribution with s = 1 is also known as **geometric distribution**.
- **Parameters**:
  - s: The number of times the event must occur (the number of successes).
  - p: Probability of the event occurring (success) on each trial; assumed the same.
- **Possible values**: x = 0, 1, ...
- **Key quantities**:
  - **Mean**: µ = E(X) = s/p
  - **Variance**: σ^2 = Var(X) = s(1-p)/p^2
#### Hypergeometric distribution
- **Models**: The number of events in a certain number of trials (draws) when each trial is a new selection from a finite population. Once selected, an item is no longer available for selection (known as "draws without replacement"). *Ex. The number of players from the AFC (one of two conferences) randomly selected for a fantasy football team.*
- **Notation**: X ~ Hypergeo(k, n, N)
- **Parameters**:
  - k: Number of trials (draws)
  - n: Number of possible events in the population
  - N: Number in the population
- **Possible values**: x = max(0, n + k - N), ... min(k,n).
- **Key quantities**:
  - **Mean**: µ = E(X) = n.k/N
  - **Variance**: σ^2 = Var(X) = n.k.(N-k)(n-n)/N^2(N-1)
### Normal distribution ≡ Gaussian Distribution 
A continuous probability distribution characterized by a bell-shaped pdf and is symmetric around the mean, µ.
- 68% of the population is within 1 standard deviation of the mean of hte normal distribution.
- 95% of the population is within 2 standard deviations of the mean of the normal distribution.
### Continuous distributions
For situations when the normal distribution is not a good choice.
- Choosing the distribution requires assumpations and key quantities such as mean and variance, shape of pdf.
#### Exponential distributions
- **Models**: Time between events. *Ex. The time until the next bus arrives at a bus stop.*
- **Notation**: X ~ Exp(ʎ)
- **Parameter**: ʎ: Rate of arrivals. *Ex. Buses arrive at a rate of ʎ = 4 per hour.*
- **Possible values**: all values ≥ 0.
- **Mean and variance**: E(X) = 1/ʎ, Var(X) = 1/ʎ^2
#### Beta distribution
- **Models**: Probability for proportions; flexible model for situations where possible values are in a range (generally 0 to 1). *Ex. The percentage of the day that will be sunny.*
- **Notation**: X ~ Beta(α,β)
- **Parameters**: α, β are shape parameters, both must be greater than 0. Sometimes additional parameters a and b are included if the range of values modeled is from a to b rather than 0 to 1.
- **Possible values**: All values between 0 and 1 (or a and b if additiona parameters added).
- **Mean and variance**: E(X) = α/(α + β), Var(X) = α.β/(α + β)^2.(α + β + 1) 
#### Uniform distribution
- **Models**: Possible values fall in arange with equal probabilities; often used to produce a random number. *Ex: The calbe repair technician provides a time window from 9 to 11 am for arrival and all times in the interval are equally possible.*
- **Notation**: X ~ U(a,b)
- **Parameters**: a is the minimum possible value and b the maximum.
- **Possible values**: All values between a and b.
- **Mean and variance**: E(X) = (a+b)/2, Var(X) = (b-a)^2/12.
#### Triangular distribution
- **Models**: Possible values fall in arange and one value in the range is considered most likely. *Ex. The return on investment is thought to range from 0 to 10% with the most likely value 7%.*
- **Notation**: X ~ Triangle(a,c,b)
- **Parameters**: a is the minimum possible value and b the maximum. The value c (which must be in the range of a to b) is the most likely value.
- **Possible values**: All values between a and b.
- **Mean and variance**: E(X) = (a+b+c)/3, Var(X) = (a^2 + b^2 + c^2 + ab - ac - bc)/18 
## Hypothesis Testing
### Statistical significance: An informal introduction
Are the sample statistics extreme enough to infer a conclusion about the population?
- If p-value < 0.05 it is statistically significant at level alpha and two possibilities exist:
  - The null hypothesis is true and the observed data is relatively unusual with an extreme sample statistic that is simply due to chance.
  - The null hypothesis is false and the alternative hypothesis provides a more reasonable explanation for the population parameter.
### Hypothesis Test Errors
- **Type I error**: True null hypothesis is rejected.
- **Type II error**: False null hypothesis is accepted.
## Confidence Intervals
A range of values believed to include a population parameter at a stated level of confidence.
- **Construction**: sample statistic and margin of error (of population mean).
  - **Margin of error (MOE)**: range of values above and below the sample statistic.
    - MOE = z* σ/√n
      - z* = critical value that depends on the type of test (one-sided vs. two sided) and the significance level α.
      - α = probability of a type I error
      - larger sample sizes  = narrower confidence interval (because of smaller MOE).
## Comparing two population means
An analyst commonly seeks to determin whether two samples are from populations with the same population means.
- A **large difference** in two **sample means**, relative to the **sample standard deviations** suggest the population means may be different. The difference depends on:
  - Standard deviations of the two populations.
  - Sample sizes.
- The sample standard deviations estimate the population standard deviations:
  - Relatively large sample standard deviations require a relatively large difference between the sample means to infer a statistically significant difference in population means;
  - Relatively small sample standard deviations require a relatively small difference between the sample means to infer a statistically significant difference in population means.
# Parametric Analysis
## Parameterized population models 
### Parametric Analysis
**Normally distributed**
- **Parameter**: Characteristics of a population
  - Population parameters are almost always unknown ∴ sampling is performed to obtain a parameter’s estimator.
- **Statistic**: Characteristic of a sample
- **Common Statistics and Parameters**
  - **Statistic**
    - ̅x: sample mean
    - s: sample standard deviation
    - s^2: sample variance
    - ̂p: sample proportion
  - **Parameter**
    - µ: population mean
    - σ: population standard deviation
    - σ^2: population variance
    - p: population proportion
### Parametric tests
-	**One-way t-test** - determines whether the hypothesized mean is equal to the true population mean.
-	**Paired t-test** - used to compare two population means in the case where the two samples are dependent.
-	**Two-way t-test** - determines whether the population means are equal.
-	**Analysis of variance (ANOVA)** - determines whether the means of two or more populations are equal.
### Normal Distribution
A bell-shaped probability distribution with two parameters: the mean (µ) and standard deviation (σ).
p(x)=1/(σ√2 π) ⅇ^((-(x-μ)^2)/(2σ^2 ))

### Finding probabilities associated with a normal distribution 
Most situations involve random variables from distributions that are continuous.
  - **Continuous random variable**: a random variable that can take on any value within a range of infinitely many or uncountable values. 
    - Ex: Random variables that represent measurements with continuous values such as body mass index and radius of an O-ring joint are continuous.
The following notation is used when working with normally distributed random variables and other random variables following continuous distributions:
- P(X<a) is the probability that the random variable X takes on a value of at most a.
- P(X>a) is the probability that the random variable X takes on a value of at least a.
- P(a<X<b) is the probability that the random variable X takes on a value between a and b.
### Central limit theorem for means
As the sample size drawn from the population with distribution X becomes larger, the distribution of the sample means X̄ approaches that of a normal distribution, N~(μx,σx/√n), where σx/√n is the standard deviation.
- Calculate probabilities associated with non-normal distributions assuming the sample sizes are sufficiently large.
#### Assumptions
1. **Randomness**: samples must be randomly selected.
2. **Independence**: sample values must be independent of each other
3. **Size**: sample size must be large enough (<30)
4. **10% condition**: sample size must be at most 10% of the population size.
## Student's t-test
### Student's t-distribution (≡ t-distribution)
Obtaining a large enough sample may not be possible or the population standard deviation is unknown. In both cases, the sample standard deviation/sample size^2 can be used in place of the population standard deviation.
- **Student's t-distribution (≡ t-distribution)** used in place of normal distirbutions where the **sample size (n) is small** or the **population standard deviation (σ) is unknown**.
  - **Parameter**: Degrees of Freedom (df) = n-1
    - As df increases, the t-distribution approches the normal distribution with mean = 0 and standard deviation = 1
- **t-statistic**: obtained from a sample assumed to have a t-distribution.
The formula for t-statistic is t=  ( ̅x - μ )/(s/√n)   where s is the sample standard deviation, ̅x is the sample mean, µ is the population mean, and n is the sample size. 
### Student's t-test (≡ t-test)
- Method of hypothesis testing for the **mean of a sample** taken from a **normally distributed population** when the **population standard deviation is unknown**.
- **Purpose**: To determine if the difference between the sample mean and the hypothesized population mean is statistically significant.
  - **Null hypothesis**: hypothesis of no difference
  - **Alternative hypothesis**: the claim contrary to the hypothesis
    - The alternative hypothesis ultimately depends on what the study claims. If the study claims that:
      - The parameter > hypothesized value: the hypothesis test is **right-tailed** and H_a:μ>μ_0. 
      - The parameter < hypothesized value, the hypothesis test is **left-tailed** and H_a:μ<μ_0. 
      - The parameter has a different value, then the hypothesis test is **two-tailed** and H_a:μ≠μ_0. 
- The **significance level** (**α**), is the probability of rejecting the null hypothesis when the null hypothesis is actually true. Thus, if the p-value is less than the significance level, sufficient evidence exists to reject the null hypothesis. Common values for α are 0.05 and 0.01.
### Confidence interval for a t-distribution
The confidence interval for a population mean was defined as (x - ̅z* σ/√n, x + ̅z^ σ/√n)
  - In practice, however, the population standard deviation is rarely known. Thus, confidence intervals using the t-distribution are more useful because the sample standard deviation is used instead.
The t-confidence interval is given by  ( ̅x - t* s/√n, ̅x + t* s/√n)
  - where t* is the critical value that depends on the type of test, degrees of freedom, and significance level. The values for t* for common significance levels given selected degrees of freedom is shown in the table below.
## Comparing 2 samples: 2-sample t-test
### Two-sample t-test
The t-test discussed analyzes the **difference between the sample mean and the hypothesized value of the population mean**. A similar method exists to compare the means of two different populations. The two-sample t-test is used to determine if a statistically **significant difference exists between two population means**. Two types of two-sample t-test exist: paired and unpaired.
#### Paired t-test (≡ dependent t-test)
- A sample taken from **one population is exposed to two different treatments**. 
- The main idea is that measurements are recorded from the **same group**. 
  - *Ex: A group of professional cycling athletes is selected for a study on the effects of caffeine dosage on exhaustion times. The populations are the cyclists for each of two dosages. The samples are the measured exhaustion times for each dosage, which implies dependence because the measurements were taken from the same group.*
  - To obtain probabilities for a paired t-test, the paired R² is needed. The formula involves finding the mean and standard deviation of the differences between corresponding measurements:
t=( ̅d - μ_d)/(s_d/√n)
Where s_d  is the sample standard deviation of the differences, ̅d is the mean difference between the samples, and n is the sample size. 

#### Unpaired t-test (≡ independent t-test)
- A sample taken from **one population is not related to a different sample taken from another population**. 
- In contrast to the paired t-test, measurements from an unpaired t-test are recorded from **different groups** when exposed to the same treatment. 
  - *Ex: The effect of caffeine intake on exhaustion times is studied by measuring the exhaustion times of a randomly selected group of 9 professional cyclists taking caffeine pills and another group of 9 cyclists not taking caffeine pills. The two populations are all cyclists taking caffeine pills and those who are not taking the pills. The samples are the measured exhaustion times from the two groups, each with 9 cyclists, which implies independence because the times are for two different groups of cyclists.*
  - The t-test statistic for unpaired data is different from that of paired data. The formula involves subtracting the means of the two samples:
( ̅x_1 - ̅x_2-(μ_1 - μ_2))/√((s_1^2)/n_1 +(s_2^2)/n_2 )
where ̅x_1,  s_1, and n_1 are the mean, standard deviation, and sample size of the sample drawn from the first population respectively; and x_2, s_2, and n_2 are the mean, standard deviation, and sample size of the sample drawn from the second population. Since measurements are not subtracted, the sample sizes are not necessarily the same. The degrees of freedom are ⅆf = n_1 + n_2 - 2. Although μ_i - μ_2 can be any number based on the hypothesized means for the two populations, most of the time, the accepted difference between the means of the populations is 0. Finally, the formula for the t-statistic above assumes that the variances are unequal. In most practical instances, the homogeneity of variances should be verified using the Fisher's F-test before performing the unpaired t-test. 
## Comparing 3+ samples: ANOVA
### Comparing 3 or more populations
- *Ex: A researcher wants to classify iris species based on sepal length by using a method called k-means clustering. As a first step, the researcher checks whether the mean sepal length differs among three species of iris: setosa, virginica, and versicolor. A possible method to compare the means is to perform three unpaired t-tests: one between setosa and versicolor, another between setosa and virginica, and finally between versicolor and virginica.*
Analysis of variance (ANOVA) controls for the errors associated with comparing multiple population means. Analysis of variance (ANOVA) determines whether a statistically significant difference exists among the means of three or more populations. Equivalently, ANOVA tests for an association between a categorical predictor variable and a response variable. 
- *Ex: In the iris study, the predictor variable is the type of species and the response variable is sepal length. Data scientists and statisticians often refer to a categorical predictor variable as a factor and a possible value of a factor as a level. A factor can be a continuous variable partitioned into intervals commonly referred to as bins. *
#### The F-statistic
The ratio of between-group variance to within group variance.  
A number of quantities are involved when calculating the F-statistic:
- The **sum of squares between groups (SSB)**: measures the between-group variablility.
- The **mean of squares between groups (MSB)**: measure the between-group variance.
- The **sum of squares within groups (SSW)**: measures the within-group variability.
- The **mean squares within groups (MSW)**: measures the within-group variance.
Since MSB and MSW represent the between-group variance and within-group variance respectively, F = MSB/MSW
#### One-way ANOVA
Compares the means of three or more groups of one predictor variable.
- Null hypothesis = all of the group means are equal.
## Linear Regression
### Linear regression model
Is a linear function used to predict the value of one variable using the values of one or more variables.
- In a linear regression involving two variables:
  - **response variable** = the variable being modeled or predicted
  - **predictor variable** = the variable used to predict the response.
    - *Ex. A researcher wishes to construct a linear model that a student's grades given the number of hours spent studying. THe predictor variable is the number of hours spent studying and the response variable is student grade*.
- A scattor plot displays a set of predictor and response varaible pairs as data points.
  - The predictor variable X goes on the horizontal axis
  - The response variable Y goes on the vertical axis
  - Assuming the data represents a population, the population linear regression function is given by E(Y)=β_0+β_1 X, where E(Y) is the expected value of Y, and β_0  and β_1 are unknown population regression parameters. 
    - **Absoulte error ∈** = The difference between the true value Y and E(Y).
#### Method of least squares
Derives a linear regression model by minimizing the sum of squared errors.
#### Sample linear regression function
Are the predicted or fitted response values based on the simple linear regression model.
#### Linear regression fitted value
Is the predicted value of Y for the ith smaple value of X based on the linear regression line.
#### Linear regression residual
Is the estimated regression error based on the sample linear regression line.
### T-Test for linear regression
Check if β_1 ≠ 0 (alternative hypothesis).
## Parametric vs. nonparametric statistics
### What is the difference between parametric and nonparametric methods?
- **Student's t-test**: compares the means of two populations.
  - *Ex. The mean heights of men and women using the sample data.*
  - **Assumptions**: Normal distribution for each population (Parametric).
- **Parametric Method**: Makes inferences based on assuming some statistical distribution of a population or for a statistic. (Normal distribution).
- **Non-Parametric Method**: Makes inferences based on data requiring fewer assumptions about the statistical distribution of the population (skewed).
### Parametric
- **Advantages**: More powerful if the assumptions of the parametric test are true.
- **Disadvantages**: Require large samples. Samples must approximate a distribution.
### Nonparametric 
  **Use**: When data is small
