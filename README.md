Cryptocurrency Price Prediction using ARIMA, GARCH & LSTM 📈
Overview

This project explores time-series forecasting techniques to predict cryptocurrency closing prices.
The goal was to compare traditional statistical models with deep learning approaches and evaluate their effectiveness on highly volatile financial data.

The repository includes the full notebook and experimental workflow used for modeling and evaluation.

Problem Statement

Cryptocurrency markets exhibit extreme volatility and nonlinear behaviour, making forecasting challenging.
This project investigates whether combining statistical time-series models with deep learning can improve prediction accuracy.

Dataset

Historical OHLCV (Open, High, Low, Close, Volume) data for major cryptocurrencies from 2017–2024 was used.

Time resolutions:

Hourly

4-hour

Daily

Methodology
Data Preprocessing

Handling missing values

Time-series resampling

Stationarity checks

Normalization using MinMax scaling

Feature Engineering

To capture market behaviour, several time-series features were created:

Moving averages

Rolling mean and rolling standard deviation

Lag features

Volatility indicators

Models Implemented
ARIMA – Trend Forecasting

Used to model linear trends and seasonality in price movements.

GARCH – Volatility Modeling

Used to model conditional variance and capture market risk/volatility.

LSTM – Deep Learning Model

A multi-layer LSTM network was trained to learn nonlinear temporal dependencies in crypto price data.

Anomaly Detection

Extreme market movements were detected using:

Z-Score

Interquartile Range (IQR)

Isolation Forest

Model Evaluation

Models were evaluated using:

RMSE (Root Mean Squared Error)

MAE (Mean Absolute Error)

Result:
The LSTM model achieved the lowest prediction error and captured nonlinear market patterns more effectively than ARIMA and GARCH.

Tech Stack

Python

Pandas & NumPy

Scikit-learn

TensorFlow / Keras

Statsmodels

ARCH (GARCH)

Matplotlib & Seaborn
