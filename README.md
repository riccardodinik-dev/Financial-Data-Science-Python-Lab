# Financial Data Science – Python Projects

This repository contains a selection of Python notebooks developed during the *Financial Data Science* course of the MSc in Finance at Bocconi University.

The notebooks apply econometric, statistical, and machine learning techniques to financial and macroeconomic datasets, with a particular focus on time-series modelling, forecasting, volatility analysis, and empirical financial research.

The objective of this repository is to document practical applications of quantitative methods commonly used in financial data analysis and decision-support systems.

---------------------------------------------------------------------------------------------------------------------------------------

## Technical Skills

The projects make use of:

- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- ARCH
- Scikit-learn
- Data cleaning and preprocessing
- Time-series econometrics
- Forecasting models
- Volatility modelling
- Machine Learning

---------------------------------------------------------------------------------------------------------------------------------------

# Repository Structure

## 01 – ARMA Modelling of Cryptocurrencies

**Dataset**
- Daily Ethereum prices

**Objective**

This notebook introduces the modelling of financial time series using ARMA processes.

The analysis includes:

- Data preprocessing and visualization
- Return computation
- Stationarity analysis
- ARMA model specification
- Model diagnostics
- Forecast generation
- Model comparison using information criteria

---------------------------------------------------------------------------------------------------------------------------------------

## 02 – Unit Roots in Interest Rates

**Dataset**
- Government bond yields

**Objective**

This notebook focuses on non-stationary financial time series and the consequences of unit roots in econometric modelling.

Main topics include:

- Interest-rate time series analysis
- Unit root testing (ADF)
- Spurious regressions
- Cointegration intuition
- Residual diagnostics
- Model validation

---------------------------------------------------------------------------------------------------------------------------------------

## 03 – Univariate Volatility Modelling

**Dataset**
- S&P 500 returns

**Objective**

Introduction to conditional volatility modelling using ARCH-type models.

Topics covered include:

- Volatility clustering
- ARCH specification
- Model estimation
- Residual diagnostics
- Conditional variance analysis
- Forecast evaluation

---------------------------------------------------------------------------------------------------------------------------------------

## 04 – Advanced Volatility Modelling

**Dataset**
- Realized Variance (RV5)

**Objective**

Extension of volatility modelling techniques through GARCH-family models.

The notebook includes:

- GARCH estimation
- Volatility persistence
- Conditional variance forecasting
- Model comparison
- Forecast performance evaluation
- Realized variance analysis

---------------------------------------------------------------------------------------------------------------------------------------

## 05 – Machine Learning for Volatility Forecasting

**Dataset**
- Realized Variance (RV5)

**Objective**

Application of machine learning techniques to volatility forecasting and comparison with traditional econometric approaches.

Models implemented include:

- Random Forest
- Gradient Boosting
- Benchmark GARCH models

The notebook evaluates predictive performance using standard forecasting metrics and compares statistical and machine learning approaches for financial volatility prediction.

---------------------------------------------------------------------------------------------------------------------------------------

## Notes

Some interactive Plotly visualizations may not be fully rendered by GitHub's notebook viewer due to rendering limitations.

The notebooks are fully executable in **Google Colab**, where all interactive visualizations and outputs are correctly displayed.

---------------------------------------------------------------------------------------------------------------------------------------

## Disclaimer

These notebooks were developed as part of the Financial Data Science coursework at Bocconi University and are intended exclusively for educational and research purposes.
