# Predict 'Nilai Tukar Nelayan' (NTN) with ARIMA and Double Exponential Smoothing (DES)

<p align="justify">The Fishermen's Exchange Rate or usually called 'Nilai Tukar Nelayan' (NTN) in Bahasa can be used as a measure of fishermen's well-being.
By knowing the estimated NTN in the future, it can provide an overview of the ability of the exchange rate of capture fisheries production to the goods/services consumed by households and fishermen's production costs.
This project aims to forecast NTN in East Java using the Autoregressive Moving Average (ARIMA) method and Double Exponential Smoothing from Holt.
The best forecasting result is selected based on the smallest Mean Absolute Percentage Error (MAPE) value.</p>

### Forecast NTN with ARIMA (2,2,0)
![arima220](https://github.com/roissyahf/Predict-NTN-with-ARIMA-DES/assets/94748266/e9b37d68-e7da-4508-8eb3-079871525a61)

### Forecast NTN with DES  (∝=0.5,β=0.6)
![des0 5 0 6](https://github.com/roissyahf/Predict-NTN-with-ARIMA-DES/assets/94748266/fb052ffd-f516-4012-a6a1-43b07c383ffc)

### Comparing model performance with MAPE
![the best one](https://github.com/roissyahf/Predict-NTN-with-ARIMA-DES/assets/94748266/77fb4f5a-7ad6-4352-8262-8490258768cb)

### Conclusion
<p align="justify">The Double Exponential Smoothing (∝=0.5,β=0.6) yielded the most effective results in forecasting the Fishermen's Exchange Rate because it had the smallest MAPE,
which was 0.0092064, whereas the MAPE for the ARIMA (2,2,0) was 0.0096509. The predicted NTN results for the period of February to July 2023, respectively, are 102.294, 102.154, 102.014, 101.874, 101.734, 101.594.
</p>
