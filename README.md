# Project Name
> House Price Prediction

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- House Price Prediction using advanced regression algorithm like ridge and lasso regression with Grid Search cross valiadtion and K-folds. 

Finding significant predictors for house slae price.
- Find How house prices are getting affected on internal, time, external, or environment factors.
- Finding best features with which we can house prices and and detect parameters that are reducing house prices.




### Dataset Characteristics

- Dataset used:
    a. dictionary.txt: Data dictionary
    b. train.csv: dataset for modelling.
    c. sajal_tiwari.ipynb: Main Notebook.
    d. ANSWERS.pdf: Answers to questiones asked.


- New Features Created

GarageAge: age of garage when sold from it's built year | integer
		
houseAge: age of house from built when sold
		
houseRemodelAge: age of house from re-modelling year and when sold
		
remodelYears: years it took to remodel home from built year


## Conclusions
- Features affecting house sale price: 
'GarageCars', 'Exterior1st_Stucco', 'TotRmsAbvGrd', 'Neighborhood_NoRidge', 'SaleType_Con', 'houseAge', 'Neighborhood_Crawfor', 'Exterior2nd_CmentBd', 'Condition1_RRAe', 'LotArea', 'Neighborhood_Veenker', 'TotalSF', 'hasBasement', 'OverallCond', 'OverallQual', 'BsmtFullBath', 'MSSubClass_90', 'Neighborhood_StoneBr', 'Exterior2nd_ImStucc', 'hasGarage', 'MSSubClass_160', 'MSSubClass_120', 'Neighborhood_NridgHt', 'KitchenAbvGr', 'LotFrontage', 'BedroomAbvGr', 'BsmtQual', 'MSSubClass_180'

- Most significant features:
    * TotalSF: total surface area in square feet : 0.419147
    * OverallQual : Rates the overall material and finish of the house (1-10) : 0.170102
    * LotArea : Lot size in square feet : 0.108426
    * BsmtQual : Evaluates the height of the basement : 0.076856
    * GarageCars : Size of garage in car capacity : 0.075986
    
- R2 score with test dataset is 0.82751
- Mean Ansolute error with test dataset is 0.03231.


## Technologies Used
- statsmodels : version 0.13.2
- matplotlib : version 3.5.1
- pandas : version 1.4.2
- numpy : version 1.21.5
- seaborn : version 0.11.2
- sklearn : version 1.0.2

## Acknowledgements
- This project was based on [upgrad](https://www.upgrad.com)


## Contact
Created by [@sajalT05]