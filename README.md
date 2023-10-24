# Upgrad - US Suprise Housing Regularized MLR Assignment 
 **submisson for Regularized MLR assignment from upgrad IITB, by Ajith Shenoy**

## Problem Statement
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

## Business Goal:
we are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Packages Used
- scikit-learn==1.2.2
- seaborn==0.12.2
- statsmodels==0.14.0
- pandas==1.5.3

## Conclusion
- Optimal alpha value for ridge is : 3.0 and for lasso its 0.001
- We will choose **Lasso** as the best model with alpha value 0.001 ,as it enables feature selection the performance is also quite good.
- lasso Training R-Squared:0.923,Test R-Squared:0.922 , Train RMSLE:0.108 Test RMSLE:0.117
- 'GrLivArea', 'OverallQual', '1stFlrSF', 'OverallCond', 'GarageArea' are the top 5 most important features that infleunce sale price.
