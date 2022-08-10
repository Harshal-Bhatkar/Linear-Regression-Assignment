# Linear-Regression-Bike-Sharing-Assignment
## Table of Contents
* [Problem Statement](#problem-statement)
* [Business Goal](#business-goal)
* [Technologies Used](#technologies-used)
* [Process Involved](#process-involved)
* [Conclusions](#conclusions)


## Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

1. Which variables are significant in predicting the demand for shared bikes.
2. How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

## Business Goal
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new marke


## Technologies Used
- python - version 3.0

## Process involved
- Data analysis
- Data visualization
- Data preparation
- Model Building
- Model Evaluation


## Conclusions
We can conclude that the model(lr_4) fit isn't by chance, and has descent predictive power.
As per our final Model, the top 3 predictor variables that influences the bike booking are: 
- tmp
- yr
- season_winter

A unit increase in temp(Temperature) variable increase the bike hire numbers by 0.518565 units.
A unit increase in yr(Year) variable increase the bike hire numbers by 0.233820 units.
A unit increase in season_winter variable increase the bike hire numbers by 0.117863 units.
So it recommended to give above variables utmost importance while planning to achieve maximum demand.

Next best variables to be considered:

weathersit_LightSnowrain - A coefficient value of ‘-0.284522’ indicated that a unit increase in weathersit_LightSnowrain variable decreases bike hire numbers by 0.284522 units.
windspeed - A coefficient value of ‘-0.160958’ indicated that a unit increase in windspeed variable decreases the bike hire numbers by 0.160958 units.

The equation of our best fitted line is:

CNT(Target Varibale) = 0.152188 + (yr × 0.233820) - (holiday × 0.097638) + (temp × 0.518565) − (windspeed × 0.160958) + (season_summer × 0.080981) + (season_winter × 0.117863) - (mnth_jan × 0.045258) +(mnth_sep x 0.099009) − (weathersit_LightSnowrain ×0.284522) − (weathersit_Misty × 0.077418)

## Contact
Created by
    Harshal Bhatkar(harshalbhatkar10f98@gmail.com)

feel free to reach out to us!!

