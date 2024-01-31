# Automatic Credit Card Approval Predictor

## Overview
Banks receive numerous credit card applications, and manual processing is time-consuming. This project presents an automatic credit card approval predictor using machine learning techniques. The goal is to automate the application review process, identifying suitable candidates for credit cards based on various features.

## Dataset
The dataset used in this project is a subset of credit card applications, covering attributes like income, loan balances, and credit history. The data is loaded into a Pandas DataFrame for analysis and model training.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn

## Machine Learning Model
The project utilizes a Logistic Regression model for credit card approval prediction. The model is trained on a subset of the dataset, and its performance is evaluated using a confusion matrix and accuracy metrics.

## Data Preprocessing
- Handling missing values: Numeric data is imputed with the mean, while categorical data is filled with the most frequent value.
- One-Hot Encoding: Categorical variables are one-hot encoded for compatibility with machine learning algorithms.
- Feature Scaling: Min-Max scaling is applied to normalize the features.

## Model Tuning
Grid Search is employed to find the best hyperparameters for the Logistic Regression model, optimizing its performance.

## Results
The final model achieves a perfect accuracy score of 1.0 on the test set, showcasing its effectiveness in predicting credit card approvals.

