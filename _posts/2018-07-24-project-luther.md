---
layout: post
title: Project Luther
---
### The Story
The intent of this project is to help people who want to purchase a house or people who want to sell their houses know the value of their properties better. Since the house prices vary in different areas, in order to predict the price more precisely, I only targeted the houses sold recently in San Francisco area first to build my model. The data was obtained from the top 2 real estate website in this area, Zillow and Redfin. Zillow has built up a machine learning model called Zestimate to predict the house prices, I will further compare the price that Zestimate predicted with the price I get from my model in the later section. The main method of analysis that will be focusing on is ordinary least squares regression (OLS), which is a powerful algorithm which allows us to gain more info about the model and also perform different tests to ensure the reliability of the model.


### Data

* Recently Sold Homes in San Francisco on Zillow (2018)
* Recently Sold Homes in San Francisco on Redfin (2018)


### Analysis

Features I included in my model are as follows:
Types of Houses, Number of Bedrooms, Number of Bathrooms, Parking Space, Sqft, Cooling System, Heating System, HOA, Year Built, Zip Code

The adjusted R squred which represents the goodness of fit of the model is 0.743. This number means my model fits around 74.3% of the data. And the root mean square error which represnts how much my predicted value will be off from the actual value is USD 629,856.27. These numbers indicate there are still some rooms for improvement, which I will list the details in my future extension section.


### Future Extension

* Obtain more features to capture the variables in the real estate market
  - Demographic data
  - Interest rate in the year that houses were sold
  - Demand and supply
* Utilize the coefficient of the features to gain more insight after improving the model
* Ease of use
