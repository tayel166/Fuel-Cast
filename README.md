# ⛽ FuelCast IT — Weekly Fuel Price Prediction (Italy)

**FuelCast IT** is a time-series forecasting project that predicts weekly fuel prices in Italy using multiple models and a robust preprocessing pipeline.  
This repository contains data preprocessing code, model implementations (Prophet, ARIMA, SARIMA, LSTM), evaluation scripts, and demonstrating results.

> This project focuses on improving forecasting accuracy by careful preprocessing (handling missing values, outliers, normalization, and decomposition).

---

## 📖 Project Overview

Fuel prices are volatile and influenced by seasonality, trends, and external events. FuelCast IT explores and compares four forecasting approaches:

- **Prophet** — robust to missing data and good for multiple seasonalities.  
- **ARIMA** — classical univariate model (AR, I, MA) for stationary series.  
- **SARIMA** — ARIMA extended with seasonal terms.  
- **LSTM** — deep learning model for non-linear, long-term dependencies.

The repository includes preprocessing routines to clean the data, handle outliers/missing values, normalize features, and decompose seasonal patterns before training models.

---

## 🧩 Key Features

- Data cleaning and preprocessing pipeline (missing value imputation, outlier handling, normalization, decomposition).  
- Implementations and notebooks for Prophet, ARIMA, SARIMA, and LSTM.  
- Model training, validation, and comparison (error metrics and plots).  
- Visualizations of before/after preprocessing and forecasting outputs.  

---

## ⚙️ Tech Stack & Requirements

| Technology | Purpose |
|---|---|
| Python 3.8+ | Core language |
| pandas, numpy | Data processing |
| matplotlib, seaborn | Visualization |
| statsmodels | ARIMA / SARIMA |
| prophet | Prophet model |
| tensorflow / keras | LSTM |
| scikit-learn | Scaling, metrics |
| jupyter | Notebooks |
