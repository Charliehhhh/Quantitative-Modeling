Financial Modeling and Time Series Analysis
This repository contains Jupyter Notebooks and Python scripts for various financial modeling and time series analysis tasks. The models and analyses cover topics such as economic data analysis, volatility modeling, time series decomposition, and credit risk evaluation.

Project Structure
The repository is structured as follows:

1. Economy Data Analysis (1_Economy_data_analysis.ipynb)
Description:
Analyzes macroeconomic data to identify trends, relationships, and patterns in key economic indicators such as GDP, unemployment rates, and consumption.
Methods:
Exploratory Data Analysis (EDA).
Visualization of economic time series data.
Use Case: Understanding economic conditions and their effects on markets.
2. Simple Return Volatility Analysis (2_Simple_Return_Volatility_Analysis.ipynb)
Description:
Calculates and analyzes the simple returns and volatility of financial assets.
Methods:
Daily return calculation.
Rolling volatility analysis.
Use Case: Identifying asset price movements and risk levels.
3. Drift-Nave Mean Model (3_Drift_Navie_Mean_Model.ipynb)
Description:
Implements drift and naive mean models to forecast time series data.
Methods:
Drift model forecasting.
Naive forecasting methods.
Use Case: Baseline forecasts for stock prices or economic data.
4. Timeseries STL Decomposition (4_Timeseries_STL_Decomposition.ipynb)
Description:
Decomposes time series data into seasonal, trend, and residual components using STL (Seasonal-Trend decomposition using Loess).
Methods:
STL Decomposition.
Visualization of decomposed components.
Use Case: Identifying trends, seasonality, and anomalies in financial or economic time series.
5. Timeseries Linear Model (5_Timeseries_Linear_Model.ipynb)
Description:
Fits a Time Series Linear Model (TSLM) to forecast time series data based on predictor variables.
Methods:
Ordinary Least Squares (OLS) regression.
Model evaluation with R-squared and p-values.
Use Case: Explaining relationships between variables such as consumption, income, and production.
6. Timeseries Piecewise Model (6_Timeseries_piecewise_model.ipynb)
Description:
Implements a piecewise linear regression model to capture structural changes in time series data.
Methods:
Segment-based linear regression.
Breakpoint detection.
Use Case: Modeling time series with distinct trend shifts, such as regime changes in markets.
7. Exponential Smoothing (7_Exponential_Smoothing.ipynb)
Description:
Applies exponential smoothing methods to forecast time series data.
Methods:
Simple Exponential Smoothing.
Holt-Winters (trend and seasonality).
Use Case: Short-term forecasts of financial or economic time series.
8. ARIMA Model (8_ARIMA_model.ipynb)
Description:
Implements the ARIMA (Autoregressive Integrated Moving Average) model for time series forecasting.
Methods:
Model fitting and diagnostics.
Forecasting with confidence intervals.
Use Case: Medium-term forecasting of stationary time series.
9. GARCH Volatility Model (9_GARCH_Volatility_model.ipynb)
Description:
Models and forecasts financial market volatility using the GARCH (Generalized Autoregressive Conditional Heteroskedasticity) model and its variants.
Methods:
GARCH(1,1), TGARCH, and GJR-GARCH.
Volatility clustering analysis.
Use Case: Risk assessment and volatility forecasting for stock returns.
10. Parametric Optimization (10_Parametric_Optimization.ipynb)
Description:
Optimizes a portfolio of financial assets to maximize the Sharpe ratio while minimizing risk.
Methods:
Mean-variance optimization.
Efficient frontier and portfolio visualization.
Use Case: Constructing an optimal investment portfolio.
11. Credit Risk Model (11_Credit_Risk_model.ipynb)
Description:
Implements and explores credit risk models such as Vasicek, CIR, Ho-Lee, and Hull-White models for interest rate and credit risk analysis.
Methods:
Simulations of short-term interest rate paths.
Visualization of credit risk dynamics.
Use Case: Pricing bonds, managing credit risk, and analyzing interest rate movements.