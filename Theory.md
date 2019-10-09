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
*e.g. The mode of 1, 4, 4, 8, 8, 8, 9 is 8, because 8 appears more times than any other value. *

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
