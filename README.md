# CIND820

Stages of the project
 
1, Add the index to the dataset

2, Split data into train and test datasets

3, Check the difference effect of the training set, and do ADF test for each difference result, get the d value.

4, Plot the ACF and PACF , determine the optimal model for the lowest AIC and BIC (p, q)
 
Based on the calculation, use below 2 models to do the forcasting

ARIMA Model with p = 3, d = 1, and q = 4 in detachd

ARIMA Model with p = 2, d = 1, and q = 3 in Condo

5, Forecast for the 10 test dataset and compared with the real data (Test data) 




Content of the repository

1, TimeSeriesAnalasis_V1.0   ----- technical reports in HTML format

2, TimeSeriesAnalasis-V1.0.ipynb  -----technical reports in ipynb format

3, dataset_condo     ------Download from listing.ca

4, dataset_detached  ------Download from listing.ca

