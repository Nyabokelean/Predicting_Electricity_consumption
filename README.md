# Predicting_Electricity_consumption
## Problem Statement
Create a model that can learn the trend in consumption based on past electricity consumption data and different climatic information and predict electricity consumption on an hourly basis.
## Business Importance
An  accurate prediction allows the client to make better decisions in terms of cost and energy efficiency.

Helps avoid situations where demand exceeds available supply.
Pricing on the wholesale electricity market is organized in a way that sensitizes participants to plan their consumption and production precisely.

## Data understanding
The dataset provided had 8 variables and 26496 observations. Data was mainly collected from 2013-07-01 to 2017-06-23. The dataset has 8 variables: ID, temperature, pressure, windspeed, var1, var2, datetime, and electricity consumption (in MWh).
The data will be split into two with the training set having the first 23 days of every month and the test set having the 24th day to the end of the month. 
The table below gives a description of the variables given;

>>
* ID - Unique ID
* datetime - Date and time info on record
* Temperature - Temperature at that hour
* var1 - Anonymized feature variable 1
* var2 - Anonymized feature variable 2
* pressure - Pressure at that hour
* windspeed - Wind speed at that hour
* electricity_consumption - Electricity consumption in MWh

## Technologies Used
The problem was a time series, therefore we had to perform several operations before building our models. However the technologies we used include; 
Python, Scikit Learn, LSTM.

## Team Members
>>
* Lean Nyaboke
* Derrick Kuria
* Paul Mwaura 
* Melisa Michuki
