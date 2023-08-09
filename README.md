# Forecasting Daily Exchange Rates: USD-EUR & Impact of Oil Prices

## Background

The relationship between oil prices and currency exchange rates, especially the USD and Euro, has historically been a focal point for both academia and the financial industry. Oil, being a primary commodity with global demand, influences macroeconomic indicators, which may in turn impact exchange rates. With the U.S. being a major consumer and producer of oil, and the Eurozone being a significant consumer region, shifts in oil prices can have ramifications on the USD-EUR exchange dynamics.

This project specifically delves into how daily fluctuations in oil prices might correlate with and potentially predict changes in the USD-EUR exchange rate.

## Strategy

1. **Data Collection:** 
   - **USD-EUR Exchange Rates** are sourced from [Yahoo Finance](https://finance.yahoo.com/).
   - **Oil Prices** are fetched from [Nasdaq](https://www.nasdaq.com/).

2. **Preprocessing:** After gathering the datasets, necessary preprocessing steps such as data cleaning, normalization, and time-series alignment are performed.

3. **Model Implementation:** Employing a suitable time series forecasting model that considers external regressors or predictors. This allows us to account for the oil prices when forecasting the USD-EUR exchange rate.

4. **Evaluation:** Model performance is evaluated using appropriate metrics like RMSE (Root Mean Squared Error), MAE (Mean Absolute Error), and possibly out-of-sample validation.

5. **Forecast:** Generate future exchange rate predictions while considering potential shifts in oil prices.

For more technical details, code implementation, and results, please explore the repository further.

## Teaser

https://github.com/pravin-raut/TimeSeries_USD-EUR_WithOilImpact/assets/65663124/ff1fc9b4-e325-420c-a6a1-e443bb0f4750

