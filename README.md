# Predicting Residential Rental Prices in Rio de Janeiro: A Time Series Analysis
*Time-series modeling to understand long-term rental price dynamics and support housing market insights in Rio de Janeiro.*

**Dataset:** 15 years of residential rental data (2010–2024)  
**Techniques:** Exploratory Data Analysis, Time Series Modeling (ARIMA/SARIMA), Trend Analysis  
**Key Result:** Identified structural growth trends and seasonal patterns influencing rental price dynamics

---

## Business Context

Housing affordability has become an increasingly discussed topic in large Brazilian cities, particularly in tourist-driven urban areas where real estate demand is highly dynamic.

Rio de Janeiro is an example of this complexity. Rental prices are influenced by multiple factors such as tourism cycles, urban development, local infrastructure and the growing presence of rental platforms as Airbnb.

Having lived in Rio de Janeiro, I personally observed how rental prices evolved rapidly in certain neighborhoods. This raised an important analytical question: **were these changes driven by structural market trends or by temporary fluctuations?**

Understanding these dynamics is important for multiple stakeholders, including:

• Residents evaluating housing affordability  
• Real estate investors monitoring long-term trends  
• Urban planners and policymakers assessing housing pressure  

A data-driven approach helps move beyond anecdotal perception and better understand how rental markets evolve over time.

---

## Problem Statement

Can historical rental price data be used to identify structural trends and generate reasonable forecasts for residential rent prices in Rio de Janeiro?

---

## Objectives

• Perform structured exploratory analysis of historical rental price data  
• Identify long-term trends and potential seasonal behaviors  
• Apply time-series modeling techniques to forecast rental price evolution  
• Translate statistical findings into market insights  
• Demonstrate how time-series analysis can support real estate market understanding

---

## Methodology

1. **Data Cleaning and Preprocessing**  
Filtering the dataset to include only residential rental listings in Rio de Janeiro and ensuring consistent monthly observations.

2. **Exploratory Data Analysis**  
Identification of price trends, volatility patterns and structural behavior in the rental market.

3. **Time-Series Preparation**  
Aggregation and transformation of data into a monthly time series suitable for forecasting.

4. **Time-Series Modeling**  
Application of ARIMA/SARIMA methods to model historical patterns and estimate future rental price trajectories.

5. **Insight Generation**  
Interpretation of model outputs in the context of urban housing dynamics.

---

## Tools & Technologies

• Python (Pandas, NumPy)  
• Statsmodels (ARIMA / SARIMA)  
• Matplotlib  
• Seaborn  
• Time-Series Analysis Methods

---

## Exploratory Data Analysis Highlights

The exploratory analysis revealed several structural patterns in the rental market:

• **Consistent upward trend:** rental prices increased significantly over the analyzed period, indicating structural pressure in the housing market.

• **Periods of accelerated growth:** certain time windows show sharper price increases, likely linked to macroeconomic cycles and tourism-driven demand.

• **Market volatility:** short-term fluctuations suggest sensitivity to external factors such as economic conditions and housing supply.

These insights motivated the application of time-series modeling to better understand the evolution of rental prices.

![Rental price time series](Images/2Annual_Variation.png)

---

## Modeling Approach

This project uses **time-series forecasting techniques** to estimate how rental prices evolve over time.

The modeling strategy focuses on capturing:

• **Trend components**, reflecting long-term growth in housing prices  
• **Seasonality**, potentially linked to tourism cycles and housing demand  
• **Random fluctuations**, representing short-term market variability

ARIMA/SARIMA models were selected due to their strong interpretability and suitability for structured time-series forecasting.

---

## Model Performance

The selected time-series models were able to capture the **long-term upward trend** in rental prices and reproduce the main historical patterns observed in the dataset.

While forecasting accuracy depends on market stability, the model provides **reasonable projections of price trajectories** based on historical dynamics.

From a practical perspective, the analysis demonstrates how historical rental data can support **forward-looking housing market insights**, even in environments influenced by multiple external factors.

---

## Key Insights

Several relevant insights emerged from the analysis:

• **Long-term structural growth:** rental prices have shown a sustained upward trajectory over the past decade.

• **Demand-driven pressure:** tourist-driven cities such as Rio de Janeiro tend to experience stronger housing price volatility.

• **Market sensitivity:** rental prices react to macroeconomic changes and urban development cycles.

• **Forecasting potential:** time-series modeling can provide useful signals for anticipating price trajectories.


![Rental price forecast](Images/3Rental_Price_Forecast.png)

---

## Business Impact & Applications

The results of this analysis could support several real-world applications:

**Housing market monitoring**  
Real estate stakeholders can track long-term price dynamics.

**Investment planning**  
Investors may use historical patterns to evaluate market opportunities.

**Urban policy analysis**  
City planners can assess long-term housing affordability pressures.

**Market intelligence**  
Rental platforms and real estate companies can integrate price trend monitoring into strategic decision-making.

---

## Next Steps

Possible extensions of this project include:

• Incorporating macroeconomic variables (inflation, interest rates)  
• Including neighborhood-level segmentation  
• Expanding the model with additional forecasting techniques  
• Building interactive dashboards to monitor rental market dynamics

---

## Repository Structure
