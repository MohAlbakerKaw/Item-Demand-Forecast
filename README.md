# Item-Demand-Forecast

Item-Demand forecasting plays a critical role in inventory management. When you can accurately predict the market demand, you can take action to ensure you hold the correct stock to maximize sales and profit.<br> 

DeepAR: 
Founded by the Amazon research team, the approach helps predict the future probability distribution of a time series based on the given past. <br>
DeepAR forecasting algorithm is a supervised learning algorithm for forecasting scalar time series using autoregressive recurrent networks. <br>
The training input for the DeepAR algorithm is one or more, target time series that have been generated by similar processes. <br>

Best Practices for using DeepAR:<br>
Don't break up the time series or provide only a part of it. You should be very aware of how to eliminate outliers when detected.<br>
Evaluate the model on unseen data.<br> 
Avoid large values for prediction length. (if far future forecast needed, consider data aggregation) <br>
Use the same value for context length as prediction length. <br>
DeepAR requires that the total number of observations available across all training time series is at least 300. 
