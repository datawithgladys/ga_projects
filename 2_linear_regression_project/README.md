# Project 2 - Ames Housing Data and Kaggle Challenge

### Gladys Pao, SG-DSI-17

## Problem Statement

In this project, we analyse the Ames Housing Dataset provided from the Ames Assessor's Office to determine what features affect the sales prices of houses in Ames, IA. Through the development of an appropriate regression model, the sales prices of houses will be predicted using various features (variables) of houses from the Ames Housing Dataset. 

Ultimately, we aim to provide a useful prediction model for real estate agents to predict house prices for their existing and potential clients, providing useful insights on the effect of different features on real estate prices through our model.


## Executive Summary

This project examines data of two datasets on house prices in Ames, Iowa: one train dataset that covers the features of houses and their associated house prices, and one test dataset that covers the features of houses only. Through the use of the train dataset, we studied the relationship between various features of a house and their impact on the final sale price. An appropriate regression model (ridge regression model) for the prediction of house prices was chosen, which was eventually used to predict the sale prices of houses using the features from the test dataset. Finally, we studied and interpreted the ridge regression model that we used in the context of how certain features affect house prices.

Initial exploratory data analysis showed that the overall quality of a house, area-related variables (the above grade living area, and total basement square feet of a house) and the enclosed garage area of a house have moderate to high correlation with the sale price of a house. These features tend to have a positive impact on saleprices, as exhibited by the following trend: when values of any of these variables increase, the sale price tends to increase as well. Unlike positively-correlated variables, none of the negatively-correlated variables seems to have a huge negative impact on saleprice upon initial exploratory data analysis.

Another analysis of our variables was made after the selection of the ridge regression model for our house price prediction. After studying the coefficients of our variables/features after ridge regression, it appears that the location of the housing (the neighbourhood it is built in), the quality of the housing, the sale type of the listing, and the exterior of the house are all important determinants in the prediction of house prices in Ames. 

This is followed by recommendations for increasing the value of homes:<br>
1. Improve the overall quality of the whole house through renovations<br>
2. Dealing with any unfinished areas in a house, since any unfinished square footage reduces the value of a house.<br>
3. Improve the exterior of the house, particularly the roof style and material of the house (to hip style and wood shingles).<br>

Lastly, with the knowledge of how these important features can impact housing prices, real estate agents can pair this knowledge with the usage of our model to help their clients in the buying and selling of houses, providing them with better estimatation of real estate prices and explaining which features will help increase the value of their homes. 

Moving forward, we can choose to add more data of new houses sold in Ames to help the model make better price predictions. In addition, we can also choose to introduce data of houses sold outside of Ames, i.e. in other cities in Iowa, to help improve the model and eventually make useful price predictions for houses in the entire state of Iowa.

### Contents:
- Problem Statement
- Executive Summary
- Data Import
- Data Exploration and Cleaning
- Setting Variables and Cleaning Outliers
- Data-cleaning For Test Data
- More Exploratory Data Analysis
- Encoding
- Feature Engineering and Feature Selection
- Modelling
- Selection of Model
- Interpretation of Chosen Model
- Predictions for Kaggle
- Conclusion
- Sources and References


## Overview of Data
An analysis was made based on the dataset provided by the Ames Assessor’s Office, which computed assessed values for individual residential properties sold in Ames, IA from 2006 to 2010.

Source of data: Ames, Iowa Assessor’s Office<br>
A complete overview of the data dictionary can be found here: [Ames Housing Data Dictionary](http://jse.amstat.org/v19n3/decock/DataDocumentation.txt)


## Conclusion and Recommendations
The following features are important determinants in sale prices of houses:<br>
1. The location (neighbourhood) that the house is located in<br>
2. The sale type of the house<br>
3. The total area of the house<br>
4. The overall quality of the house (which also includes the total unfinished areas of the house)<br>
5. The exterior of the house (includes the exterior roof, material and style of the house)<br>

### Recommendations
To increase the value of homes, the following can be done:
1. Improve the overall quality of the whole house, since overall quality highly affects the sale price of a house. Renovations can be done to the house to help improve overall quality of a home.<br>
2. Any unfinished areas in a house, particularly the basement, must be dealt with, especially since any unfinished square footage reduces the value of a house.<br>
3. Improve the exterior of the house, particularly the roof style and material of the house (in particular, to hip style and wood shingles).

If clients are interested in investing in real estate, the following areas can be considered due to its high positive impact on sales prices:
1. Stone Brook<br>
2. Northridge Heights<br>
3. Northridge<br>

### Conclusion
After comparing the performance of all models, we decided to choose a ridge regression model for the prediction of housing sale prices due to its lower RMSE despite comparable $R^2$ score to other models. 
Through exploratory data analysis and the study of our coefficients generated by our model, we have found out that location of the housing, the quality of the housing, the sale type of the listing, the exterior of the house, and the total area (square feet) of the house are important determinants in the prediction of house prices in Ames. 
Paired with the knowledge of how these important features can impact housing prices, real estate agents can make use of the model to help their clients in the buying and selling of houses, providing them with predictions of prices and explaining what features will help their houses fetch better selling prices.

Moving forward, the model can be continuously improved by introducing more new data to it. As more houses get sold in Ames and more data is added, this will help to improve the model, hence getting better sale price predictions for real estate agents and their respective clients. 
In addition, more data of houses sold (features and its associated saleprice) from other cities in Iowa could also be added to the model so as to make the model more fitted to the entire state of Iowa, hence eventually making house price predictions for the state of Iowa in the future.
