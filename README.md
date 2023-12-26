# Spam_Email_Detection


# Overview

This project aims to classify emails as spam or ham (non-spam) using machine learning. We employ a Logistic Regression model and process email texts through TF-IDF vectorization to predict their categories.

# Dataset

The dataset, mail_data.csv, contains email messages and their respective categories (spam or ham). It's preprocessed to replace missing values and to convert the target variable into a binary format.

# Features

Data Preprocessing: Handling missing values, encoding text data using TF-IDF vectorization.
Exploratory Data Analysis: Initial analysis to understand the dataset's structure.
Model Training: Logistic Regression model to classify emails.
Model Evaluation: Using accuracy, precision, recall, and F1-score for both training and test data. Cross-validation is used to validate the model's effectiveness.
Prediction: Classifying new email messages as spam or ham.
Requirements

This project requires Python 3 and the following libraries:

Pandas
NumPy
Scikit-learn
Matplotlib (optional for further data exploration)
