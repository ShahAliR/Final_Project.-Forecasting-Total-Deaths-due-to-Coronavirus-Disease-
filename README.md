# Final_Project.-Forecasting-Total-Deaths-due-to-Coronavirus-Disease-![Coronavirus_3D_illustration_by_CDC_1600x900 (1)](https://user-the total number of deaths 
The aims of this project were:

1) Predict total number of deaths due to coronavirus during a 60-day period in eight European counties (the Netherlands, France, Germany, United Kingdom, Portugal, Spain Luxembourg and Turkey) based on everyday data from data from previous February 1st of 2019.
2) Identify the most important predictors of number of total deaths per country in the world among 17 parameters

The data have been retrieved from the "Our World in Data" website and consists of the necessary information to conduct the time series analysis. An Auto Regressive Integrated Moving Average (ARIMA) time series model was used for prediction of the total number of deaths for each of the eight countries. The dataset was cleaned and some parameters were transformed to satisfy all the necessary assumptions of the ARIMA model. For each country, the total number of deaths from February 1st of 2019 to 29 August 2022 were fed in to model as the training set and the total number of deaths between 29 August 2022 and 27 October 2022 was predicted. Validation of the models was based on comparing the predicted values against the true values in the test set. 

Furthermore, I used a linear regression model to predict the total number of deaths per country based on several national parameters such as demographics, disease rates, public health factors, and socio-economic indices. Parameters with the largest regression coefficient in this model were identified as the most important predictors of the total number of deaths per country. 

Results of the times series models are presented in the table below

![table](https://user-images.githubusercontent.com/111515711/201471507-4c9caf4d-3104-41fc-925d-683cc6b7466c.JPG)


The result of the linear regression model showed that the number of new cases, new vaccinations, and male smokers, along with GDP per Capita index are the most important parameters that predict the total number of deaths due to coronavirus per country. 
