# Project Topic: Weather Forecasting
- This project demonstrate 2 approaches to analyze and predict weather data. 
  1. The first approach is to use linear regression using other weather features such as temperture or wind atmospheric pressure to predict humidity.
  2. The second approach is to apply univariate time series analysis that focus only past humidity data.

# Data
- The data have been downloaded from the website http://rp5.ru/. The data are measurements collected by the
weather station 2978 in Helsinki from September 2006 to May 2019 (the data have been downloaded on 22.05.2019).

- The original data have been resampled by day, and they have been simplified in the following way:
  - Index:
    - “datetime" is the index, indicating the date in the format YYYY-MM-DD.
  - Numerical attributes:
    - “T" is the air temperature, in degrees Celsius, 2 meters above the earth’s. surface.
    - “Po" is the atmospheric pressure at weather station level, in millimeters of mercury.
    - “P" is the atmospheric pressure reduced to mean sea level, in millimeters of mercury.
    - “Ff" is the mean wind speed at a height of 10-12 meters above the earth’s surface, in meters per second.
    - “Tn" is the minimum air temperature, in degrees Celsius, over the past day.
    - “Tx" is the maximum air temperature, in degrees Celsius, over the past day.
    - “W" is the horizontal visibility, in km.
    - “Td" is the dewpoint temperature at a height of 2 meters above the earth’s surface, in degrees Celsius.
    - “U" is the relative humidity, in percentage, 2 meters above the earth’s surface.
    - “OBSERVED" is a categorical variable, where 0 (not dry) indicates that the amount of precipitation was
    more than 0.3 millimeters, and 1 (dry) indicates that there was little or no precipitation.

- The data have been split in train and test (approximately 70% of the data are the training set, and 30% are the test set),
and are divided in 4 .csv files:
  - Weather data train: contains 3140 observations, and 16 columns.
  - Weather data train labels: contains the labels ‘U mu’ and ‘OBSERVED’ for these 3140 observations.
  - weather data test: contains 1346 observations, and 16 columns
  - weather data test labels: contains the labels “U mu" and “OBSERVED" for these 1346 observationsHere a
# Project Demonstration
Please go to https://github.com/vinhng10/Weather-Forcasting/blob/master/Weather%20Forecasting.ipynb
