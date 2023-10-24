# Advance regression Assignment - Surprise Housing
> Problem Statement :
-- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


> Business Goal :
-- Required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)


## General Information
- The Notebook will provide the walkthrough on detailed steps for Advance regression using Lasso and Ridge.
- The company is expecting the features/variables that will help them in determining the Saleprice.
- The Dataset is provided under name- train.csv

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
The Ridge has more better R2 scores when compared to Lasso.
- Both of the models have provided best variables which will help company for predicitve analysis.

- Ridge regression alpha = 20
- Ridge columns as below:

    ['OverallQual', 'Neighborhood_Crawfor', 'Neighborhood_StoneBr',
       'Neighborhood_NridgHt', 'Exterior1st_BrkFace', 'GrLivArea',
       'Functional_Typ', 'Condition1_Norm', 'LandContour_HLS',
       'CentralAir_Y']


- Lasso regression alpha = 0.001
- Lasso Columns as below: 

    ['GrLivArea', 'Neighborhood_StoneBr', 'OverallQual',
       'Neighborhood_NridgHt', 'Neighborhood_Crawfor',
       'Exterior1st_BrkFace', 'GarageCars', 'Condition1_Norm',
       'Functional_Typ', 'CentralAir_Y']
       
- Lasso in turn does feature engineering as we can see the coeffecient of 270 features out of 356 are brought to 0, resulting 86 columns being processed.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Contact
Created by [@soham1827] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
