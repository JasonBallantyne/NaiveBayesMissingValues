# Naive Bayes Missing Values

## Part 1
Implementing a Gaussian Naive Bayes function that handles missing values.Gaussian Naive Bayes can handle missing values in training by calculating conditional probabilities on the values that are present. We explore two strategies:
1. Consider missing values explicitly in the classification algorithm.
2. Using imputation methods to guess missing values.

## Part 2
Testing the performance of my implementation against the scikit-learn GaussianNB using missing value imputation. For this we use two datasets:
1. PenguinsMV0.2.csv (20% missing values)
2. PenguinsMV0.4.csv (40% missing values)
