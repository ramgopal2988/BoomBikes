# Boom Bikes
## **Problem Statement**

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider **BoomBikes** has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands <br>

Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

**Business Goal**:

We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

**Objectives:**
The objectives include predicting significant variables influencing American market shared bike demand, determining the crucial predictors, developing a model to understand demand variations, facilitating adaptive business strategies, and exploring demand dynamics for effective decision-making. This case study aims to achieve this goal by building a multivariate linear regression model using the provided [dataset](./day.csv).

The primary objective is to identify the key variables that significantly influence the prediction of shared bike demand and assess how effectively these variables describe the patterns in bike demands.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->
## Technologies Used
- Python Version: 3.12.4
- Matplotlib Version: 3.8.4
- Numpy Version: 1.26.4
- Seaborn Version: 0.13.2
- Statsmodels Version: 0.14.2
- Scikit-Learn Version: 1.4.2


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- **cnt** is the target variable
- **cnt** is dependant on temprature, season and weather situtaions 
- **cnt** shows an upward trend during Summer and Fall. Sees dip during winters and spring.
- **cnt** and atemp are highly correlated and hence one of them can be dropped
- **cnt** depends if a weekday is a workingday or a holiday
- The equation of the best fitted line is
  - ridercount = 0.252 + 0.235 x yr + 0.023 x workingday + 0.435 x atemp - 0.13 x windspeed - 0.276 x LightRain - 0.075 x Mist - 0.1271 x spring + 0.036 x winter

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
