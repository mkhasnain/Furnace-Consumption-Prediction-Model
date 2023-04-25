# Furnace-Consumption-Prediction-Model
Furnace Consumption Prediction Model using TimeSeries prediction


# Statement of Purpose:

The purpose of this regression model is to analyze and forecast the Furnace [kW] consumption based on the given dataset. By creating a linear regression model and training it on the dataset, we can predict the Furnace [kW] consumption in the future based on other features like temperature, humidity, visibility, apparent temperature, pressure, wind speed, cloud cover, wind bearing, precip intensity, dew point, and precip probability. This model can be useful for energy management companies and homeowners who want to optimize their energy consumption by predicting the Furnace [kW] usage in advance. The model's accuracy can be improved by fine-tuning the features and hyperparameters and by incorporating other time series forecasting techniques like seasonal decomposition and smoothing techniques.

### To perform prediction on the furnace_consumption dataset, you can use time series analysis and regression-based forecasting techniques. Here are some steps you can follow:

First, you need to import the dataset into a suitable software or programming language such as Python, R, or MATLAB.

Then, you should examine the data to identify any trends, seasonality, or outliers. You can use various time series visualization techniques such as line plots, box plots, and histograms to identify such patterns.

After examining the data, you can split it into training and testing datasets. Typically, you would use around 70-80% of the data for training and the remaining 20-30% for testing.

Next, you can build regression-based forecasting models such as linear regression, polynomial regression, or autoregressive integrated moving average (ARIMA). These models can help you forecast future values based on past values and other relevant variables.

You can also explore seasonal trends in the data by applying seasonal decomposition of time series (STL) or seasonal autoregressive integrated moving average (SARIMA) models.

Additionally, you can apply smoothing techniques such as moving averages, exponential smoothing, or double exponential smoothing to compare the performance of different models.

Finally, you can evaluate the performance of the models using metrics such as mean absolute error (MAE), mean squared error (MSE), and root mean squared error (RMSE). You can use these metrics to compare the accuracy of different models and select the one that performs best on the testing dataset.

By following these steps, you can build accurate regression-based forecasts for the furnace_consumption dataset and gain insights into its seasonal trends and patterns.
