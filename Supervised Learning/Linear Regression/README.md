# Linear Regression Implementation

## Introduction

The "Linear Regression.ipynb" notebook showcases the implementation of Linear Regression, a fundamental machine learning algorithm, using Python and various libraries like NumPy, Pandas, Matplotlib, and Scikit-learn. This notebook details the process of examining a real estate dataset from New Taipei City, Taiwan, focusing on data inspection, visualization, data regularization, model implementation, training, evaluation, and error analysis.

## Dataset Overview

The dataset contains real estate valuations from New Taipei City. The exploration begins by loading the dataset into a Pandas DataFrame to understand its structure, attributes, and contents, facilitating further analysis and planning for model building.

## Notebook Structure

1. **Importing Libraries and Data**: The notebook starts by importing essential libraries for data manipulation, visualization, and machine learning. The dataset, "Real estate.csv," is loaded into a Pandas DataFrame.

2. **Data Regularization**: Ensuring feature scaling consistency for model stability and effectiveness through z-score normalization, preventing bias due to varying feature magnitudes.

3. **Data Splitting**: Division of the dataset into training and test sets, allocating 2/3 for training and 1/3 for testing purposes.

4. **Model Training and Evaluation**: The model is trained using gradient descent and the normal equation, minimizing mean squared error. The notebook visualizes the training process, evaluates the model on test data, and compares both methods' performance.

5. **Results Visualization**: Visualizations depicting feature versus price/sqft comparisons, aiding in understanding feature relationships and predicted versus actual values.

6. **Error Analysis**: Evaluating model efficacy through error metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and $R^2$ Error on the test data.

## Conclusion

The Linear Regression implementation within this notebook demonstrates foundational regression concepts, including data regularization, model training, evaluation, and error analysis. It emphasizes the significance of data preprocessing, training techniques, and error evaluation in understanding and assessing regression models' predictive capabilities.
