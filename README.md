# Walmart_Sales_Time_Series

# Problem Statement:

1. You are provided with the weekly sales data for their various outlets. Use statistical
analysis, EDA, outlier analysis, and handle the missing values to come up with various
insights that can give them a clear perspective on the following:
a. If the weekly sales are affected by the unemployment rate, if yes - which stores
are suffering the most?
b. If the weekly sales show a seasonal trend, when and what could be the reason?
c. Does temperature affect the weekly sales in any manner?
d. How is the Consumer Price index affecting the weekly sales of various stores?
e. Top performing stores according to the historical data.
f. The worst performing store, and how significant is the difference between the
highest and lowest performing stores.

2. Use predictive modeling techniques to forecast the sales for 5 stores (selected at random) for the next 12
weeks.

# Steps Performed:

1.	Performed EDA and plotted graphs signifying relations among different features
2.	Started the model building by first filtering the data set for 5 random stores (Stores – 1 , 3 , 5 ,7 ,9)
3.	Made use of ADF hypothesis test to see if data is stationary or not. As checked we found that data is stationary , meaning uniform variance and mean.
4.	Then created a ARIMA model for each of the 5 stores and plotted the train , test and predicted data

