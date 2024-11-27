# Bike_Sharing_Assignment
This assignment is a programming assignment wherein you have to build a multiple linear regression model for the prediction of demand for shared bikes. You will need to submit a Jupyter notebook for the same.

## Table of Contents
* [Problem Statement](#problem-statement)
* [Business Objective](#business-objective)
* [Technologies Used](#technologies-used)
* [Recommendations](#recommendations)
* [Acknowledgements](#acknowledgements)

## Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

## Business Goal:

You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Technologies Used:
* Python - version 3.11.4
* Matplotlib - version 3.7.1
* Numpy - version 1.24.3
* Pandas - version 1.5.3
* Seaborn - version 0.12.2
* Statsmodels - version 0.14.0
* Scikit-Learn - version 1.3.0

## Recommendations:

The equation of the best fit line is given by:
cnt = 1.04 * year + 0.47 * temp + 0.28 * September + 0.28 * Saturday + 0.25 * workingday + 0.24 * Winter -0.29 * July -0.35 * Misty & Cloudy -0.5 * Spring -1.35 * Light Snow & Rain -0.51

Based on the equation, the significant Variables for Predicting Bike Demand are:
* Workingday: Positive impact on demand.
* Temperature: Positive impact on demand.
* Year: Positive impact on demand.
* Seasons: Winter has high demand whereas Spring has low demand.
* Months: September show significant demand and July show negative demand.
* Weather Situation: Bad and moderate weather conditions affect demand.

## Acknowledgements
This project was inspired by live session of upGrad on Industry Relevance of Linear Regression Models by Shivam Garg
UpGrad tutorials on Linear Regression on the learning platform

## Contributors:
Haripriya_Pamu




