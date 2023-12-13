# Perceptron

## Overview

The "Perceptron.ipynb" notebook explores the implementation and functionality of a perceptron, a fundamental single-layer neural network used for binary classification tasks. It demonstrates building a perceptron model from scratch and its application using the IBM Employee Attrition dataset.

## Introduction

A perceptron is a basic neural network comprising input nodes, weights, a summation function, and an activation function. This notebook introduces the perceptron model, detailing its architecture and learning process. It explains how the perceptron learns and makes predictions based on input features by adjusting weights during training.

## Model Implementation

The notebook begins with essential imports and visualization libraries necessary for data processing, visualization, and evaluation. It then loads and preprocesses the IBM Employee Attrition dataset, preparing it for perceptron model training.

### Building the Perceptron

It defines a Perceptron class for binary classification, outlining the functions for activation, loss calculation, gradient approximation, weight updates, and model fitting. The notebook showcases the training process and tracks the loss history during training.

### Preprocessing

The notebook covers dataset preprocessing steps, including dropping variables with zero variance, encoding categorical columns, feature selection, and standardizing features using z-score normalization for efficient perceptron training.

## Performance Analysis

It evaluates the trained perceptron model's performance by examining metrics such as accuracy scores, confusion matrices, and visualizing decision boundaries. It provides insights into the model's accuracy on training and test sets and analyzes classification reports.

## Conclusion

The "Perceptron.ipynb" notebook serves as an educational resource demonstrating the implementation and utilization of a perceptron model from scratch. It highlights the model's strengths, limitations, and its applicability in binary classification tasks using real-world data.
