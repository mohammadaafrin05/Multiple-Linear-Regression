# Multiple-Linear-Regression
Description:
This repository contains predictive models based on single and multiple linear regression for the following tasks:
50-startup dataset: Predict the profit for a startup using single and multiple regression based on features such as 'R&D Spend', 'Administration', 'Marketing Spend', and 'State'.
Toyota Corolla dataset: Predict the price of a Toyota Corolla car using various features like 'Age', 'KM', 'HP', 'cc', and more.
The performance is evaluated using metrics like accuracy and R² value.
Datasets:
50-startup Dataset: https://www.kaggle.com/code/cundratjuninhokuth/multiple-linear-regression-predict-profit
Toyota Corolla Dataset:https://www.kaggle.com/datasets/klkwak/toyotacorollacsv?select=ToyotaCorolla.csv

File Explanations:
50_startup_profit_prediction.py:
This script loads the 50-startup dataset and applies both single and multiple linear regression models to predict the profit based on features like 'R&D Spend', 'Administration', 'Marketing Spend', and 'State'.
Outputs include accuracy and R² values for the models.

toyota_corolla_price_prediction.py:
This script uses the Toyota Corolla dataset to predict the price of a car based on features like 'Age', 'KM', 'HP', 'cc', 'Doors', 'Gears', 'Quarterly_Tax', and 'Weight'.
It applies both single and multiple regression models and computes the accuracy and R² values.

Performance Metrics:
Accuracy: Measured by evaluating the difference between the predicted and actual values.
R² Value (Coefficient of Determination): Measures the goodness of fit for the regression model. A value of 1 indicates a perfect fit.
