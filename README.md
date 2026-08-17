# Stock Price Forecasting

This project analyzes and forecasts Apple's (AAPL) stock price using statistical
and deep learning models.

The project compares ARIMA, ARIMAX, LSTM, and GRU models for stock price forecasting
and evaluates their performance using standard error metrics.

## Features

- Historical Apple stock price analysis
- Data preprocessing and exploratory data analysis
- Correlation analysis
- Stationarity testing using the Augmented Dickey-Fuller (ADF) test
- ARIMA-based forecasting
- LSTM-based forecasting
- GRU-based forecasting
- Model comparison using RMSE and MAE
- 30-day future stock price forecasting

## Methodology

1. Downloaded historical AAPL stock data using Yahoo Finance.
2. Performed data cleaning and exploratory data analysis.
3. Checked stationarity of the closing price series using the ADF test.
4. Applied differencing where required for ARIMA modelling.
5. Fitted different ARIMA models and compared them using AIC and BIC.
6. Prepared sequential data and trained LSTM and GRU models for stock price forecasting.
7. Evaluated the models using RMSE and MAE.
8. Selected the better-performing model based on test-set performance.
9. Generated a 30-day future stock price forecast using the selected model.

## Models Used

- ARIMA
- LSTM
- GRU

## Evaluation Metrics

- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Statsmodels
- TensorFlow / Keras
- yfinance
