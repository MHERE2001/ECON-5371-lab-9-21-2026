# ECON-5371 Lab Repository

This repository contains lab materials for ECON-5371 (Time Series Analysis and Forecasting) at UTEP. 
## Lab 1

Applying unit root testing, ARIMA, and SARIMA models to a synthetic GDP dataset in Python.

**Files:**
- `lab_1/gdp_synthetic.csv` — dataset
- `lab_1/lab_1.py` — analysis script

**Raw data URL (for use in Python/pandas):**
https://raw.githubusercontent.com/MHERE2001/ECON-5371-lab-9-21-2026/refs/heads/main/lab_1/gdp_synthetic.csv



## Lab 2

Forecasting a synthetic monthly economic indicator ("Widget Sales Index") using ARIMA models — includes stationarity testing (ADF), ACF/PACF-based order selection, model comparison (AIC/BIC), residual diagnostics, and out-of-sample forecast evaluation (RMSE, MAE, MAPE).

**Files:**
- `lab_2/generate_synthetic_data.py` — generates the synthetic dataset
- `lab_2/widget_sales.csv` — dataset (96 monthly observations, 2018–2025)
- `lab_2/lab_2.py` — ARIMA forecasting analysis
- `lab_2/requirements.txt` — required Python packages