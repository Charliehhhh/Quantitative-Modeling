# **Time Serie, Investment and Credit Risk Modeling**  

In this repository, we introduce and demonstrate the application of some of the most widely used techniques in time series analysis, investment portfolio optimization, investment risk and credit risk modeling. These methods are essential for anyone working in quantitative finance, data science, or economics, and they allow for deeper insights into financial data, risk assessment, and forecasting.

---

## **Project Structure**  

### **1. Economy Data Analysis**  
📄 **File**: `1_Economy_data_analysis.ipynb`  
- **Description**: Analyzes macroeconomic data to identify trends, relationships, and patterns in key economic indicators such as GDP, unemployment rates, and consumption.  
- **Methods**:  
   - Exploratory Data Analysis (EDA).  
   - Visualization of economic time series data.  
- **Use Case**: Understanding economic conditions and their effects on markets.  

---

### **2. Simple Return Volatility Analysis**  
📄 **File**: `2_Simple_Return_Volatility_Analysis.ipynb`  
- **Description**: Calculates and analyzes the simple returns and volatility of financial assets.  
- **Methods**:  
   - Daily return calculation.  
   - Rolling volatility analysis.  
- **Use Case**: Identifying asset price movements and risk levels.  

---

### **3. Drift-Naive Mean Model**  
📄 **File**: `3_Drift_Navie_Mean_Model.ipynb`  
- **Description**: Implements **drift** and **naive mean models** to forecast time series data.  
- **Methods**:  
   - Drift model forecasting.  
   - Naive forecasting methods.  
- **Use Case**: Baseline forecasts for stock prices or economic data.  

---

### **4. Time Series STL Decomposition**  
📄 **File**: `4_Timeseries_STL_Decomposition.ipynb`  
- **Description**: Decomposes time series data into **seasonal**, **trend**, and **residual** components using STL (Seasonal-Trend decomposition using Loess).  
- **Methods**:  
   - STL Decomposition.  
   - Visualization of decomposed components.  
- **Use Case**: Identifying trends, seasonality, and anomalies in time series data.  

---

### **5. Time Series Linear Model (TSLM)**  
📄 **File**: `5_Timeseries_Linear_Model.ipynb`  
- **Description**: Fits a **Time Series Linear Model** to forecast time series data using predictor variables.  
- **Methods**:  
   - Ordinary Least Squares (OLS) regression.  
   - Model evaluation (R-squared, p-values).  
- **Use Case**: Explaining relationships between variables like consumption, income, and production.  

---

### **6. Time Series Piecewise Model**  
📄 **File**: `6_Timeseries_piecewise_model.ipynb`  
- **Description**: Implements a **piecewise linear regression** model to capture structural changes in time series data.  
- **Methods**:  
   - Segment-based linear regression.  
   - Breakpoint detection.  
- **Use Case**: Modeling time series with distinct trend shifts, such as regime changes in markets.  

---

### **7. Exponential Smoothing**  
📄 **File**: `7_Exponential_Smoothing.ipynb`  
- **Description**: Applies **exponential smoothing methods** for time series forecasting.  
- **Methods**:  
   - Simple Exponential Smoothing.  
   - Holt-Winters (trend and seasonality).  
- **Use Case**: Short-term forecasts of financial or economic time series.  

---

### **8. ARIMA Model**  
📄 **File**: `8_ARIMA_model.ipynb`  
- **Description**: Implements the **ARIMA (Autoregressive Integrated Moving Average)** model for time series forecasting.  
- **Methods**:  
   - Model fitting and diagnostics.  
   - Forecasting with confidence intervals.  
- **Use Case**: Medium-term forecasting of stationary time series.  

---

### **9. GARCH Volatility Model**  
📄 **File**: `9_GARCH_Volatility_model.ipynb`  
- **Description**: Models and forecasts **financial market volatility** using GARCH models.  
- **Methods**:  
   - GARCH(1,1), TGARCH, and GJR-GARCH.  
   - Volatility clustering analysis.  
- **Use Case**: Risk assessment and volatility forecasting for stock returns.  

---

### **10. Parametric Optimization**  
📄 **File**: `10_Parametric_Optimization.ipynb`  
- **Description**: Optimizes a financial portfolio to **maximize the Sharpe ratio** while minimizing risk.  
- **Methods**:  
   - Mean-variance optimization.  
   - Efficient frontier visualization.  
- **Use Case**: Constructing an optimal investment portfolio.  

---

### **11. Credit Risk Model**  
📄 **File**: `11_Credit_Risk_model.ipynb`  
- **Description**: Implements credit risk models such as **Vasicek**, **CIR**, **Ho-Lee**, and **Hull-White** models.  
- **Methods**:  
   - Simulations of short-term interest rate paths.  
   - Visualization of credit risk dynamics.  
- **Use Case**: Pricing bonds, managing credit risk, and analyzing interest rate movements.  

---

## **How to Use**  

1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/your-username/Quantitative-Investment.git
   cd Quantitative-Investment
