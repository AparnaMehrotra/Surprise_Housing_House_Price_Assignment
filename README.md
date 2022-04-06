# US Housing Company Assignment
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

 > The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

>The company wants to know:

- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.
- Also, determine the optimal value of lambda for ridge and lasso regression.




## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- We are required to create a model to predict the house prices using regularisation techniques.
- This model will help the business to understand most important features affecting house prices.
- They can accordingly work on strategy to yield high returns.
- Further, the model will help the business to understand the pricing dynamics of housing market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Optimum parameters through Ridge Regression
    - lambda : 0.5
    - Mean Squared Error : 0.0187
    - R-squared on train data : 0.9180
    - R-squared on test data : 0.8573
    
- Top 10 best predictor for Ridge are -
    - 'GrLivArea'
    - 'OverallQual'
    - 'LotArea'
    - 'MSZoning_FV'
    - 'OverallCond'
    - 'MSZoning_RL'
    - 'GarageCars'
    - '1stFlrSF'
    - 'GarageQual'
    - 'SaleCondition_AdjLand'

- Optimum parameters through Lasso Regression
    - lambda : 0.0002
    - Mean Squared Error : 0.0192
    - R-squared on train data : 0.9163
    - R-squared on test data : 0.8539
    
- Top 10 best predictor for Lasso are -
    - 'GrLivArea'
    - 'OverallQual'
    - 'LotArea'
    - 'OverallCond'
    - 'GarageCars'
    - 'MSZoning_FV'
    - '1stFlrSF'
    - 'GarageQual'
    - 'BsmtQual'
    - 'SaleType_New'  
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas library - version 1.3.5
- numpy library - version 1.20.1
- matplotlib library - version 3.3.4
- seaborn library - version 0.11.1
- statsmodels - version 0.12.2
- sklearn - version 0.24.1
    - sklearn.linear_model
    - sklearn.preprocessing
    - sklearn.model_selection
    - sklearn.feature_selection
    - sklearn.metrics

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was based on model regularization(using ridge and lasso), an Advance Regression Module for the Executive PG Programme in Machine Learning & AI - IIIT,Bangalore.


## Contributors
- <a href="https://github.com/AparnaMehrotra/">Aparna Mehrotra</a>


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

