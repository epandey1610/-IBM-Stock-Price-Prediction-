# -IBM-Stock-Price-Prediction-
This project predicts the future stock prices of IBM using **LightGBM**, a fast and efficient gradient boosting framework. The model leverages historical stock data and advanced feature engineering to forecast stock prices for the next month.

## Key Features

- **Data Source**: Historical stock data fetched using the `yfinance` API.
- **Feature Engineering**: Includes moving averages, momentum indicators (e.g., ROC), volatility measures (e.g., Bollinger Bands), and lagged features.
- **Model**: LightGBM is used for its speed, efficiency, and ability to handle large datasets.
- **Evaluation**: Model performance is evaluated using **RMSE** (Root Mean Squared Error) and **R-squared** metrics.
- **Visualization**: Includes plots of actual vs predicted stock prices and feature importance.



## Requirements

- Python 3.x
- Libraries: `lightgbm`, `pandas`, `numpy`, `yfinance`, `scikit-learn`, `matplotlib`
