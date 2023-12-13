# Ensemble Learning in Machine Learning

## Introduction

Ensembling in machine learning involves combining multiple individual models to create a more robust and accurate predictor than any single model. This technique can be implemented in various ways, such as bagging, boosting, or stacking, using diverse or similar algorithms to create an ensemble model.

## Algorithm

Ensemble algorithms work by training multiple models and combining their predictions to produce a final output. Some popular ensemble methods include:
- Bagging (Bootstrap Aggregating)
- Boosting
- Stacking

## Dataset 

The data used for this model is a public data from Kaggle https://www.kaggle.com/farhanmd29/predicting-customer-ad-clicks.

The data contains the following features:

- Daily Time Spent on Site: consumer time on site in minutes
- Age: cutomer age in years
- Area Income: Avg. Income of geographical area of consumer
- Daily Internet Usage: Avg. minutes a day consumer is on the internet
- Ad Topic Line: Headline of the advertisement
- City: City of consumer
- Male: Whether or not consumer was male
- Country: Country of consumer
- Timestamp: Time at which consumer clicked on Ad or closed window
- Clicked on Ad: 0 or 1 indicated clicking on Ad

## Advantages
- Enhanced Predictive Performance
- Robustness
- Versatility

## Disadvantages
- Complexity
- Overfitting
- Increased Computation Time

ML-Ensemble, a library, uses Scikit-learn's high-level API and computational graph frameworks to build ensemble networks efficiently. It enables memory-efficient and parallelized ensembling while offering flexibility in model combination and concurrency methods.

## Data Analysis

### Histograms
Visualize the distributions of features using histograms to understand their spread.

### Pairplot
Create a pairplot to explore relationships between multiple variables, coloring points by 'Clicked on Ad'.

### Heatmap
Create a heatmap to visualize the correlation between different numerical features in the dataset.

### ROC Curve
Generate an ROC curve to evaluate model performance.

## Models

### Multivariable Logistic Regression
- Train and test a Logistic Regression model.
- Evaluate the model using a Confusion Matrix and a Classification Report.
- Visualize the ROC Curve.

### Random Forest Classifier
- Train and test a Random Forest Classifier.
- Evaluate the model using a Confusion Matrix and a Classification Report.

### Decision Tree
- Train and test a Decision Tree Classifier.
- Evaluate the model using a Confusion Matrix and a Classification Report.

### Ensemble
- Create a VotingClassifier ensemble comprising Logistic Regression, Random Forest, and Decision Tree.
- Evaluate the accuracy of each classifier individually and the VotingClassifier.

## Conclusion

The results obtained from applying different algorithms to predict whether an internet user clicked on an advertisement were:

- Logistic Regression achieved an accuracy score of 0.90.
- Random Forest Classifier exhibited the highest accuracy score of 0.96.
- Decision Tree Classifier attained an accuracy score of 0.93.
- Voting Classifier—an ensemble of the three models—yielded an accuracy score of 0.95.

The highest accuracy achieved by Random Forest underscores its suitability for this prediction task. The Voting Classifier showcased a significant improvement over Logistic Regression, demonstrating the effectiveness of combining multiple models to achieve better predictive performance.

