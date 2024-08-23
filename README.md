Titanic Survival Prediction
This repository contains a Python implementation for predicting the survival of passengers on the Titanic using machine learning. The project leverages the Titanic dataset and applies a Random Forest classifier to predict whether a passenger would have survived or not based on various features such as age, gender, class, fare, and more.

Key Features:
Data Preprocessing: Handles missing data, encodes categorical variables, and prepares the dataset for training.
Random Forest Classifier: A robust ensemble learning method that is trained to classify passengers based on survival.
Performance Evaluation: Includes accuracy score, classification report, and confusion matrix to evaluate the model's performance.
Visualization: Plots a confusion matrix to visualize the model’s performance and feature importance to understand the influence of different features on predictions.
Steps:
Load and Preprocess Data:

Load the Titanic dataset from a CSV file.
Drop irrelevant columns (PassengerId, Name, Ticket, Cabin).
Handle missing values for Age and Embarked using the most frequent value.
Encode categorical variables (Sex, Embarked) into numerical format.
Model Training:

The data is split into training and testing sets.
A Random Forest classifier is trained on the training data.
Model Evaluation:

Predictions are made on the test data.
The model's accuracy is computed, along with a confusion matrix and classification report.
Visualization:

The confusion matrix is plotted to show the model's performance visually.
Feature importance is plotted to highlight which features are most influential in predicting survival.
Requirements:
Python 3.x
pandas
seaborn
matplotlib
scikit-learn

Results:
The model provides an accuracy of approximately 81.6% on the test data. Visualizations of the confusion matrix and feature importance help in understanding the model’s decisions and performance.
