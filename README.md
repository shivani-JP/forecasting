## PART 1: Exploratory Data Analysis

1. **Exploration and Analysis:**
   - Thoroughly explored and analyzed time series data to identify inherent patterns in real-world data.
   - Documented findings and prepared a comprehensive technical report with informative graphs.
<img width="441" alt="image" src="https://github.com/shivani-JP/ATM-Data-Timeseries-Forecasting/assets/85876559/575aaf1f-fe6d-4cfc-8451-6be16dcb0844">
<img width="421" alt="image" src="https://github.com/shivani-JP/ATM-Data-Timeseries-Forecasting/assets/85876559/b70abb13-bca9-455a-8a30-f324478007d3">


2. **Identified Patterns:**
   - Revealed an additive trend and multiplicative seasonality in the dataset.
   - Discovered additional weekly seasonality through rigorous analysis.
   - Employed statistical tests to supplement visual analysis and addressed any discrepancies.
   - Generated and examined Autocorrelation function (ACF) and partial autocorrelation function (PACF) graphs.
<img width="447" alt="image" src="https://github.com/shivani-JP/ATM-Data-Timeseries-Forecasting/assets/85876559/1288ec38-6096-432f-98d6-2fc21effc5e8">
<img width="463" alt="image" src="https://github.com/shivani-JP/ATM-Data-Timeseries-Forecasting/assets/85876559/091bc8a4-7e57-48b8-bfd8-a85104c4f43d">


3. **Conclusion:**
   - Provided a summary of patterns observed across all individual time series within the group.
   - Analyzed commonalities and differences among time series patterns, discussing implications for automated forecasting.

<img width="432" alt="image" src="https://github.com/shivani-JP/ATM-Data-Timeseries-Forecasting/assets/85876559/1af5ce80-5a66-48d8-bf0e-f83cb5f81788">
First-order differencing was applied to the time series with a lag of 1 to remove any trend. Then, the seasonal component was estimated by analyzing the data with a lag of 7 to identify recurring patterns. Subsequently, the ACF and PACF plots of Series were analyzed. The ACF plot suggests potential non-stationarity in the data, while the PACF plot reveals significant lags occurring at intervals of 7, with a decreasing level of significance.


## PART 2: Machine Learning Models for Accurate Forecasting

1. **Model Construction and Evaluation:**
   - Constructed and evaluated seven forecasting models, including exponential smoothing, ARIMA, linear regression, and neural networks.
<P></P>
<u> exponential smoothing </u>
</P>
<img width="1162" alt="Screenshot 2024-04-16 at 6 52 29 pm" src="https://github.com/shivani-JP/ATM-Data-Timeseries-Forecasting/assets/85876559/a1ce5da4-869f-4e2e-b00c-8c032e294600">

<P>
<u> ARIMA Model </u>
</P>
<img width="1147" alt="Screenshot 2024-04-16 at 6 52 38 pm" src="https://github.com/shivani-JP/ATM-Data-Timeseries-Forecasting/assets/85876559/42bb73bb-4b0d-498c-8e6e-8bdd27c107f3">

<P>
<u> Regression Model </u>
</P>
<img width="1153" alt="Screenshot 2024-04-16 at 6 52 45 pm" src="https://github.com/shivani-JP/ATM-Data-Timeseries-Forecasting/assets/85876559/c9d957d2-787c-4a56-b884-796c0581868e">
<P>
<u> Neural Network </u>
</P>
<img width="765" alt="Screenshot 2024-04-16 at 6 52 59 pm" src="https://github.com/shivani-JP/ATM-Data-Timeseries-Forecasting/assets/85876559/0ab32e9d-17f2-4f2e-95fc-e72264265670">



3. **Performance Assessment:**
   - Assessed model performance using metrics such as RMSE, MAE, MAPE, AIC, and BIC, alongside time series cross-validation techniques.

4. **Model Comparison:**
   - Compared model performance against Naïve and Seasonal Naïve models to determine the best-fit model for forecasting ATM withdrawal data.
