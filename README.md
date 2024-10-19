# Datascience-project

Summary: Linear Regression for Predicting House Prices
This project uses Linear Regression to predict house prices from the Ames Housing dataset. The dataset contains multiple features describing residential homes, and for simplicity, this project focuses on predicting house prices based on the feature 'Gr Liv Area' (Above Ground Living Area).

Key Steps:
Data Loading and Exploration:

The Ames Housing dataset was loaded using Pandas, and an initial exploration of the data was conducted. The dataset contains 82 columns, but we focused on Gr Liv Area (ground living area) and SalePrice (target variable).
Feature Selection:

For simplicity, the project predicts house prices using only the 'Gr Liv Area' as the independent variable (x) and 'SalePrice' as the dependent variable (y).
Linear Regression Calculation:

The mean of Gr Liv Area and SalePrice was calculated.
The coefficients of the linear regression equation (b0 for the intercept and b1 for the slope) were computed using the ordinary least squares (OLS) method.
The linear equation was formed:


y=b0+b1×x
where b0 = 13289.64 and b1 = 111.69.
Model Prediction:

The model predicted house prices based on the linear relationship between Gr Liv Area and SalePrice.
Predictions were made and stored in y_pred.
Model Evaluation:

The model was evaluated using the Mean Squared Error (MSE) and R-squared (R²) score:
MSE: 358,739,895.17 (indicating the average squared difference between predicted and actual house prices).
R² Score: 0.4995 (indicating that the model explains about 50% of the variance in house prices).
Visualization:

A scatter plot was generated showing the actual data points (green dots) and the regression line (red line). The graph indicates a positive linear relationship between the ground living area and house prices.
