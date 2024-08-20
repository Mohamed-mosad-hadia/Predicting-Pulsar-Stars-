# Predicting Pulsar Stars using Support Vector Machine (SVM)

This project focuses on predicting whether a star is a pulsar using machine learning techniques, particularly Support Vector Machine (SVM). The dataset includes various features extracted from the integrated pulse profiles, and the goal is to classify stars into pulsar or non-pulsar categories.


# Overview
This notebook guides you through the following steps:

Data Import: Load and combine the training and test datasets.

Exploratory Data Analysis (EDA):

 -Examine dataset dimensions and summary statistics.
 -Analyze the distribution of the target class and identify potential issues, such as missing data and class imbalance.
Data Preprocessing:

-Handle missing values by imputing with median values, which is more appropriate due to the skewness of the data.
-Visualize and handle outliers using SVM.

Feature Engineering:
Feature scaling is performed using StandardScaler to standardize the features for the SVM model.
Model Training:
Split the dataset into training and test sets.
Train the SVM model on the training data.
Model Evaluation:
Visualize the performance of the SVM model.
Evaluate using confusion matrix and classification metrics, including precision, recall, and F1-score.
