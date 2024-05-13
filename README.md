ARIMA Modeling Project for Forecasting Covid Cases

Project Overview
This project is centered on mastering and deploying ARIMA models to forecast Covid-19 case numbers. The auto.arima model, set with parameters (p,d,q) x (P,D,Q), is utilized to scrutinize the time series data of Covid cases for a specific state.

Model Implementation

The primary auto.arima model was fitted to the state's Covid case data.
Alternative ARIMA models were explored and fitted as deemed appropriate.
The Holt-Winters model was also considered for additional insights.
Model Selection and Forecasting

Forecasts from the best-performing model and other viable alternatives were averaged, using AICC or BIC weights for optimization.
The forecast period extended from January 1, 2021, to February 10, 2021.
