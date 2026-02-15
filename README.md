# Cryptocurrency Price Prediction using ARIMA, GARCH & LSTM

<p align="center">
Time-series forecasting of highly volatile cryptocurrency markets using statistical + deep learning models.
</p>

---

##  Project Highlights

-  Forecast crypto closing prices using **ARIMA, GARCH & LSTM**
-  Compare statistical vs deep learning performance
-  Detect extreme market anomalies
-  End-to-end time-series pipeline

---

##  Problem Motivation

Cryptocurrency markets are extremely volatile and nonlinear.  
Traditional models struggle to capture complex temporal dependencies.

This project investigates whether combining:

• Statistical models → **ARIMA, GARCH**  
• Deep learning → **LSTM**

can improve forecasting accuracy.

---

##  Dataset

Historical **OHLCV** data of major cryptocurrencies  
 Time span: **2017 – 2024**

Time resolutions used:
- Hourly
- 4-Hour
- Daily

---

##  Pipeline Architecture

Raw Crypto Data  
↓  
Data Cleaning & Feature Engineering  
↓  
Stationarity & Scaling  
↓  
ARIMA → Trend Modeling  
GARCH → Volatility Modeling  
LSTM → Deep Learning Forecasting  
↓  
Model Evaluation (RMSE, MAE)

---

##  Models Used

### ARIMA — Trend Forecasting
Captures linear trends and seasonality in time-series data.

### GARCH — Volatility Modeling
Models conditional variance and market risk behaviour.

### LSTM — Deep Learning Model
Learns nonlinear temporal patterns and long-term dependencies.

 **Best performer:** LSTM achieved lowest RMSE.

---

##  Anomaly Detection

Extreme market movements detected using:
- Z-Score
- IQR
- Isolation Forest

---

##  Tech Stack

| Category | Tools |
|---|---|
| Language | Python |
| Data | Pandas, NumPy |
| ML | Scikit-learn |
| Deep Learning | TensorFlow, Keras |
| Time Series | Statsmodels, ARCH |
| Visualization | Matplotlib, Seaborn |

---


