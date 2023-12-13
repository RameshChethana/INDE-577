K Nearest Neighbors (KNN)
Overview

The "K Nearest Neighbors (KNN)" notebook explores the K Nearest Neighbors algorithm, a straightforward yet effective supervised learning technique used for classification and regression tasks. It delves into the principles, advantages, and limitations of KNN, emphasizing its non-parametric, instance-based nature.

Algorithm Description

KNN operates by identifying data points in close proximity to a new instance in the feature space. For classification, it assigns a class label based on the majority class among its K nearest neighbors; for regression, it predicts a value based on the mean of its K nearest neighbors' values.

Dataset
https://www.kaggle.com/datasets/rohitsahoo/employee
Watson Analytics Sample Data
Uncover the factors that lead to employee attrition and explore important questions such as ‘show me a breakdown of distance from home by job role and attrition’ or ‘compare average monthly income by education and attrition’. This is a fictional data set created by IBM data scientists

Content
This the data about the employee on various factor influencing the attrition from the company.
Predict the Attrition of an employee based on the various factor given

Pros and Cons

Pros include simplicity, versatility in handling both classification and regression tasks, and robustness to noisy data. However, it has cons such as computational intensity during prediction and sensitivity to irrelevant features.

Contents

The notebook covers essential libraries for data operations, data visualization, data preprocessing using Sklearn, and key steps in implementing KNN for classification and regression:

Data Preprocessing
Handling missing values, scaling features, and encoding categorical variables
Removing columns with zero variance
Splitting Data
Division into training and test sets for model evaluation
Classification with KNN
Determining optimal 'K' value using accuracy scores
Training and evaluating KNN classifier
Analyzing performance metrics like accuracy, confusion matrix, and ROC curve
Principal Component Analysis (PCA)
Dimensionality reduction technique to enhance model performance
KNN Classification with PCA
Applying KNN with PCA and assessing its performance
Regression with KNN
Utilizing KNN for regression tasks and evaluating performance using Root Mean Squared Error (RMSE)