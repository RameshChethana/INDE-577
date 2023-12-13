# Support Vector Machine (SVM) Implementation

## Overview

The "SVM.ipynb" notebook focuses on implementing the Support Vector Machine (SVM) algorithm using the sci-kit learn library. SVM is a potent supervised machine learning model used extensively for classification and regression tasks. The notebook follows a structured approach, detailing phases commonly observed in machine learning projects.

## Phase 1: Data Cleaning/Analysis

The initial phase involves data preprocessing, exploratory data analysis (EDA), and understanding the dataset. The notebook cleans and preprocesses the dataset, encodes categorical features, standardizes 'age' attribute, and prepares it for model training.

## Phases 2 & 3: Train and Test the Model

The notebook splits the dataset into training and testing sets, trains SVM models with different kernel types ('linear', 'poly', 'rbf', 'sigmoid'), evaluates accuracy scores, and chooses the most suitable kernel ('rbf' kernel in this case) based on performance.

## Phase 4: Model Evaluation and Comparison

The SVM model is trained and tested, yielding an F1 score of 0.93. This score is compared with other models, highlighting the MLP's superior performance with a flawless F1 score of 1, emphasizing the trade-off between interpretability and accuracy in model selection.
