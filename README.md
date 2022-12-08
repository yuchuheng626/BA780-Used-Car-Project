# BA780-Used-Car-Project
BA780 Used Car Price Project

Contributors: Chuheng (Kevin) Yu, Shih-han (Elle) Juan, Sifan Zhu, Weiming (Kevin) Wang, Ziyuan Li


## Project Definition
The globally used car market size was valued at $1.50 trillion in 2021, and it is projected to reach \$2.75 trillion by 2030. Moreover, the average used car price in the US has also increased by around 30%. On the demand side, around 8 out of 10 drivers’ first car is a used car in the United States. Our group wants to use EDA and regression to help customers save money and estimate a reliable price for a used vehicle. 

The goal of this project is to identify and evaluate the price of used cars based on their features. We will implement EDA methods and a regression model in python to help customers to identify what characteristics of a used car would affect the price.


##Report Summary
Our notebook mainly consists of three parts:

- First structure our notebook with simple variable exploration. By investigating each individual variable separately, we will understand what each variable is consisted of, and how they will cause the price variation, checking if they have a correlation with price
- Select the features(fuel type, drive, vehicle type) that have a correlation with the price, further interacted with manufacturers, to deeply analyze how these features will impact the price
- EDA helps us to understand the dataset and each feature comprehensively, and our team later build up a regression model, to predict the price of used vehicles, and better assist the people who are interested in buying used cars
- After trying a couple of regression models, RandomForest has the best performance with the lowest MSE and RMSE score. RandomForest regression model indicates that year, 4 cylinders, odometer, automatic transmission, and fwd drive type are the most affect attributes on price
