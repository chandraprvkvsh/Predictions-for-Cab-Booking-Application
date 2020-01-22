# Predictions-for-Cab-Booking-Application
# Brief introduction

Objective of this project was to combine historical usage pattern along with the open data sources like weather data to forecast cab booking demand in a city

The project involved Visualization, Outlier Analysis, Missing value analysis, Correlation Analysis, Feature Engineering, Hyperparameter tuning, Regression Analysis, Ensemble Model.

In this project most of the regression algorithms were used :
Linear regression, Ridge regression, Lasso regression, RandomForest regressor, AdaBoost regressor, GradientBoosting regressor, XGBoost regressor.

Pandas, Matplotlib and Scikit-Learn were used.

# Details about the project

BACKGROUND:-

Cab booking system is the process where renting a cab is automated through an app throughout a city. Using this app, People can book a cab from one location to another location.  

Being a cab booking App Company, exploiting the understanding of cab supply and demand could increase the efficiency of their service and enhance user experience by minimizing waiting time.

Objective of this project is to combine historical usage pattern along with 
the open data sources like weather data to forecast cab booking demand in a city.

PROCESS FLOW:-

You will be provided with hourly renting data span of two years. Data is randomly divided into train and test set. You must predict the total count of cabs booked in each hour covered by the test set, using the information available prior to the booking period.
You need to append the train label dataset to train.csv as ‘Total_booking’ column.

Please find the descriptions of the columns present in the datasets below.

1) datetime-hourly date +timestamp 
2) season-spring, summer, autumn, winter
3) holiday-whether the day is considered a holiday
4) workingday-whether the day is neither a weekend nor holiday
5) weather-Clear , Cloudy,  Light Rain, Heavy temp-temperature in Celsius
6) atemp-"feels like" temperature in Celsius
7) humidity-relative humidity
8) windspeed-wind speed
9) Total_booking-number of total booking

TASKS:-

Following are the tasks, which need to be developed while executing the project:

Task1:
1. Visualize data using different visualizations to generate interesting insights.
2. Outlier Analysis
3. Missing value analysis
4. Visualizing Total_booking Vs other features to generate insights
5. Correlation Analysis

Task2:
1. Feature Engineering
2. Grid search
3. Regression Analysis
4. Ensemble Model
