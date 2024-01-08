Logistic Regression for Diabetes Prediction.
This repository contains a Python script that demonstrates the implementation of logistic regression for predicting diabetes based on certain features. The dataset used for this example is the "diabetes.csv" file.

Getting Started
Prerequisites
Make sure you have the required libraries installed using the following command:
pip install pandas numpy scikit-learn

Overview
1. Dataset
The dataset is loaded from the "diabetes.csv" file, and the first few rows are displayed to give an overview of the data.

2. Data Preparation
The dataset is divided into features (X) and the target variable (y), and then split into training and testing sets.

3. Model Training
A logistic regression model is created and trained using the training data.

4. Model Evaluation
The model is evaluated using the testing set, and accuracy along with the confusion matrix is displayed.

5. Prediction for a New Patient
A new patient entry is created, and the trained model predicts whether the patient has diabetes or not.

Results
The accuracy of the model on the test set is approximately 81.17%, and the confusion matrix provides additional insights into the model's performance.
