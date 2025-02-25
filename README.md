# Project Name
> BoomBike Bike_Sharing Assignment.

#General Information
During Covid-19 when all the businesses were going through a financial crisis, BoomBikes which is a US-based bike-sharing service also experienced a decline in their revenue. As the economy recovered, the company wanted to have a enhance business plan to analyze the demand to optimize its fleet, pricing, and operational strategies.

The Business Goal was to identify some of the key factors which drives the revenue and results in profit. Some of the factors were:
1. Identifying Significant Factors Affecting Bike Demand where we will analyze correlations and trends to find what influences bike rentals the most. And these factors could be (temperature, humidity, wind), season, weekdays vs. weekends, and holidays.

2. Building a Predictive Model where in we will use Linear Regression to predict future rentals based on historical data.

3. Identify peak demand times and seasonal trends so management can optimize bike availability.

#Conclusions
1. From the dataset received, we can understand that the demand varies such as:
a. Prices increased over time from 2018 to 2019
b. Demand is higher in warm seasons such as summer and spring and less in winter season such as winter and fall.
c. The rentals are lower in holidays and more during non-holidays and more demand observed during non-holidays.
d. Weather conditions reduces demands and if it is good weather with normalized temperature then rentals are good.
2 In our normal probability plot, some target variable data points are deviating from normality.
3 From our correlation plot, we can observe that some features are positively correlated and some are negatively correlated to each other. 
4. The temp and atemp are highly positively correlated to each other, it means that both are carrying same information.The total_count, casual and registered are highly positively correlated to each other. So, we have ignored atemp, casual and registered variable for further analysis.
5. For modelling the dataset, we split the dataset into train and test in the ratio of 80:20.
Model Evaluation metrics: R-Squared (R² or the coefficient of determination) is a statistical measure in a regression model that determines the proportion of variance in the dependent variable that can be explained by the independent variable.The R-squared or coefficient of determination for our model is 0.80 on average , it means that predictor is only able to predict 80% of the variance in the target variable which is contributed by independent variables.
6. Model Evaluation metrics: Root Mean Square Error (RMSE) is the standard deviation of the residuals (prediction errors), and The mean absolute error of a model with respect to a test set is the mean of the absolute values of the individual prediction errors on over all instances in the test set.
7. For our model, Root mean square error : 717.6303209814927 and Mean absolute error : 554.292840556423

## Technologies Used
anaconda3

