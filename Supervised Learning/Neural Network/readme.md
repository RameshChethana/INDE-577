# Multilayer Neural Network

## Overview

The "Neural Network.ipynb" notebook explores the implementation and application of Multilayer Neural Networks, specifically Multi-Layer Perceptrons (MLPs), in solving complex nonlinear relationships within data. The notebook details the algorithm's core components, advantages, and disadvantages, demonstrating its practical usage through the analysis of the Fashion MNIST dataset from Keras.

## Introduction

Multilayer Neural Networks, such as Multi-Layer Perceptrons (MLPs), consist of interconnected layers of neurons, including input, hidden, and output layers. These networks are adept at processing intricate information and handling nonlinear relationships within data.

## Algorithm

The notebook outlines the forward and backward propagation phases of MLPs:

- Forward Propagation: Sequential passage of input data through the network's layers, calculating weighted sums and applying activation functions to generate outputs.
- Backward Propagation (Training): Error computation between predicted and actual outputs, backward propagation of errors through the network, and weight adjustment using optimization techniques like gradient descent to minimize errors.

## Advantages

- Nonlinearity: Capability to model complex nonlinear relationships within data.
- Adaptability: Applicability across a diverse range of problems encompassing regression, classification, and pattern recognition.
- Feature Learning: Automatic feature extraction and learning from raw data.
- Generalization: Ability to generalize well to new, unseen data when properly trained.

## Disadvantages

- Complexity: Computational demands during training and tuning, particularly for large datasets and deep architectures.
- Overfitting: Vulnerability to overfitting with insufficient data or overly complex models.
- Hyperparameter Sensitivity: Sensitivity of model performance to chosen hyperparameters.
- Interpretability: Challenges in interpreting learned features and the decision-making process, especially in deep architectures.

## Model Implementation

The notebook features a custom implementation of Multilayer Perceptron (MLP) encompassing methods for forward propagation, error calculation, activation functions, gradient descent, and training using mini-batch gradient descent.

## Applications on Datasets

Utilizing the Fashion MNIST dataset from Keras, the notebook preprocesses the data, normalizes pixel values, and shapes the data for MLP training and testing.

## Model Evaluation

It compares the performances of MLPs using different activation functions (tanh, relu, sigmoid) through mini-batch gradient descent, highlighting the impact of activation functions on model performance.
