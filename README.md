# -Bike_Sharing_Demand_Prediction
## This project will be explored over the previous data in order to predict the number of bikes that can be rented per hour by the company. So that customers can get the best experience without any delays. We will build different regression models and check which proves to be the best for the deployment.

![image](https://user-images.githubusercontent.com/106463464/210526981-5a56dadc-38a3-4bf0-b4c7-610faa760a2c.png)

This repository consists of Rental Bike demand prediction required at each hour of the day so that stable supply of rental bikes can be made possible. This is done by applying various Regression Machine Learning Algorithms.

Date : year-month-day

Rented Bike count - Count of bikes rented at each hour

Hour - Hour of he day

Temperature-Temperature in Celsius

Humidity - %

Windspeed - m/s

Visibility - 10m

Dew point temperature - Celsius

Solar radiation - MJ/m2

Rainfall - mm

Snowfall - cm

Seasons - Winter, Spring, Summer, Autumn

Holiday - Holiday/No holiday

Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)


## Project Flowchart:
 Loading data and Diagnosing the data
 
 Data Filtering
 
 EDA of Row data to understand inside correlations
 
 Feature Engineering
 
 Feature Selection : we are not use much beacuase of limited features in our data(only one feature elemenate using heatmap to escalate multicollinearity  issue)
 
 Model Building
 
 Model Training and Testing
 
 Model Evaluation  & Hyper Parameter tuning
  
  
  ## Models used
     Linear Regression
     
      Lasso Regression
      
      Ridge Regression
      
      Decision Tree
      
      Random Forest
      
      Gradient Boosting
      
      XGBoost
      
    Conclusions:

Bike rental count is mostly correlated with the time of the day as it is peak at 8 am morning and 6 pm at evening.


We observed that bike rental count is high during working days than non-working day.


We see that people generally prefer to bike at moderate to high temperatures and when little windy.


It is observed that highest number bike rentals counts in Autumn & Summer seasons & the lowest in winter and spring season.


We observed that the highest number of bike rentals on a clear day and the lowest on a snowy or rainy day and also increasing humidity, the number of bike rental counts decreases.

