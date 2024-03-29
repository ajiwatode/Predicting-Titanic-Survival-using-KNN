# Predicting-Titanic-Survival-using-KNN
RMS Titanic, during her maiden voyage on April 15, 1912, sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. The tragedy is considered one of the most infamous shipwrecks in history and led to better safety guidelines for ships.


Overview:-

The data has been split into two groups:

training set (train.csv)

test set (test.csv)

The training set should be used to build your machine learning models. For the training set, we provide the outcome (also known as the “ground truth”) for each passenger. Your model will be based on “features” like passengers’ gender and class. You can also use feature engineering to create new features.

The test set should be used to see how well your model performs on unseen data. For the test set, we do not provide the ground truth for each passenger. It is your job to predict these outcomes. For each passenger in the test set, use the model you trained to predict whether or not they survived the sinking of the Titanic.


The following process of above project:-

1.Understand different features in the training dataset

2.Clean the features

3.Remove outliers

4.Find relation between different features and survival

5.Find the best features using SelectKBest (to get an optimal fit between bias and variance)

6.Train and fit the model

7.Predict the scores using KNearestNeighbors

8.Check Accuracy

9.Predict Survival values for test.csv

10.Create final file for submission
