# Housing Company Assignment
    -- Submitted by Suprabhat Paul
    
## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

***The company wants to know:***

- Which variables are significant in predicting the price of a house
- How well those variables describe the price of a house

***Goal:***
- Develop a model to find the variables which are significant in predicting the price of a house.
- Determine the optimal value of lambda for ridge and lasso regression.
- It will be used by the management to understand and manipulate the business strategy to meet the demand levels and meet the customer's expectations.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- We can say the model accuracy of all the models are similar so we can choose a simple model. Now the Linear Regression model is complex, hence rejecting. Even Ridge Rigression model is also complex hence rejecting it.
- Lasso Regression model is simpler, hence we would consider that.
- The optimal lambda value in case of Ridge and Lasso is as below:
    - Ridge - 4
    - Lasso - 50
- Most important 30 features that are affecting Sales pricing are:
   - OverallQual_9                           Score: 44090.81
   - OverallQual_10                          Score: 28811.319
   - SaleCondition_Alloca                    Score: -28616.24
   - Neighborhood_StoneBr                    Score: 27458.272
   - Functional_Mod                          Score: -27408.595
   - Neighborhood_Crawfor                    Score: 23028.136
   - Neighborhood_MeadowV                    Score: -22777.991
   - KitchenQual_TA                          Score: -19807.934
   - KitchenQual_Gd                          Score: -19293.312
   - SaleCondition_Partial                   Score: 18086.014
   - Exterior1st_BrkFace                     Score: 17443.443
   - Functional_Typ                          Score: 15927.706
   - OverallQual_8                           Score: 15336.547
   - Condition1_RRAe                         Score: -14376.206
   - KitchenQual_Fa                          Score: -13807.831
   - MSSubClass_160                          Score: -13204.071
   - BsmtExposure_Gd                         Score: 12439.447
   - MSZoning_FV                             Score: 10677.755
   - Neighborhood_NoRidge                    Score: 10541.689
   - Neighborhood_BrkSide                    Score: 10172.209
   - OverallCond_8                           Score: 9456.502
   - MasVnrType_Stone                        Score: 8633.016
   - Exterior1st_CemntBd                     Score: 8270.356
   - OverallCond_3                           Score: -8254.628
   - BsmtFinType1_GLQ                        Score: 8002.555
   - Neighborhood_Edwards                    Score: -7815.645
   - OverallCond_5                           Score: -7740.807
   - Condition1_Norm                         Score: 6881.349
   - BsmtQual_TA                             Score: -6532.466
   - GarageCond_Fa                           Score: -6525.176

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
 - Python - 3.8.8
 - NumPy - 1.21.4
 - Pandas - 1.3.4
 - Seaborn - 0.11.2
 - matplotlib - 3.4.3

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
 - References:
         - upGrad: What is Exploratory Data Analysis in Python? Learn From Scratch
         - kaggle: Comprehensive data exploration with Python


## Contact
Created by Suprabhat - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->