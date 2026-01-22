# Rio de Janeiro Rental Price Forecasting (2010–2025)

### Project Overview

This project analyzes the evolution of **residential rental prices in Rio de Janeiro** using historical time series data. 

The analysis combines exploratory data techniques with a univariate ARIMA model to capture long-term trends, economic cycles, and short- to medium-term dynamics in the rental market.

The study was motivated by an interest in understanding the structural drivers behind long-term rental price dynamics in large urban and touristic cities.

---

### Dataset

* **Source**: FipeZap (official residential rental price index)

* **Frequency**: Monthly

* **Period**: 2010–2025

* **Property typologies**: Total, 1-bedroom, 2-bedroom, 3-bedroom, and 4-bedroom units

* **Target variable**: Average rental price per square meter (R$/m²)

---

### Exploratory Data Analysis

Key findings from the EDA include:

* A **strong upward trend** in rental prices over the last 15 years

* Clear **economic cycles**, notably during the 2015–2016 recession and the COVID-19 period

* **Property typology differences**, with 1-bedroom units consistently more expensive per square meter

* Periods of increased volatility captured through monthly and 12-month variation analysis

---

### Modeling Approach

* **Method**: ARIMA (AutoRegressive Integrated Moving Average)

* **Rationale**: Suitable for univariate time series with trend and temporal dependence

* **Differencing**: First-order differencing to address non-stationarity

* **Forecast horizon**: 24 months (2026–2027)

---

### Key Insights

* Results indicate a **continued gradual increase** in rental prices, consistent with recent post-pandemic trends

* The forecasts reflect a gradual continuation of historical trends rather than abrupt structural changes

* Economic shocks influence short-term volatility without reversing long-term trends

---

### Limitations

* The analysis relies on a **univariate** model and does not incorporate external drivers

* Macroeconomic variables, policy changes, and spatial factors are not explicitly modeled

* Forecasts are sensitive to historical patterns and structural changes in the market

---

### Future Work

* Include **macroeconomic indicators** such as inflation and interest rates

* Explore the impact of **short-term rental platforms** (e.g., Airbnb) on long-term rental prices

* Perform **spatial and temporal analysis by neighborhood** to capture local heterogeneity

* Compare results with alternative forecasting models (e.g., SARIMA, Prophet)

---

### Tools and Libraries

Python, Pandas, NumPy, Matplotlib, Seaborn, Statsmodels

---

### Author

Vanessa Donato
Data Science | Time Series Analysis | Python
