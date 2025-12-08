OVERVIEW
This repository contains all code/notebooks for my machine learning capstone project.
The project is based on predicting housing prices using the Ames Housing dataset from Kaggle.
The project includes classical machine learning algorithms (Linear, Logistic, Polynomial Ridge) and research-based (Gradient Boost, Lasso) regression methods.
Performance is evaluated using RMSE and R².

DATA FILES
train.csv
Primary training dataset from Kaggle. Contains housing features and the SalePrice target variable.

test.csv
Test dataset from Kaggle.

NOTEBOOK FILES
LinearRegression.ipynb
Implements baseline Linear Regression with full preprocessing, encoding, scaling, training, and evaluation.

LogisticRegression.ipynb
Implements Logistic Regression as a classification model.

PolynomialRidgeRegression.ipynb
Implements Polynomial Ridge Regression with hyperparameter tuning using grid search.

LassoRegression.ipynb
Implements Lasso Regression with L1 regularization and automatic feature selection.

GradientBoostRegression.ipynb
Implements Gradient Boosting Regressor as a research-based model with hyperparameter tuning.

