🏡 King County House Price Prediction — Machine Learning Regression Models

This project builds a full end-to-end machine learning pipeline to predict house prices in King County, Washington using multiple regression and ensemble learning techniques. The dataset includes property features such as square footage, number of bedrooms/bathrooms, lot size, renovation year, location, and more.

The goal is to compare different regression models, evaluate their performance, and identify which model provides the most accurate price predictions.

🔧 Models Implemented

The notebook includes training, tuning, and comparing the following algorithms:

Ridge Regression (L2)
Adds L2 regularization to reduce overfitting and stabilize coefficient values.

Lasso Regression (L1)
Performs feature selection by shrinking some coefficients to zero.

Elastic Net Regression
Hybrid of L1 and L2 regularization for balanced shrinkage + sparsity.

Random Forest Regressor
Ensemble of decision trees using bagging to reduce variance and boost predictive power.

Gradient Boosting Regressor
Sequential boosting model that reduces errors from previous weak learners.

XGBoost Regressor / LGBM Regressor (optional — used only if installed)
Modern gradient boosting frameworks optimized for speed and performance.

k-Nearest Neighbors (kNN) Regressor
Instance-based learning method that predicts prices based on nearest neighbors.

Support Vector Regressor (SVR)
Uses kernel tricks to capture non-linear relationships in house prices.

📊 Key Features of the Project

Exploratory Data Analysis (EDA)

Data cleaning and preprocessing

Train/test split and cross-validation

Hyperparameter tuning with GridSearchCV

Performance comparison using MSE, RMSE, MAE, and R²

Visualization of model results and feature importance

🎯 Outcome

By evaluating multiple models, the project identifies the best-performing regression technique for predicting King County housing prices, offering insights into model behavior and the impact of regularization and ensemble methods.
