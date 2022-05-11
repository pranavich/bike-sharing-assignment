# Multiple Linear Regression Model For The Prediction Of Demand For Shared Boom Bikes
*	This is to understood the driving factors (or driver variables) behind sharing bike, i.e. the variables which are highly corelated for target variable, using linear regression model we are checking which features are best and high corelated for booking the bike for rentals.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information

* Problem Statment
	A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

	A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

	In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

	They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. 
	
* The company wants to know:
	•	Which variables are significant in predicting the demand for shared bikes.
	•	How well those variables describe the bike demands

* Business Goal

	Business goal is required to Model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.


## Conclusions 

- As per the final model, the top 3 predictor variables that influences bike booking are:
- Temperature (Temp) A coefficient value of ‘0.579’ indicated that a temperature has significant impact on bike rentals
- Year (yr) A coefficient value of ‘0.232’ indicated that a year wise the rental numbers are increasing
- Light Rain & Snow (weathersit =3) A coefficient value of ‘-0.295’ indicated that the light snow and rain deters people from renting out bikes
- It is recommended to give utmost importance to these three variables while planning to achieve maximum bike rental booking.As high temperature and good weather positively impacts bike rentals, it is recommended that bike availability and promotions to be increased during summer months to further increase bike rentals.


## Technologies Used

- Python - version 3.7
- Numpy - v1.21.5
- sklearn - 0.24.2
- Pandas  - v1.3.5
- Seaborn - v0.11.2

## Acknowledgements
Give credit here.
- This project was inspired by UpGrad Learning platform in understaning Linear Regression


## Contact
Created by [@Pranavi][https://github.com/pranavich/bike-sharing-assignment] - feel free to contact me!

