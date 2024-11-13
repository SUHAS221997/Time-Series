Time Series Analysis on Air Passengers Dataset
This project applies time series analysis to the Air Passengers dataset, which records monthly totals of international airline passengers. The goal is to explore trends, seasonal patterns, and make future forecasts, offering insights into historical air travel growth and helping to anticipate future demands.

Dataset Overview
The Air Passengers dataset is a well-known time series dataset that contains monthly totals of international air passengers from 1949 to 1960. This dataset is commonly used for time series analysis due to its clear trend and seasonal patterns.

Key Column
Month: The month of each observation, formatted as YYYY-MM, which serves as the primary time index for analysis.
Passengers: The total number of passengers (in thousands) traveling in that month.
This structure allows for monthly time series analysis, revealing seasonal patterns and long-term trends in air passenger numbers.

Analysis Workflow

Data Preprocessing:
Ensure the Month column is properly parsed as a datetime format.
Set Month as the index to prepare for time series analysis.

Exploratory Data Analysis (EDA):
Plot the data to visually inspect trends, seasonal variations, and potential anomalies.
Calculate and visualize rolling averages to smooth out short-term fluctuations and highlight trends.

Time Series Decomposition:
Decompose the time series into trend, seasonal, and residual components to understand each factor’s impact.
Use additive or multiplicative decomposition based on the nature of the series.
Forecasting Models:

ARIMA: AutoRegressive Integrated Moving Average, useful for handling seasonality and trends in univariate time series.
SARIMA: Seasonal ARIMA, an extension of ARIMA that includes seasonal components.
Evaluate model performance using metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), or Mean Absolute Percentage Error (MAPE).

Visualization and Interpretation:
Plot the observed vs. forecasted values to assess model accuracy.
Visualize trends and seasonal components to gain insights into the growth pattern of air passenger numbers.