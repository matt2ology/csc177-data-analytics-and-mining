# Linear Regression and Classification Trees

## 1) If a branch separates all records into a single class, then the purity is very low

- [ ] True
- [x] False

## 2) Bias toward selecting an attribute at a node of the decision tree may happen if the attribute has many branches

- [x] True
- [ ] False

## 3) Discretized values in a decision tree may be combined into a single branch if order is not preserved

- [ ] True
- [x] False

Discretized values in a decision tree should not be combined into a single
branch if order is not preserved because it could lead to incorrect
classifications. The order of discretized values often carries important information
about the data. If this order is not preserved when the values are combined
into a single branch, this information is lost, which can negatively impact
the performance of the decision tree.

## 4) XOR function mappings can easily be classified by decision trees

- [x] True
- [ ] False

## 5) Jaccard coefficient ignores 00 combinations since it is meant to eliminate skewness when 00 combinations are common and irrelevant

- [x] True
- [ ] False

The Jaccard coefficient, also known as the Jaccard similarity index, is a
statistic used for comparing the similarity and diversity of sample sets.
The coefficient measures similarity between finite sample sets, and is defined
as the size of the intersection divided by the size of the union of the sample
sets.

The Jaccard coefficient ignores 00 combinations (i.e., instances where both sets
being compared do not have the feature) because these instances do not contribute
to the similarity between the sets. If 00 combinations were common and relevant,
they would artificially inflate the similarity score. By ignoring these combinations,
the Jaccard coefficient provides a more accurate measure of the true similarity
between the sets.

## 6) Higher level aggregations may have more variations than lower level aggregations

- [ ] True
- [x] False

## 7) Dimensionality reduction helps to eliminate irrelevant attributes or reduce possible noise

- [x] True
- [ ] False

Dimensionality reduction techniques, such as Principal Component Analysis (PCA)
or Singular Value Decomposition (SVD), help to eliminate irrelevant attributes
or reduce possible noise in the data by transforming the original
high-dimensional data into a lower-dimensional space.

These techniques work by identifying the directions (or dimensions) in the data
that capture the most variance, and projecting the data onto these dimensions.
The dimensions that capture the least variance are considered to be noise or
irrelevant attributes, and are therefore eliminated.

This process can help to improve the performance of machine learning algorithms
by reducing the complexity of the data, and can also help to prevent overfitting
by removing noise or irrelevant attributes.

## 8) Linear Regression cannot not be applied on every dataset.

- [x] True
- [ ] False

Linear regression assumes a linear relationship between the independent and
dependent variables, which may not hold true for all datasets.

Some reasons why linear regression might not be suitable include:

1. Non-linearity: The relationship between variables is not linear.
2. Heteroscedasticity: The variance of the errors, or residuals, is not constant.
3. Outliers: The dataset contains extreme values that can unduly influence the regression model.
4. Multicollinearity: The independent variables are highly correlated with each other.
5. Non-normal residuals: The residuals, or error terms, do not follow a normal distribution.

In such cases, other types of regression or machine learning models may
be more appropriate.

## 9) Correlations are never distorted if the data is not standardized

- [ ] True
- [x] False

GitHub Copilot: Correlations can indeed be distorted if the data is not
standardized. This is because correlation measures the strength and direction
of a linear relationship between two variables, and this measurement can be
influenced by the scale of the variables.

For example, consider two variables: height in millimeters and weight in
kilograms. The actual correlation between these two variables might be quite
strong, but if you were to calculate the correlation without standardizing the
data first, the large scale of the height variable (millimeters are much larger
numbers than kilograms) could dominate and distort the correlation.

Standardizing the data ensures that all variables have a mean of 0 and a
standard deviation of 1, putting them on the same scale and allowing for a more
accurate calculation of correlation.

## 10) For non-linear relationships, correlations can give correct results

- [ ] True
- [x] False

Correlation measures the linear relationship between two variables.
If the relationship is non-linear, the correlation coefficient may not capture
the strength or direction of the relationship accurately. In other words, even
if there is a strong non-linear relationship, the correlation could be close to
zero, suggesting no relationship. Therefore, correlation is not a suitable
measure for non-linear relationships.

## 11) Multiple choice

### Gini Index

- [ ] Causes Variance
- [ ] 1- (max(P(i│t)) for all i)
- [x] 1- (∑[P(j│t)]^2 for all j)
- [ ] Can overcome disadvantage from skewed lower GINI values
- [ ] Model too simple
- [ ] Cannot classify properly

### Interactions

- [ ] Causes Variance
- [ ] 1- (max(P(i│t)) for all i)
- [ ] 1- (∑[P(j│t)]^2 for all j)
- [ ] Can overcome disadvantage from skewed lower GINI values
- [ ] Model too simple
- [x] Cannot classify properly

### Dividing Gain by SplitINFO

- [ ] Causes Variance
- [ ] 1- (max(P(i│t)) for all i)
- [ ] 1- (∑[P(j│t)]^2 for all j)
- [x] Can overcome disadvantage from skewed lower GINI values
- [ ] Model too simple
- [ ] Cannot classify properly

### Misclassification Error

- [ ] Causes Variance
- [x] 1- (max(P(i│t)) for all i)
- [ ] 1- (∑[P(j│t)]^2 for all j)
- [ ] Can overcome disadvantage from skewed lower GINI values
- [ ] Model too simple
- [ ] Cannot classify properly

### Underfitting

- [ ] Causes Variance
- [ ] 1- (max(P(i│t)) for all i)
- [ ] 1- (∑[P(j│t)]^2 for all j)
- [ ] Can overcome disadvantage from skewed lower GINI values
- [x] Model too simple
- [ ] Cannot classify properly

## 12) Decision trees use a \_\_\_ approach which often is unable to find the best tree

> Decision trees use a **greedy** approach which often is unable to find the best tree.

## 13) A continuous attribute range may be split at the point where the GINI index values is \_\_\_.

> A continuous attribute range may be split at the point where the GINI index values is **minimum**.

A continuous attribute range may be split at the point where the GINI index
value is minimum. This is because the goal of the GINI index is to minimize
the probability of misclassification, so we choose the split point that gives
us the lowest GINI index value.

## 14) The loss function for linear regression is the square of the difference between the original Y value and the \_\_\_ Y value.

> The loss function for linear regression is the square of the difference between the original Y value and the **predicted** Y value.

The loss function for linear regression is the square of the difference between
the original Y value and the predicted Y value.

## 15) \_\_\_ = GINI measure before splitting - GINI measure after splitting

> **Gain** = GINI measure before splitting - GINI measure after splitting.

GINI Gain = GINI measure before splitting - GINI measure after splitting.

## 16) The process of \_\_\_ data before calculating correlations is the best way to get good correlations

> The process of **removing outliers** data before calculating correlations is the best way to get good correlations.

The process of cleaning data before calculating correlations is the best way to
get good correlations.

## 17) BoxPlots are centric to

- [ ] Q1
- [x] median
- [ ] mean
- [ ] mode

Because a BoxPlot visually represents the median of the data as the line in the
middle of the box. The median is a measure of central tendency, and it's less
sensitive to outliers than the mean, making it a good choice for the center of
a BoxPlot.

## 18) Standardization transformation is centric to

- [ ] Mode
- [ ] Highest Value
- [x] Mean
- [ ] Median

## 19) The Mean of the transformed data after standardization becomes

- [ ] double the original
- [ ] no change
- [x] 0
- [ ] 1

The mean of the transformed data after standardization becomes 0 because
standardization involves subtracting the mean of the data from each data point.
This process shifts the entire distribution of data such that it is centered
around 0. This is why the mean of the data after standardization is 0.

## 20) The standard deviation of the new transformed data after standardization is

- [ ] depends on new mean
- [ ] 2 times original standard deviation
- [x] 1
- [ ] factor \* original standard deviation

The standard deviation of the transformed data after standardization is 1
because standardization not only involves subtracting the mean from each data
point (which makes the new mean 0), but also dividing each data point by the
standard deviation of the original data. This process scales the distribution
of the data to have a standard deviation of 1. This is why the standard
deviation of the data after standardization is 1.

## 21) Outliers are values outside the range between Q1 - 1.5 \* IQR and this

- [ ] Median + 3 \* IQR
- [x] Q3 + 1.5 \* IQR
- [ ] Q1 + 1.5 \* IQR
- [ ] Median - 3 \* IQR

The definition of outliers as values outside the range between Q1 - 1.5 _ IQR
and Q3 + 1.5 _ IQR is based on the concept of the Interquartile Range (IQR).
The IQR is a measure of statistical dispersion, and it's calculated as the
difference between the 75th percentile (Q3) and the 25th percentile (Q1)
of the data.

Values that fall below Q1 - 1.5 _ IQR or above Q3 + 1.5 _ IQR are considered
outliers because they are significantly different from the central values of
the data. This rule is a common way to define outliers in a dataset, but it's
not the only way. Other methods might use different multipliers, or they might
define outliers based on standard deviations from the mean.

## 22) Is this statement true? When outliers are important then it is important not to change the current minimum and maximum for normalization

- [x] True
- [ ] False

## 23) Is this statement true? When outliers are not significant then it is important to change the maximum and minimum by subtracting outlier end points from minimum and maximum to get the new minimum and maximum

- [x] True
- [ ] False

## 24) Read this article and provide your summary of the [article](https://statisticsbyjim.com/regression/interpret-r-squared-regression/)

<https://statisticsbyjim.com/regression/interpret-r-squared-regression/>

Also discuss your understanding of the equation:

R2 = SSR/SST = 1 - SSE/SST

(Note: All of you will get full points for this question for answering.
Do bit worry about quality. The purpose is: the paper gives you a new
perspective of how to look at things.)

> $R^2$ is a statistical measure in regression analysis that represents the
> proportion of the variance for a dependent variable explained by an
> independent variable or variables. It's calculated as the ratio of the Sum
> of Squares of the Regression (SSR) to the Total Sum of Squares (SST), or
> alternatively, as 1 minus the ratio of the Sum of Squared Errors (SSE) to
> the SST. A higher $R^2$ value indicates a better fit of the model.
