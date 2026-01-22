# Rio de Janeiro Rental Price Forecasting (2010–2025)

### Project Overview

This project analyzes the evolution of **residential rental prices in Rio de Janeiro** using historical time series data. 

The analysis combines exploratory data techniques with a univariate ARIMA model to capture long-term trends, economic cycles, and short- to medium-term dynamics in the rental market.

The study was motivated by an interest in understanding the structural drivers behind long-term rental price dynamics in large urban and touristic cities.

### Objectives

* Analyze long-term rental price behavior and market cycles

* Compare price dynamics across property typologies

* Model temporal dependencies in rental prices

* Produce a short- to medium-term forecast based on historical patterns

### Dataset

* **Source**: FipeZap (official residential rental price index)

* **Frequency**: Monthly

* **Period**: 2010–2025

* **Target variable**: Average rental price per square meter (R$/m²)

### Exploratory Data Analysis

Key findings from the EDA include:

* A **strong upward trend** in rental prices over the last 15 years, despite temporary downturns

* Clear **economic cycles**, notably during the 2015–2016 recession and the COVID-19 period

* **Property typology differences**, with 1-bedroom units consistently more expensive per square meter

* Periods of increased volatility captured through monthly and 12-month variation analysis



### Modeling Approach

* **Method**: ARIMA (AutoRegressive Integrated Moving Average)

* **Rationale**: Suitable for univariate time series with trend and temporal dependence

* **Target series**: Total average rental price (`rent_price_total`)

* **Differencing**: First-order differencing to address non-stationarity

* **Model selection**: Based on standard diagnostics and information criteria

Model diagnostics indicate that residuals behave like white noise, supporting the adequacy of the chosen specification.

### Forecast Results

* Forecast horizon: **24 months (2026–2027)**

* Results indicate a **continued gradual increase** in rental prices, consistent with recent post-pandemic trends

* The forecast reflects historical dynamics rather than exogenous assumptions


### Limitations

* The analysis relies on a **univariate** model and does not incorporate external drivers

* Macroeconomic variables, policy changes, and spatial factors are not explicitly modeled

* Forecasts are sensitive to historical patterns and structural changes in the market

### Future Work

* Include **macroeconomic indicators** such as inflation and interest rates

* Explore the impact of **short-term rental platforms** (e.g., Airbnb) on long-term rental prices

* Perform **spatial and temporal analysis by neighborhood** to capture local heterogeneity

* Compare results with alternative forecasting models (e.g., SARIMA, Prophet)

### Tools and Libraries

Python, Pandas, NumPy, Matplotlib, Seaborn, Statsmodels

### Author

Vanessa Donato
Data Science | Time Series Analysis | Python
