# Hotel Price Prediction 🏨📈

This project uses data from hotel bookings to predict the daily average rate (ADR) using:
- Linear Regression
- HistGradientBoostingRegressor

## Dataset
Data source: `hotel_bookings.csv`  
Target: `adr` (renamed to `price`)

## Features & Techniques
- Label Encoding and One-Hot Encoding
- Mean imputation for missing values
- Train/Test split
- Model performance evaluated using R²

## Results
## 🔍 Model Performance Summary

| Model                  | Train R² | Test R² | MAE   | RMSE  |
|------------------------|----------|---------|-------|--------|
| Linear Regression       | 0.657    | 0.514   | 20.95 | 37.68  |
| HistGradientBoosting    | 0.856    | 0.677   | 12.80 | 30.71  |

Gradient boosting clearly outperforms linear regression, indicating the presence of nonlinear relationships and interactions between features that a simple linear model can't capture.

## How to run
Use `hotel_price_model.ipynb` in Google Colab.
