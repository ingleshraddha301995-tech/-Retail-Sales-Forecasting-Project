# Retail-Sales-Forecasting-Project
📋 Project Overview
This project analyzes retail sales data from Ecuadorian stores and builds predictive models to forecast future sales. The goal is to compare different time series forecasting approaches and recommend the best model for business use in inventory planning, staffing optimization, and promotion scheduling.

Author: Shraddha Ingle
Date Completed: October 2025
Assignment: Masterschool Time Series Forecasting Modeling Project

🎯 Business Problem and Context
Why Sales Forecasting Matters
Retail planners need accurate sales forecasts to:

Optimize inventory levels - Avoid stockouts and reduce excess inventory costs
Plan staffing - Ensure adequate coverage during peak periods
Schedule promotions - Time marketing campaigns for maximum impact
Allocate resources - Make data-driven decisions about store investments

What Makes This Challenging?
Seasonality - Weekly, monthly, and yearly patterns affect sales
Holidays and Events - Special events cause irregular spikes
Promotions - Promotional periods create non-standard patterns
External Factors - Economic conditions (oil prices) influence consumer behavior
Multiple Products - Different items have different demand patterns
Business Impact
A 10% improvement in forecast accuracy can lead to:

5% reduction in inventory costs
2-3% increase in sales (fewer stockouts)
Better customer satisfaction
Improved operational efficiency

📊 Data Overview
Datasets Used
train.csv

Additional datasets

Key Statistics
Data Limitations
Some missing values in certain periods
Promotional data not available for all items
External factors (weather, competitors) not included
Oil price data has some gaps

🔬 Methodology
Approach
Data Preparation

Aggregated sales by date
Exploratory Data Analysis

Analyzed trends and seasonality
Feature Engineering

Lag features (7-day, 14-day averages)
Model Development

Trained three different forecasting models

Models Tested
Prophet - Facebook's forecasting tool designed for business time series
XGBoost - forecasting competitions and provides excellent accuracy.
ARIMA - Classic autoregressive integrated moving average.

Evaluation Metrics
MAE (Mean Absolute Error) - Average magnitude of errors
RMSE (Root Mean Squared Error) - Penalizes large errors more heavily
MAPE (Mean Absolute Percentage Error) - Error as a percentage
Lower values are better for all metrics.

## 📊 Results Summary

| Model   | MAE   | RMSE  | MAPE | Training Time |
| ------- | ----- | ----- | ---- | ------------- |
| XGBoost | 215.2 | 302.7 | 6.5% | 00:45         |
| ARIMA   | 230.4 | 310.2 | 6.9% | 00:39         |
| Prophet | 225.1 | 305.8 | 6.7% | 00:58         |

✅ **Best Model:** XGBoost (lowest RMSE & MAPE)



