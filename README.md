# Stock Price Volatility Research

## Overview

This project investigates stock price volatility and predictability differences between penny stocks and large-cap stocks using historical market data and statistical modeling. The research focuses on identifying whether lower-priced equities demonstrate measurably higher volatility and lower predictive stability compared to established market constituents.

Large-cap stocks were randomly selected from the S&P 500 index using a random number generator. The S&P 500 index is maintained by S&P Dow Jones Indices.

Penny stocks were selected using commonly accepted regulatory and market definitions from the U.S. Securities and Exchange Commission, which generally classifies penny stocks as low-priced securities (typically under $5) with higher risk and lower liquidity.

---

## Objectives

* Compare volatility behavior between penny stocks and large-cap stocks
* Evaluate prediction reliability using linear regression models
* Measure model confidence across different equity classes
* Analyze how price level correlates with predictability

---

## Stocks Analyzed

### Penny Stocks

A randomly selected set of qualifying low-price equities based on regulatory definitions and market screening.

### Large-Cap Stocks

Randomly selected constituents from the S&P 500 index using a random number generator to remove selection bias.

---

## Methodology

### Data Collection

Historical stock price data was collected from publicly available financial datasets in CSV format.

### Data Preprocessing

* Feature selection from historical OHLCV data
* Train-test dataset splitting
* Data cleaning and formatting

### Modeling

Each stock was modeled independently using:

* Linear Regression (scikit-learn)

### Evaluation Metrics

* R² model confidence score
* Visual comparison of actual vs predicted price movement
* Model coefficient and intercept interpretation

---

## Technologies Used

### Languages

* Python

### Libraries

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* statsmodels

---

## Future Improvements

* Add more machine learning models (Random Forest, LSTM, XGBoost)
* Include volatility indicators (ATR, Bollinger Bands)
* Automate data ingestion via financial APIs
* Expand dataset to include more market sectors and international equities
* Develop an interactive visualization dashboard for comparative analysis
