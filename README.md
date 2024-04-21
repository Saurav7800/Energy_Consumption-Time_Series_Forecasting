# Energy Consumption - Time Series Forecasting

This Python project focuses on time series forecasting using the XGBoost machine learning model to predict energy consumption. The dataset utilized for this project is the PJM Hourly Energy Consumption Data obtained from Kaggle.

## About the Dataset

The PJM Hourly Energy Consumption Data is sourced from Kaggle and comprises hourly power consumption readings in megawatts (MW). It originates from PJM Interconnection LLC (PJM), a regional transmission organization (RTO) in the United States. PJM is part of the Eastern Interconnection grid. It operates an electric transmission system serving all or parts of Delaware, Illinois, Indiana, Kentucky, Maryland, Michigan, New Jersey, North Carolina, Ohio, Pennsylvania, Tennessee, Virginia, West Virginia, and the District of Columbia. The dataset may have missing data for certain dates or regions due to changes in PJM's regions over the years.

## Project Goals

1. Split the dataset into training and test sets to develop a predictive model for energy consumption.
2. Identify trends in energy consumption based on factors such as time of day, holidays, and long-term patterns.
3. Analyze how daily consumption patterns vary depending on the time of year, contrasting summer and winter trends.

## Files

- **PJME_hourly.csv**: Contains the raw energy consumption data for analysis.

## Dependencies

- pandas
- numpy
- matplotlib.pyplot
- seaborn
- xgboost
- sklearn.metrics (mean_squared_error)

## Acknowledgements

- Kaggle for hosting the dataset.
- Special thanks to [Rob Mulla](https://www.youtube.com/@robmulla)'s YouTube channel for insightful tutorials and guidance on time series forecasting and machine learning.


Happy forecasting!
