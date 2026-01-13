# SIMPLE-LINEAR-REGRESSION
Linear regression model predicting CO₂ emissions from engine size and fuel consumption data

Linear regression model predicting CO₂ emissions from engine size and fuel consumption data.

Project Overview

This project explores the relationship between engine characteristics and CO₂ emissions using a simple linear regression model. The dataset contains various attributes of car engines, including engine size, number of cylinders, and fuel consumption metrics.

The goal is to build a predictive model that estimates a vehicle’s CO₂ emissions based on its engine size and fuel consumption.

Data Insights

Most engines in the dataset have 4, 6, or 8 cylinders.

Typical engine sizes range between 2 and 4 liters.

Combined fuel consumption and CO₂ emissions show very similar distributions, indicating a strong correlation.

A strong linear relationship exists between combined fuel consumption and CO₂ emissions across three car groups.

The groups have similar intercepts but different slopes, suggesting that fuel efficiency varies by vehicle type.

Model Development

For simplicity, engine size was chosen as the predictor variable for CO₂ emissions. The dataset was split into training (80%) and testing (20%) subsets using Scikit-Learn.

Model Used

LinearRegression() from scikit-learn

Regression Equation

CO₂ Emission = 38.99 × (Engine Size) + 126.29

Model Parameters

Coefficient: 38.99

Intercept: 126.29

Model Evaluation

Metric	Value
Mean Absolute Error	24.10
Mean Squared Error	985.94
Root Mean Squared Error	31.40
R² Score	0.76
Prediction

Input Feature	Value	Predicted CO₂ Emission
Fuel Consumption (9.5 L/100 km)	—	222.82 g/km
Engine Size (2.8 L)	—	235.47 g/km
Libraries

Numpy , Pandas , Matplotlib , Scikit-learn
