# synent-task8-MachineLearningModel-Mahek

# Task 8: Machine Learning Model — Loan Prediction

## Problem Statement
Predict whether a loan application will be approved or rejected based on applicant details.

## Dataset
- Source: [Kaggle - Loan Prediction Dataset](https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset)
- Rows: 614 | Columns: 13

## Approach
1. Loaded and cleaned the dataset
2. Handled missing values using median and mode
3. Performed EDA to find key patterns
4. Encoded categorical columns using Label Encoding
5. Split data into 80% train and 20% test
6. Trained Logistic Regression, Decision Tree, and Random Forest
7. Compared model accuracies and evaluated best model

## Results
- Random Forest gave the best accuracy (~82%)
- Credit History is the strongest predictor of loan approval

## Models Used
- Logistic Regression
- Decision Tree
- Random Forest
