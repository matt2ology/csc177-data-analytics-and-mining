# Quiz4 - KNN, Logistic Regression (Logit), Association Analysis and Miscellaneous

## Question 1

    Which of the following statements is true about the k-NN algorithm?

    1) k-NN performs much better if all of the data have the same scale.
    2) k-NN works well with a small number of features (X's) however, struggles
    when the number of inputs is very large.
    3) k-NN makes no assumptions about the functional form of the problem solved.

- [ ] Only 1
- [ ] 1 and 3
- [ ] 1 and 2
- [x] All of the above

## Question 2

    Which of the following distance measure do we use in case of categorical
    variables in k-NN?

    1)Hamming Distance
    2)Euclidean Distance
    3)Manhattan Distance

- [ ] 1, 2 and 3
- [x] 1
- [ ] 1 and 2
- [ ] 3
- [ ] 2
- [ ] 2 and 3

## Question 3: Logistic regression assumes a

- [ ] Linear relationship between observations.
- [ ] Linear relationship between continuous predictor variables.
- [x] Linear relationship between continuous predictor variables and the logit of the outcome variable.
- [ ] Linear relationship between continuous predictor variables and the outcome variable.

## Question 4: Regarding bias and variance, which of the following statements are true?

- [ ] Models which overfit have a high bias and underfit have a high variance
- [ ] Models which overfit have a low bias and underfit have a high variance
- [ ] Models which overfit have a high bias and underfit have a low variance
- [x] Models which overfit have a low bias and underfit have a low variance

## Question 5: Adding more basis functions in a linear model

- [ ] Decreases variance
- [ ] Decreases estimation bias
- [ ] Doesn’t affect bias and variance
- [x] Decreases model bias

## Question 6: Choose which data mining task is the most suitable for the following scenario: diagnosing the level of flood severity

- [ ] Prediction
- [ ] Classification
- [ ] Anomaly detection
- [x] Association rules

## Question 7

    For the question given below consider the data Transactions :

    I1, I2, I3, I4, I5, I6
    I7, I2, I3, I4, I5, I6
    I1, I8, I4, I5
    I1, I9, I10, I4, I6
    I10, I2, I4, I11, I5

    With support as 0.6 find all frequent itemsets?

- [x] `<I1>, <I2>, <I4>, <I5>, <I6>, <I1, I4>, <I2, I4>, <I2, I5>, <I4, I5>, <I4, I6>, <I2, I4, I5>`
- [ ] `<I1>, <I4>, <I5>, <I6>`
- [ ] `<I11>, <I4>, <I5>, <I6>, <I1, I4>, <I5, I4>, <I11, I5>, <I4, I6>, <I2, I4, I5>`
- [ ] `<I2>, <I4>, <I5>, <I2, I4>, <I2, I5>, <I4, I5>, <I2, I4, I5>`

## Question 8

Describe how you would correct for zero probabilities or solve zero frequency
problems in Naive Bayes? (Explain in detail)

## Question 9: The inference made by an association rule does not necessarily imply causality

- [x] True
- [ ] False

## Question 10

In naive bayesian classification, describe the main difference between how
discrete categorical and continuous numerical outcomes are handled.
Only provide the main differences.
