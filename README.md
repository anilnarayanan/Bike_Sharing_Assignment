# Predicting Demand for Shared Bikes
This project involves building a multiple linear regression model to predict the demand for shared bikes. The goal is to identify the significant factors affecting bike demand and understand how these factors influence demand patterns. The insights gained from this model will help BoomBikes optimize their business strategy to meet post-quarantine demand and stand out in the American market.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
BoomBikes aspires to understand the demand for shared bikes among the people after the ongoing quarantine situation due to Covid-19 ends across the nation. This understanding will help them prepare to cater to the people's needs once the situation improves, stand out from other service providers, and make significant profits.

BoomBikes has contracted a consulting company to identify the factors that influence the demand for shared bikes, specifically in the American market. The key objectives are:

- To identify which variables are significant in predicting the demand for shared bikes.
- To determine how well these variables describe the bike demands.

    #### Business Goal
    Model the demand for shared bikes using the available independent variables. This model will help management understand how demand varies with different features. The insights from the model will allow them to adjust their business strategy to meet demand levels and customer expectations. Additionally, the model will help management understand the demand dynamics of a new market.

    #### Dataset
    The dataset used for this project includes various features that potentially influence the demand for shared bikes. These features may include weather conditions, seasonal effects, holiday impacts, and other relevant factors.


## Conclusions
- The model achieved an R-squared value of 0.848 and an Adjusted R-squared value of 0.811. This indicates that the model explains approximately 81.1% of the variance in bike demand, suggesting a strong fit with reliable prediction.
- The model identified temperature and weather conditions as significant predictors of bike demand. This indicates that bike usage is highly sensitive to changes in temperature and weather, suggesting that people are more likely to use bikes in favorable weather conditions.
- Seasonal variations significantly affect bike demand, with higher demand in certain seasons. This implies that bike usage patterns change throughout the year, peaking during warmer or more pleasant weather months.
- Working days and holidays have a notable impact on bike demand. Noticed higher demand on working days for commuting purposes and different on holidays for leisure activities.
- The developed model provides valuable insights into demand patterns and can help in strategic planning and decision-making.


## Technologies Used
- Python - Version 3.10.12
- pandas - Version 2.1.4
- numpy - Version 1.26.4
- statsmodels - Version 0.14.2
- matplotlib - Version 3.7.1
- seaborn - Version 0.13.1
- scikit-learn - Version 1.3.2


## Contact
Created by [@anilnarayanan]
