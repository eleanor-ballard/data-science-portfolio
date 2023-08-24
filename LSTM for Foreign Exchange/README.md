# Predicting Foreign Exchange Rates with Long Short-Term Memory Model using TensorFlow and Keras
This project began with a publicly available Kaggle data set of daily foreign exchange rates between the years 2000 and 2019. In the Foreign Exchange API calls and data prep notebook, this data set is cleaned and supplemented by data extracted from ExchangeRate-API for the years 2020, 2021 and 2022 for five target currencies: Australian Dollar, Canadian Dollar, Great British Pound, Euro and Swiss Franc. The subsequent Forex_20_years.csv file contains a data set of those 5 currencies trimmed to a length of 20 years for model training purposes in each of the currency's Forecast Model notebook. Each forecast process ends with a 15 day long forecast.

Kaggle Dataset: https://www.kaggle.com/datasets/brunotly/foreign-exchange-rates-per-dollar-20002019?resource=download
API used: https://www.exchangerate-api.com/
