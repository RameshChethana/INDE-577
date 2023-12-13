# Logistic Regression

## Overview

The "Logistic Regression.ipynb" notebook explores the implementation and application of Logistic Regression, a classification algorithm utilized for binary classification tasks. This notebook showcases the theoretical foundations, advantages, and limitations of logistic regression while demonstrating its practical application using the Wine dataset from sklearn.datasets.

## Introduction

Logistic Regression, despite its name, is a classification algorithm used to predict the probability of a sample belonging to a specific class. The algorithm employs the sigmoid function to map predicted values to probabilities, modeling the relationship between dependent and independent variables by estimating probabilities based on input features.

## Algorithm

The logistic regression algorithm utilizes the sigmoid function to transform linear combinations of input features into probabilities. It estimates the likelihood of a sample belonging to a class and predicts the class label based on these probabilities.

## Advantages

- Simple and Efficient: Easy to implement and interpret, making it suitable for various classification problems.
- Provides Probabilities: Offers probabilities for outcomes, enabling threshold tuning for precision-recall trade-offs.
- Less Prone to Overfitting: Tends to be less prone to overfitting, particularly with smaller datasets.

## Disadvantages

- Linear Decision Boundary: Assumes a linear relationship between features and the log-odds of the response.
- Limited for Complex Relationships: Might not perform well with highly nonlinear feature-target relationships.
- Assumes Independence of Observations: Assumes observations are independent, which might not hold in certain real-world scenarios.

## Model Implementation

The notebook includes a custom implementation of Gradient Descent Logistic Regression. It defines the methods for cross-entropy loss, sigmoid function, gradient calculation, model fitting, and prediction.

## Applications on Datasets

It demonstrates logistic regression's application on the Wine dataset from sklearn.datasets. The notebook preprocesses the data, standardizes features, splits the dataset, and fits the logistic regression model using Gradient Descent.

## Model Evaluation

The notebook evaluates the model by predicting test data, calculating accuracy, and visualizing the confusion matrix to understand model performance on the test set.
