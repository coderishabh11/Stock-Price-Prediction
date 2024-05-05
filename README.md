# Apple Stock Price Prediction with LSTM, KNN & Random Forest

This project explores three machine learning models for predicting Apple (AAPL) stock prices.

## Data Acquisition

We used the `yfinance` library in Python to extract historical closing price data for Apple stock for the past 3600 days.

## Models

1. **LSTM (Long Short-Term Memory):**
   This model utilizes the LSTM architecture to learn long-term dependencies in the historical data.

2. **KNeighborsClassifier:**
   This classifier categorizes future price movements as either increasing (class 1) or decreasing (class -1) based on historical patterns.

3. **RandomForestRegressor:**
   This regression model predicts the actual numerical value of the future closing price.

## Disclaimer

The predictions generated by these models are for informational purposes only and should not be considered financial advice.

## Future Work

- Experiment with different hyperparameters for each model.
- Explore other machine learning approaches (e.g., ARIMA, Prophet).
- Incorporate additional features like technical indicators or sentiment analysis.

## Contributions

We welcome contributions to this project! Feel free to submit a pull request with any improvements or suggestions.
