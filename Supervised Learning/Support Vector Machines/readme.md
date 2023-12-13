Support Vector Machine (SVM) Implementation
Overview
The "SVM.ipynb" notebook focuses on implementing the Support Vector Machine (SVM) algorithm using the sci-kit learn library. SVM is a potent supervised machine learning model used extensively for classification and regression tasks. The notebook follows a structured approach, detailing phases commonly observed in machine learning projects.

Phase 1: Data Cleaning/Analysis
The initial phase involves data preprocessing, exploratory data analysis (EDA), and understanding the dataset. The notebook cleans and preprocesses the dataset, encodes categorical features, standardizes 'age' attribute, and prepares it for model training.

Phase 2 & 3: Train and Test the Model
The notebook splits the dataset into training and testing sets, trains SVM models with different kernel types ('linear', 'poly', 'rbf', 'sigmoid'), evaluates accuracy scores, and chooses the most suitable kernel ('rbf' kernel in this case) based on performance.

Phase 4: Model Evaluation and Comparison
The SVM model is trained and tested, yielding an F1 score of 0.93. This score is compared with other models, highlighting the MLP's superior performance with a flawless F1 score of 1, emphasizing the trade-off between interpretability and accuracy in model selection.

Dataset
https://www.kaggle.com/datasets/mathchi/diabetes-data-set
his dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective is to predict based on diagnostic measurements whether a patient has diabetes.

Content
Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.

Pregnancies: Number of times pregnant
Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
BloodPressure: Diastolic blood pressure (mm Hg)
SkinThickness: Triceps skin fold thickness (mm)
Insulin: 2-Hour serum insulin (mu U/ml)
BMI: Body mass index (weight in kg/(height in m)^2)
DiabetesPedigreeFunction: Diabetes pedigree function
Age: Age (years)
Outcome: Class variable (0 or 1)