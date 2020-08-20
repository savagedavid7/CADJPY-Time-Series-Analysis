# CADJPY-Time-Series-Analysis

Project Goal:
In this project I aim to test several time series tools in order to predict future movements in the value of the Canadian dollar vs. the Japanese Yen. 

**Jupyter Notebooks:**

(i)**Time Series Notebook:** in this notebook I first parse the historical futures price data for CAD/JPY and then go through several time series analysis tools. 

*Step by Step process:*
1. Decomposition using a Hodrick-Prescott filter (decompose the settle price into trend and noise).
2. Forecasting returns using an ARMA model.
3. Forecasting the exchange rate price using an ARIMA model.
4. Forecasting volatility with GARCH.

Link to notebook:
[Time-Series Notebook](time_series_analysis.ipynb)

(ii)**Linear Regression Analysis:** in this notebook I built a Scikit-Learn linear regression model to predict CAD/JPY returns with lagged CAD/JPY futures returns and categorical calendar seasonal effects.

*Step by Step process:*

1. Data preparation (creating returns and lagged returns, and splitting the data into training and testing data)
2. Fitting a linear regression model.
3. Making predictions using the testing data.
4. Out-of-sample performance.
5. In-sample performance.

Link to notebook:
[Regression Analysis Notebook](regression_analysis.ipynb)


## Time Series Analysis Results

