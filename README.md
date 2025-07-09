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
| Model                      | Train Score | Test Score |
|---------------------------|-------------|------------|
| Linear Regression          | 0.656       | 0.513      |
| HistGradientBoostingReg.   | 0.854       | 0.676      |

## How to run
Use `hotel_price_model.ipynb` in Google Colab or Jupyter Notebook.
