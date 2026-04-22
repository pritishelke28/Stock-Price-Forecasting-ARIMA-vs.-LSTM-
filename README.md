# Stock Price Forecasting: ARIMA vs. LSTM 📈

This project explores two different approaches to predicting stock market trends using 5 years of historical data for Apple (AAPL) fetched via the `yfinance` API.

## Overview
- **ARIMA:** A statistical model that uses time-series differencing and autocorrelation to predict short-term linear trends.
- **LSTM (Long Short-Term Memory):** A deep learning neural network capable of capturing complex, non-linear patterns in financial data.

## Key Features
- Dynamic data retrieval using `yfinance`.
- Stationarity testing with the **Augmented Dickey-Fuller (ADF) test**.
- Comparative visualization of statistical vs. neural network predictions.

## How to Run
1. Clone the repo: `git clone <your-repo-link>`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the Jupyter Notebook: `Stock_Prediction_Arima_LSTM.ipynb`
