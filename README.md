# TimeSeriesForecasting
Time series forecasting of Electrical Energy consumption
## Time Series Forecasting Models - Readme

This repository contains advanced time series forecasting model (ARMA) for energy consumption prediction. It aims to optimize energy distribution networks and improve operational efficiency by accurately forecasting future energy consumption patterns. The models leverage historical data to capture trends, seasonality, and complex relationships, facilitating informed decision-making for resource allocation and infrastructure planning. Collaborators and stakeholders are invited to explore and contribute to this repository, driving advancements in sustainable energy management.

### Dataset
1. Dataset is taken from International Energy Agency(IEA) monthly electricity statistics.
2. This Dataset contains Net Electricity Production, Electricity used for pumped storage, Distribution Losses of different countries and many more useful attributes.

### Models Implemented

1. ARMA (AutoRegressive Moving Average):
The ARMA model is a classic time series forecasting approach that captures the autoregressive and moving average components of the energy consumption data. It considers the historical values and lagged errors to make accurate predictions.

### Requirements

The implementation is based on Python 3.7 or later. The following libraries are required:

- NumPy
- Pandas
- Statsmodels
- TensorFlow (for LSTM)
- Matplotlib
- Seaborn (optional, for visualization)

