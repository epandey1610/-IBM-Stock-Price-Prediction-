# -IBM-Stock-Price-Prediction-
This project predicts the future stock prices of IBM using **LightGBM**, a fast and efficient gradient boosting framework. The model leverages historical stock data and advanced feature engineering to forecast stock prices for the next month.

## Key Features

- **Data Source**: Historical stock data fetched using the `yfinance` API.
- **Feature Engineering**: Includes moving averages, momentum indicators (e.g., ROC), volatility measures (e.g., Bollinger Bands), and lagged features.
- **Model**: LightGBM is used for its speed, efficiency, and ability to handle large datasets.
- **Evaluation**: Model performance is evaluated using **RMSE** (Root Mean Squared Error) and **R-squared** metrics.
- **Visualization**: Includes plots of actual vs predicted stock prices and feature importance.




## In this analysis, we explored the stock data of SuperMicrocomputer (SMCI) from January 2010 to December 2024. The goal was to understand the stock's behavior, predict future prices, and analyze the factors contributing to its sudden increase in value. The analysis was conducted using Python, leveraging libraries such as pandas, numpy, matplotlib, and yfinance to fetch and visualize the data.

## Key Learnings

Data Collection and Preprocessing: We used the yfinance library to fetch historical stock data for SMCI, including the closing price and trading volume. the data was cleaned by removing unnecessary columns (High, Low, Open) and simplifying the column names for easier analysis.We created a new column, "Prediction," which represents the next day's closing price, shifted by one day. This will be used as the target variable for our prediction model.

## Data Visualization: 
We plotted the closing price of SMCI over time to observe trends and patterns. The stock showed a gradual increase over the years, with a significant spike towards the end of 2024. The trading volume was also analyzed, showing periods of high activity, particularly during the stock's rapid increase in value.

## Stock Price Surge: 
The most notable observation was the sudden and significant increase in SMCI's stock price towards the end of 2024. This could be attributed to several factors:

## Market Trends: 
The tech sector, particularly companies involved in AI and cloud computing, experienced a boom during this period.

## Company Performance: 
SuperMicrocomputer may have released new products or technologies that were well-received by the market.

## External Factors:
Economic conditions, investor sentiment, or industry-specific news could have contributed to the stock's rise.

## Prediction Model: 
We prepared the data for a predictive model by creating a target variable (Prediction) and splitting the data into features (Close, Volume) and the target. Although the notebook does not include the actual model training, the data is ready for further analysis using machine learning algorithms such as Linear Regression or XGBoost.

## Conclusion : 
The analysis of SMCI's stock data revealed a clear upward trend, with a significant surge in late 2024. This increase could be due to a combination of strong company performance, favorable market conditions, and external economic factors. The data is now prepared for further predictive modeling, which could help in forecasting future stock prices and making informed investment decisions.


## Requirements

- Python 3.x
- Libraries: `lightgbm`, `pandas`, `numpy`, `yfinance`, `scikit-learn`, `matplotlib`
