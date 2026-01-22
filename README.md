# Forecasting Residential Rental Prices in Rio de Janeiro (2010–2025)

### Project Overview

This project analyzes the historical evolution of residential rental prices in Rio de Janeiro and develops a time series forecasting model based on monthly data from 2010 to 2024.

The analysis combines exploratory data analysis with a univariate ARIMA model to capture long-term trends, economic cycles, and short- to medium-term dynamics in the rental market.

### Objectives

* Analyze long-term rental price behavior and market cycles

* Compare price dynamics across property typologies

* Model temporal dependencies in rental prices

* Produce a short- to medium-term forecast based on historical patterns

### Dataset

* Source: FipeZap residential rental price index

* Frequency: Monthly

* Period: 2010–2025

* Target variable: Average rental price per square meter (R$/m²)

### Exploratory Data Analysis

The exploratory analysis highlights several relevant patterns:

* A persistent upward trend in rental prices over the last 15 years, despite temporary downturns

* Clear economic cycles, particularly during the 2015–2016 recession and the COVID-19 period

* Consistent differences across property typologies, with smaller units showing higher prices per square meter

* Periods of increased volatility captured through monthly and 12-month variation metrics

* These findings provide context for the modeling phase and help interpret the forecast results.

### Modeling Approach

Rental prices are modeled using an ARIMA framework, chosen for its suitability for univariate time series with trend and temporal dependence.

* Target series: Total average rental price

* Differencing: First-order differencing to address non-stationarity

* Model selection: Based on standard diagnostics and information criteria

Residual diagnostics indicate no significant remaining autocorrelation, supporting the adequacy of the model for forecasting purposes.

### Forecast Results

The fitted model is used to generate a 24-month forecast (2026–2027).

The results suggest a continued gradual increase in rental prices, consistent with the post-pandemic recovery observed in recent years. The forecast reflects historical dynamics and should be interpreted as a trend-based projection rather than a causal estimate.

### Limitations

* The analysis relies on a univariate model and does not incorporate external drivers

* Macroeconomic variables, policy changes, and spatial factors are not explicitly modeled

* Forecasts are sensitive to historical patterns and structural changes in the market

### Future Work

* Include macroeconomic indicators such as inflation and interest rates

* Explore the impact of short-term rental platforms (e.g., Airbnb) on long-term rental prices

* Extend the analysis to a neighborhood-level time series

* Compare results with alternative forecasting models (e.g., SARIMA, Prophet)

### Tools and Libraries

Python, Pandas, NumPy, Matplotlib, Seaborn, Statsmodels

### Author

Vanessa Donato
Data Science | Time Series Analysis | Python
