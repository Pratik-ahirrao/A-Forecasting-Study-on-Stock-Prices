# A-Forecasting-Study-on-Stock-Prices
This paper analyzes different forecasting models on stock price datasets of Microsoft, Netflix, and Tesla. Stock price datasets
are highly nonlinear and nonstationary. Daily close prices of Microsoft Corporation ( MSFT), Tesla Inc. (TSLA) and Netflix
Inc (NFLX) from Yahoo Finance for the time period of 2011 to 2021 are collected. Datasets from 2011 to 2020 are used to build
the models and testing is done on the 2021 dataset. We have used five traditional univariate forecasting models, one global
forecasting model and five deep learning models. We used five error metrics for evaluation: the Mean Absolute Scaled Error
(MASE), Symmetric Mean Absolute Percentage Error (sMAPE), Mean Absolute Error (MAE), Root Mean Squared Error
(RMSE) and Modified Symmetric Mean Absolute Percentage Error (msMAPE).
Cross-Validation is done for all forecasting models on the test set using rolling windows. We have also ensembled some
models by taking simple averages. This helps to check whether the ensembled model performed better than individuals for
these stock price datasets or not.
