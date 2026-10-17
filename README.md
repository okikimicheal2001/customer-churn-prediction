# Customer Churn Prediction

## Project Overview
This project uses machine learning to predict whether a telecommunications customer is likely to leave a company.

The goal is to identify customers who may be at risk of leaving so that businesses can investigate and improve customer retention.

## Objectives
- Explore customer churn data.
- Preprocess numerical and categorical features.
- Train and evaluate machine learning models.
- Tune model hyperparameters using GridSearchCV.
- Estimate churn probabilities for hypothetical customers.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Google Colab

## Features Used
- Customer tenure
- Paperless billing
- Device protection
- Contract type
- Monthly charges

## Machine Learning
Several models were compared during development, including:
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

The final Logistic Regression model was tuned using GridSearchCV.

## Model Evaluation
The tuned Logistic Regression model achieved an F1 score of approximately 0.61 for the churn class during cross-validation.

On the held-out test set, the model achieved approximately 73% accuracy.

## Example Predictions
The model was tested using hypothetical customer profiles to estimate their churn probabilities.

These predictions demonstrate how the model can support customer-retention analysis. They are estimates, not guarantees of future customer behavior.

## Limitations
The model uses a limited set of customer features. Its predictions may not generalize to every business or customer population.

## Future Improvements
- Develop an interactive web application.
- Explore additional customer features.
- Improve probability calibration.
- Monitor performance on new customer data.