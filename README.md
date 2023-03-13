# Bike-Sharing-Demand-Prediction
![ddareungi-another-name-seoul-bike-sharing-system-korea-oct-there-hundreds-stations-renting-returning-all-165838152](https://user-images.githubusercontent.com/123405300/224766816-39dacbd6-951b-4abe-ab34-2a3a5234c66e.jpg)


📖Introduction
Rental bikes have been introduced in many urban cities to enhance mobility comfort. It is crucial to make rental bikes available and accessible to the public at the right time to reduce waiting time. Hence, predicting the bike count required at each hour is essential for a stable supply of rental bikes in the city.


📖Problem Statements
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.


📖Approach
The Seoul Bike Sharing Demand Prediction project aims to predict the demand for shared bikes in Seoul based on various features including temperature, rainfall, season,Visibility and snowfall, etc. The project involves the following stages:
Know the dataset
Understanding Your Variables
Data wrangling
EDA
Hypothesis testing
Feature Engineering & Data Pre-processing
ML model implementation - Linear regression, Decision Tree, Random Forest Classifier, LightGBM & XG Boost Classifier
Conclusion



📖Conclusion
There is a clear seasonal trend in bike rental demand, with higher demand during the summer months and lower demand during the winter months.

Hourly bike rental demand shows a bimodal distribution, with peaks during the morning and evening rush hours.

From April to August and in October, there are more bike rentals (more than 750 bike rentals per hour).

During non-holidays (>700 rented bike per hour), there are more bike rentals compared to holidays (approximately 500 rented bikes per hour). However, it should be noted that the number of people who prefer to rent bikes on holidays is not too low.

Rental bikes are more popular on functioning days, while on non-functioning days, rental bike activity is minimal or close to zero.

Weekdays have higher demand than weekends, with Monday through Friday showing the highest demand. However, weekends do not have significantly lower demand.

Temperature and humidity have a positive correlation with bike rental demand, while windspeed has a negative correlation.

The R2 scores of linear regression, Decision Tree, Random forest, LightGBM and XGBoost are 0.75, 0.91, 0.93, 0.92 and 0.94, respectively. These scores indicate that the models are good fits for test dataset.

The final model, XGBoost, can be used to predict hourly bike rental demand with a reasonable level of accuracy, which can be useful for bike rental companies in managing inventory and planning for demand.

The results of the project can inform business strategy, such as identifying the most profitable times to operate bike rental stations.
