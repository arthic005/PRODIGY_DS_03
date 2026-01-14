Task-03: Decision Tree Classifier — Bank Marketing Dataset
Overview

This project implements a Decision Tree Classifier to predict whether a customer will subscribe to a bank product or service based on their demographic and behavioral data. The dataset is from the Bank Marketing dataset (UCI Machine Learning Repository).

Objective

Build a Decision Tree classifier.

Predict the target variable (y) — whether the customer will subscribe (yes/no).

Evaluate the model’s performance using accuracy.

Dataset

Source: UCI Machine Learning Repository - Bank Marketing Dataset

Number of features: 16 (including categorical & numerical)

Target column: y

Features include:
age, job, marital, education, default, balance, housing, loan, contact, day, month, duration, campaign, pdays, previous, poutcome

Target:

y: 1 if the customer subscribed, 0 if not

Steps Performed

Load Dataset: Fixed CSV separator issue using sep=";".

Preprocessing: Encoded all categorical columns using LabelEncoder.

Split Data: 80% training and 20% testing using train_test_split.

Model Training: Trained a DecisionTreeClassifier on the training set.

Prediction: Predicted subscription on test data.

Evaluation: Calculated accuracy to evaluate the model.

Results

Model Accuracy: 0.8663 (≈ 86.6%)

This means the model predicts correctly about 87 times out of 100.

Conclusion
The Decision Tree model was able to learn patterns from customer data and make accurate predictions about their subscription behavior.
This demonstrates the effectiveness of decision trees in classification problems with categorical and numerical data.

The Decision Tree model was able to learn patterns from customer data and make accurate predictions about their subscription behavior.
This demonstrates the effectiveness of decision trees in classification problems with categorical and numerical data.
