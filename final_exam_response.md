# Final Exam

## 1

```md
K-means has problems (or issues) when the data contains `BLANK`
```

K-means has problems (or issues) when the data contains `outliers`

## 2

```md
A neural net may as well be accomplished with just one `BLANK`
```

A neural net may as well be accomplished with just one `layer`

## 3

```md
Only `BLANK` algorithm out of the algorithms listed below can perform both
classification and regression
```

- [x]KNN
- [ ]Linear Regression
- [ ]Logistic Regression
- [ ]Naive Bayes

## 4

```md
`BLANK` of error is the main important step that helps approximate the weights
in a neural net
```

`Backpropagation` of error is the main important step that helps approximate
the weights in a neural net"

## 5

```md
Bias is associated with `BLANK` as opposed to overfitting
```

Bias is associated with `underfitting` as opposed to overfitting.

## 6

```md
Sampling is the main technique for `BLANK` the size of data from the population
size to a manageable size.
```

Sampling is the main technique for `reducing` the size of data from the
population size to a manageable size.

## 7

```md
The probability of rain is (2%) but grass is wet 10% of the time.
There is a 91% chance rain makes grass wet.
Then the probability of rain when the grass is wet is `BLANK`.
```

---

The probability of rain is (2%) but grass is wet 10% of the time.
There is a 91% chance rain makes grass wet.
Then the probability of rain when the grass is wet is `18.2%`.

This is calculated using Bayes' theorem:

```md
P(Rain|Wet) = P(Wet|Rain) _ P(Rain) / P(Wet)
= 0.91 _ 0.02 / 0.10
= 0.182 or 18.2%

To calculate the probability of rain when the grass is wet, you can use Bayes' Theorem:

\[ P(\text{Rain | Wet grass}) = \frac{P(\text{Wet grass | Rain}) \times P(\text{Rain})}{P(\text{Wet grass})} \]

Given:

- \( P(\text{Rain}) = 0.02 \) (2%)
- \( P(\text{Wet grass | Rain}) = 0.91 \) (91% chance rain makes grass wet)
- \( P(\text{Wet grass}) = 0.10 \) (10% of the time grass is wet)

Substitute these values into the formula:

\[ P(\text{Rain | Wet grass}) = \frac{0.91 \times 0.02}{0.10} \]

\[ P(\text{Rain | Wet grass}) = \frac{0.0182}{0.10} \]

\[ P(\text{Rain | Wet grass}) = 0.182 \]

So, the probability of rain when the grass is wet is \( 18.2\% \).
```

## 8

```md
Deep learning uses mostly the `BLANK` activation function in the hidden layers.
```

Deep learning uses mostly the `ReLU (Rectified Linear Unit)` activation
function in the hidden layers.

## 9

Match the following approaches based on centroid-based clustering using K-Means

Centroid-based clustering

- [ ] creates a tree of clusters
- [ ] grouping is done by gaussian distribution
- [x] organizes the data into non-hierarchical clusters
- [ ] has difficulty with data of varying densities and high dimensions
- [ ] has trouble clustering data when clusters are of varying sizes and density

Density-based clustering

- [ ] creates a tree of clusters
- [ ] grouping is done by gaussian distribution
- [ ] organizes the data into non-hierarchical clusters
- [x] has difficulty with data of varying densities and high dimensions
- [ ] has trouble clustering data when clusters are of varying sizes and density

Distribution-based Clustering

- [ ] creates a tree of clusters
- [x] grouping is done by gaussian distribution
- [ ] organizes the data into non-hierarchical clusters
- [ ] has difficulty with data of varying densities and high dimensions
- [ ] has trouble clustering data when clusters are of varying sizes and density

Hierarchical Clustering

- [x] creates a tree of clusters
- [ ] grouping is done by gaussian distribution
- [ ] organizes the data into non-hierarchical clusters
- [ ] has difficulty with data of varying densities and high dimensions
- [ ] has trouble clustering data when clusters are of varying sizes and density

K - Means Clustering

- [ ] creates a tree of clusters
- [ ] grouping is done by gaussian distribution
- [ ] organizes the data into non-hierarchical clusters
- [ ] has difficulty with data of varying densities and high dimensions
- [x] has trouble clustering data when clusters are of varying sizes and density

## 10

```md
What are the characteristics of an Artificial Neural Network (ANN)?
```

- [x] It can handle redundant and irrelevant attributes because weights are automatically learnt for all attributes
- [x] It is sensitive to noise in training data
- [x] It represents a hierarchy of features at multiple levels of abstractions
- [ ] It is extremely fast in handling missing attributes

## 11

```md
Which of the following evaluation metrics cannot be applied in case of logistic
regression output to compare with target?
```

- [x] Mean-Squared-Error
- [ ] AUC-ROC
- [ ] Accuracy
- [ ] LogLoss

## 12

```md
In k-NN what will happen when you increase/decrease the value of k?
```

- [ ] The boundary becomes smoother with decreasing value of K
- [ ] Smoothness of boundary doesn’t dependent on value of K
- [x] The boundary becomes smoother with increasing value of K
- [ ] None of these

## 13

```md
Which of the following is an example of predicting regression?
```

- [ ] Predicting wind velocities
- [x] Predicting sales amounts of new product based on advertising expenditure.
- [ ] Time series prediction of stock market indices
- [ ] Predicting tumor cells as benign or malignant

## 14

```md
Think on your feet!:

Explain in your own words, how can different proximity measures be employed
experimentally, and results compared to decide on a suitable proximity
measure when performing KNN?
```

To find the most suitable proximity measure for K-nearest neighbors (KNN),
different distance metrics like Euclidean or Manhattan can be experimentally
applied to a dataset with known outcomes. By comparing the algorithm's
performance using metrics such as accuracy and precision, data scientists and
analyst can identify the most effective proximity measure for a given dataset
and task. This empirical approach aids in selecting the optimal distance metric
for KNN based on performance results.

## 15

```md
Explain the following (think on your feet!):

In the neural net topic, the back propagation of error is used iteratively in a
cycle to update the weight and other parameters. a

When does the updating stop? The most common conditions are one of the following:

When the new values of the bias and weights are only incrementally different
from those of the preceding iteration

When the misclassification rate reaches a required threshold

When the limit on the number of runs is reached

Please explain the above three conditions with your own intuition what they
mean and why these conditions may exist.
```

## 16

```md
Explain K-Means Clustering Algorithm and its Limitations.
```

K-Means is a grouping method that organizes similar data points into clusters.
It works by repeatedly assigning points to clusters based on their similarity
and updating the cluster centers until convergence. It is often used for tasks
like customer segmentation or image compression; however, K-Means has drawbacks,
for it assumes clusters are round-shaped and of similar size, making it less
effective with elongated or unevenly sized clusters. It requires knowing the
number of clusters beforehand, is sensitive to initial conditions, and struggles
with outliers. These limitations should be considered when using K-Means for
clustering tasks.

## 17

```md
Explain SVM and what are slack variables in SVM?
```

SVM (Support Vector Machine) is a machine learning algorithm used for
classification and regression tasks. It works by finding the optimal hyperplane
that best separates different classes in a dataset, maximizing the margin
between them.

Slack variables in SVM are introduced to handle cases where a clean separation
between classes is not possible. In real-world scenarios, data points may not
always fall neatly on one side of the decision boundary. Slack variables allow
for some misclassification by assigning a penalty for data points that fall on
the wrong side or within the margin. They help SVM find a balance between
achieving a broader margin and allowing for a certain degree of classification
error, making the model more flexible in handling complex datasets.

## 18

```md
What is ROC Curve? (3 points)

For the following Table Calculate the Precision, Recall and F-1 Score
(F measure) (using the chap4 slides on imbalanced classes on Accuracy,
Precision, Recall and F-1 Score in Classification) from the matrix: (4 points)

Explain in detail, if necessary, by providing an example with a change in data
in the confusion matrix, how the F-1 score has more value than the Accuracy
measure for a specific use case, where accuracy score may be misleading.
Details of working are as important as your answer. (3 points)

|                     | Predicted Positive | Predicted Negative |
| ------------------- | ------------------ | ------------------ |
| **Actual Positive** | TP = 400           | FN=300             |
| **Actual Negative** | FP = 400           | TN=900             |
```

**What is ROC Curve?**




## 19

```md
Problem Solving:

The following set of records have the following classes:

Answer the question below with respect to the following table.
Provide clear steps.

| Height | Weight | Class |
| ------ | ------ | ----- |
| low    | low    | no    |
| high   | low    | yes   |
| high   | medium | no    |
| medium | medium | no    |
| low    | high   | yes   |
| medium | high   | yes   |

Explain how correction is applied when probabilities are zero to get non-zero
probabilities in Naive Bayes classification. (5 points)

Using Naive Bayes method, find the class for the test record with height
'medium' and weight "high".

(a) with the traditional naive bayes independence condition, and (6 points)

(b) without the independence condition (6 points)

Compare and explain the reasons for the differences and what the differences
mean intuitively. (3 points)

Show all working. You may do your working on paper and upload your working
(if you are using a cell phone camera app, make sure the writing on each page
is very clear and you upload a PDF file).
Details of working are as important as your final answer.
```
