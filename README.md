# Used-car-sale-regression

Used Car Price Prediction
This project aims to predict the prices of used cars based on various attributes using machine learning regression models.

Project Overview
The objective is to develop a predictive model for car prices, which can help sellers price their cars more competitively and assist buyers in making informed decisions.

Key Features of the Dataset
Brand & Model
Model Year
Mileage
Fuel Type
Engine Type
Transmission
Exterior & Interior Colors
Accident History
Clean Title
Price (Target Variable)
Data Collection
Data was sourced from cars.com, with web scraping techniques used to compile the dataset containing 4,009 records of car sales.

Modeling Approach
Exploratory Data Analysis (EDA): Analyzed data distributions, handled missing values, and visualized key relationships.
Feature Engineering: Encoded categorical variables and created new features like average model price.
Model Training: Multiple regression models were tested, including:
Linear Regression
Random Forest Regressor
Gradient Boosting Regressor
Results
The Random Forest model was the best performer based on the evaluation metrics, capturing the significant factors influencing car prices.

Feature Importances
Mileage: 34.6%
Model Year: 10.8%
Exterior Color Encoding: 8.2%
Horsepower: 6.7%
Others contributed less to the overall performance.
Conclusion
The developed model provides accurate predictions, enabling stakeholders to make informed pricing decisions in the used car market.
