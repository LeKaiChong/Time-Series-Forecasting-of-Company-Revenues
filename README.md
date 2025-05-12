# Time-Series-Forecasting-of-Company-Revenues


# Objective of the Project: Prediction of Division Revenues based on the SIC codes
Process is as such:
1) Create a WRDS account and extract relevant data by Industry SIC code
2) Handling Missing data using Forward Fill
3) nsdiffs and ndiffs
4) ACF and PACF plot (We also saw that some industries require seasonal differencing)
5) ADF Test for stationarity
# The selection of the hyperparameters for each technique are optimised based on the in sample performance 
6) STL Decomposition -> Naive and Seasonal Naive Methods
7) ARIMA/SARIMA (auto.arima vs manual ARIMA using ACF/PACF plot) model comparision based on AICC code
8) ARIMAX model with 6 exogenous macroeconomic indicators
9) VAR Test
10) Ljung Box test on all methods, shortlisting the best model with the lowest MSE in terms of out of sample and residuals that are white noise
