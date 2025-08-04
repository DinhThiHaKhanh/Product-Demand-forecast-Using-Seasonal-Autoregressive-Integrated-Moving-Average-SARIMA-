# Product Demand Forecast Using Seasonal Autoregressive Integrated Moving Average (SARIMA)
## Overview
This project aim to forecast historical product demand using time series analysis. The goal is to apply SARIMA model to predict future monthly orders for various products, a crucial task for optimizing inventory management and improving supply chain efficiency.
## Key Features
Data Cleaning: Robust preprocessing to handle inconsistent data types, negative order values, and missing dates.
Product Eligibility Filtering: A systematic process to identify and exclude products that are not suitable for time series forecasting (e.g., those with no recent demand or insufficient history).
Automated Model Selection: Utilizes auto_arima to efficiently find the best SARIMA model parameters for each product.
Time Series Forecasting: Generates monthly demand forecasts for a future period.
Visualization: Creates and saves plots comparing the training data, test data, and model forecasts.
Model Evaluation: Calculates MAE and MAPE to provide a clear understanding of each model's forecast accuracy.
