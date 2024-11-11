# GMF-Investments
Tesla Stock Price Forecasting
Overview
This project forecasts Tesla (TSLA) stock prices using three different models:

ARIMA: A classical model for univariate time series.
SARIMA: Extends ARIMA with seasonality handling.
LSTM: A deep learning model that captures complex patterns in the data.
We used historical data fetched via the yfinance library and evaluated model performance with common metrics (MAE, RMSE). The best model was selected for future price forecasting.