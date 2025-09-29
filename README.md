# Car-Price-Prediction
This is my first ML project

This project focuses on predicting car prices using Linear Regression, Lasso Regression, and Ridge Regression. The aim is to compare the performance of different regression techniques while handling multicollinearity and overfitting.

## Project Overview
Performed data cleaning (handling missing values, outliers, duplicates).
Applied encoding for categorical features (e.g., brand, fuel type, transmission).
Implemented Linear Regression, Lasso, and Ridge models.
Compared model performance using metrics such as R², RMSE, and MAE.

## Models Implemented
Linear Regression (baseline model)
Ridge Regression (L2 regularization)
Lasso Regression (L1 regularization for feature selection)

## Results
Linear Regression worked as a baseline but struggled with multicollinearity.
Ridge Regression improved generalization and reduced overfitting.
Lasso Regression performed feature selection by shrinking irrelevant predictors.

## Future Work
Add hyperparameter tuning with GridSearchCV.
Compare with tree-based models (Random Forest, XGBoost).
Deploy as a simple web app for price prediction.
