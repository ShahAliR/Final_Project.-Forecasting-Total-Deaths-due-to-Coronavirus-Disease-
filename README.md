# Final_Project.-Forecasting-Total-Deaths-due-to-Coronavirus-Disease-![Coronavirus_3D_illustration_by_CDC_1600x900 (1)](https://user-images.githubusercontent.com/111515711/200666768-457168c7-3f4f-4d50-8a77-b367b531e49c.png)
The aims of this project were:

1) Predicting total number of deaths due to the coronavirus in eight counties of Europe (the Netherlands, France, Germany, United Kingdom, Portugal, Spain Luxembourg and Turkey) for 60 days from 29 August 2022 to 27 October 2022.
2) Exploring parameters can play more role in prediction of the total number of deaths in the entire world
The data have been retrieved from "Our World in Data" and consists of the necessary information to conduct the time series analysis. The time series model that was selected to make the prediction is called Auto Regressive Integrated Moving Average (ARIMA). The data structure has been cleaned and adjusted to satisfy all the necessary assumptions to use ARIMA to make the prediction. The total number of deaths from February 1st of 2019 to 29 August 2022 were fed to model as a training.

Furthermore, I used a linear regression model to predict the total number of deaths and explore the parameters that play more important roles in this prediction.

Results of the times series model demonstrated in the table below


The result of the linear regression models showed number of new cases, new vaccination number, male smoker number and GDP per Capita index are the most important parameters to predict deaths in the entire worlds.  
