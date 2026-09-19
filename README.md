# Credit Card Fraud Detection

## Project Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning. A Logistic Regression model is trained to classify transactions as fraudulent or non-fraudulent.

The project includes data exploration, preprocessing, feature scaling, model training, prediction, and performance evaluation.

## Objectives

- Analyze the credit card transaction dataset.
- Identify fraudulent and non-fraudulent transactions.
- Handle class imbalance using balanced class weights.
- Train a Logistic Regression classification model.
- Evaluate the model using multiple performance metrics.
- Visualize the model performance using a Confusion Matrix and ROC Curve.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- GitHub

## Project Workflow

1. Load the dataset.
2. Explore the dataset and transaction classes.
3. Separate features and target variable.
4. Split the data into training and testing sets.
5. Standardize the features using `StandardScaler`.
6. Train a Logistic Regression model.
7. Use balanced class weights to handle class imbalance.
8. Predict fraud and non-fraud transactions.
9. Evaluate the model using:
   - Accuracy
   - Precision
   - Recall
   - F1 Score
   - Confusion Matrix
   - ROC-AUC
10. Visualize the results.

## Machine Learning Model

### Logistic Regression

Logistic Regression is used as the classification algorithm for predicting whether a transaction is fraudulent or non-fraudulent.

The model uses:

```python
LogisticRegression(
    class_weight='balanced',
    max_iter=1000,
    random_state=42
)
