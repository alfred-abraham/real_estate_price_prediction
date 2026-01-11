# Real Estate Price Prediction

## Overview
This project applies supervised machine learning to predict residential property prices using structural and location-based features. The goal is to evaluate model performance and interpretability on a small, real-world housing dataset.

## Problem
The task is to predict house price per unit area based on property characteristics such as age, proximity to transit, and geographic location. This is a supervised regression problem evaluated using error-based metrics.

## Data
The dataset comes from the UCI Machine Learning Repository and contains historical real estate transaction data from New Taipei City, Taiwan. All variables are numeric and include structural and geographic features.

## Models
- Linear Regression  
- Decision Tree Regressor  

These models were chosen to contrast interpretability and flexibility on a small dataset.

## Evaluation
Model performance is evaluated using:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Cross-validation error

Results show that the Decision Tree significantly overfits the training data, while Linear Regression generalizes more consistently.


## Limitations
This analysis does not incorporate macroeconomic variables such as interest rates or broader market conditions. Results should be interpreted as estimates rather than exact valuations.

