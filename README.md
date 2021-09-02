**# 1. Data description**

WTI is a monthly average price of the West Texas Intermediate benchmark crude oil from 1995 until July 2021. Data was taken from a public source at https://sproule.com/price-forecast/ "Escalated Forecast " link.

**#2. Question of interest**

The goal of of the project is to perform exploratory analysis to help select appropriate parameters for ETS and ARIMA models and use models to produce forecasts. It will be attempted to select the model that would forecast most accurately against the test data of interest: year 2020 and first 7 months of 2021, a period when the global COVID-19 happened and adversely affected the oil industry. Test errors will be quantified and will be used to assess each model's performance. After models for ETS and ARIMA methods has been selected and tested, the next questions that I would like to address below are:

If a training set of a shorter length is chosen, would the model be able to predict better? 
and 
If the year 2020 is excluded from the test set, would the model be able to predict January through 2021?
