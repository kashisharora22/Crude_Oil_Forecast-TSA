## Time series analysis of Crude Oil Prices ##
This project involves the univariate time-series forecasting of Crude oil prices in India, using ARIMA and a MSE of 6.1377 has been acheived. 
The data has been collected from PPAC(Petroleum Planning and Ananlysis Cell) from April-2000 to March-2024.

**The Libraries used are-**
* For data analysis & manipulation- Numpy
* Data visualisation- Matplotlib, seaborn
* For time series analysis- statsmodels(adf test, seasonal decomposition, acf&pacf plots, ARIMA)
* For AUTOARIMA- pmdarima

The project aims to perform time-series analysis- applying adf test to test stationarity,seasonal decomposition, interpretation of detrended,deseasonalised plots, applying box-jenkins methodology for identification of order of ARIMA, evaluating ARIMA/SARIMA performance using cross validation(recursive methodology for multistep forecasting) followed by residual analysis. The predictions are made from April 2024 to January-2025 and a MSE of 6.1377 for ARIMA and 6.6290 for SARIMA.


