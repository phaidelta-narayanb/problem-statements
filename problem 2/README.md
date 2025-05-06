# Problem: Daily Minimum Temperatures in Melbourne

This dataset comprises daily minimum temperatures recorded in Melbourne, Australia, over a 10-year period.

[Data source](https://www.kaggle.com/datasets/vipullrathod/daily-min-temperatures)

## Statement

You're given a CSV dataset `daily-min-temperatures.csv` with two columns: Date and Temp, between 1981-01-01 till 1990-12-31 and temperature in °C.

Write a Python program / functions to:

1. Load the data and parse dates.

2. Resample it to get the average monthly temperature.

3. Implement a simple forecasting model (of your choice) using moving average (window=3 months).

4. Forecast the temperature for the next 3 months.

5. Plot the original series and the forecast.

6. (Optional) Validate the accuracy of the forecast on the training set itself. Is the model over/under-fitting?
