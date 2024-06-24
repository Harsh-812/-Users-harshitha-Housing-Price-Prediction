# Housing Price Prediction Analysis

## Project Overview

This project aims to predict housing prices using various machine learning algorithms. The dataset used is the Boston Housing Dataset, which contains information about houses in Boston, including features such as crime rate, number of rooms, age of the house, and more. The goal is to compare the performance of different regression models and determine the best model for predicting house prices.

## Features

- **Data Preprocessing**: Data cleaning, feature scaling, and splitting the data into training and testing sets.
- **Model Training and Evaluation**:
  - Linear Regression
  - Decision Tree
  - Random Forest
  - XGBoost
  - Extra Trees
- **Performance Metrics**: 
  - Cross-Validation Score (CV Score)
  - Mean Squared Error (MSE)
  - R-squared (R²)
  - Accuracy (in percentage)
- **Feature Importance**: Visualization of feature importance for tree-based models and coefficients for Linear Regression.

## Results

### Model Performance

| Model              | CV Score | MSE   | R²   | Accuracy (%) |
|--------------------|----------|-------|------|--------------|
| Linear Regression  | 24.33    | 26.47 | 0.64 | 63.90        |
| Decision Tree      | 32.00    | 10.67 | 0.85 | 85.46        |
| Random Forest      | 14.94    | 7.69  | 0.90 | 89.51        |
| XGBoost            | 13.98    | 7.15  | 0.90 | 90.25        |
| Extra Trees        | 11.95    | 9.86  | 0.87 | 86.56        |

### Best Model
Based on the evaluation metrics, **XGBoost** is the best model for predicting house prices, with the lowest Mean Squared Error (7.15), the highest R-squared (0.90), and the highest accuracy (90.25%).
