# 📊 Stock Price Forecasting using ARIMA Model

---

## (1) Problem Statement

The objective of this project is to analyze historical stock price data of a publicly traded company listed on the NSE and forecast future stock prices using time series analysis. The challenge lies in handling non-stationary data and accurately predicting short-term trends using statistical models.

---

## (2) Objective

* To preprocess and analyze stock price data
* To identify patterns and trends in time series data
* To implement the ARIMA model for forecasting
* To predict the next 30 days of stock closing prices
* To visualize and interpret forecasting results

---

## (3) Dataset

**Source:**
NSE (National Stock Exchange) Historical Data

**Features:**

* Date
* Open Price
* High Price
* Low Price
* Close Price
* Volume

**Size:**
~1 month of daily stock data (can vary depending on selected dataset)

---

## (4) Methodology

### 🔹 Data Preprocessing

* Converted date column to datetime format
* Sorted dataset chronologically
* Handled missing values using forward fill
* Selected closing price for analysis

### 🔹 Exploratory Data Analysis (EDA)

* Visualized stock price trends over time
* Identified patterns and fluctuations
* Checked stationarity using ADF Test

### 🔹 Model Building

* Applied differencing to make data stationary
* Used ACF and PACF plots to determine ARIMA parameters (p, d, q)
* Built ARIMA model using `statsmodels`

### 🔹 Evaluation

* Compared actual vs predicted values
* Analyzed model summary and residuals
* Checked overall trend accuracy

---

## (5) Results

* Successfully implemented ARIMA model for forecasting
* Generated next 30 days stock price predictions
* Observed trend behavior (upward/downward/stable based on output)

**Insights:**

* Stock prices exhibit short-term volatility
* ARIMA performs well for short-term forecasting
* Model accuracy depends on parameter tuning

---

## (6) How to Run

```bash
pip install -r requirements.txt
python main.py
```

---

## (7) Conclusion

This project demonstrates the application of time series analysis using the ARIMA model for stock price forecasting. The model effectively captures patterns in historical data and provides reasonable short-term predictions. However, external factors such as market conditions and news events are not considered, which may impact accuracy.

---

## (8) Student's Details

**Name:** Pallan Dhanush Guruswamy
**Roll No:** 39
**UIN:** 231A038
**Year:** TE-AIDS

---

## ⚖️ AI Ethics & Responsible Usage

* The dataset used is publicly available and does not violate privacy policies
* The model is used strictly for educational purposes
* Predictions should not be considered as financial advice

---
