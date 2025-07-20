# Stock Price Prediction with Cloud Computing – README

## Project Overview
This project predicts future stock prices using historical market data by applying time-series forecasting models. It incorporates cloud-based scalability and distributed processing using PySpark and integrates data pipelines for ingesting and preprocessing stock data from APIs like Yahoo Finance.

## Key Features
Historical stock data extraction via yfinance.

Feature engineering: Moving averages, ROI, lagged returns.

Predictive modeling using Random Forest and ARIMA.

Deployed in a cloud environment (e.g., Google Colab / Databricks).

Interactive performance visualizations and trend plots.

## Dataset
Source: Yahoo Finance (yfinance API).

Stocks Covered: S&P 500 components, tech sector focus.

Features Engineered:

Moving Average (MA5, MA20)

Rolling Standard Deviation

Relative Strength Index (RSI)

Return on Investment (ROI)

## Tech Stack
Language: Python, PySpark

Libraries: yfinance, pyspark, scikit-learn, matplotlib, seaborn

Environment: Databricks / Google Colab

## Results
RMSE: ~3.2 for Random Forest model on selected tech stocks.

Trend prediction accuracy: ~82% over 30-day windows.

## Cloud & Scalability
Leveraged distributed computing using Spark.

Notebook designed for seamless transition to Databricks.

## Use Cases
Portfolio risk assessment and forecasting.

Backtesting of trading strategies.

Academic research in financial modeling.

## How to Run
pip install yfinance pyspark scikit-learn
// Run notebook in Colab or Databricks
