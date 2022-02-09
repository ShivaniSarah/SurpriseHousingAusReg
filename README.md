# SurpriseHousingAusReg

> A US-based housing company named 'Surprise Housing' has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The company is looking at prospective properties to buy to enter the market and decide if the company should invest in their house or not.
- We are building a regression model using regularisation in order to predict the actual value of the prospective properties
- The company wants to know which variables are significant in predicting the price of a house and how well those variables describe the price of a house.
- Dataset used here is 'train.csv' and the description of features are contained in 'data_description.txt'

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Hence we can observe that both Lasso and Ridge regression are able to get test and train score. We can use either for the final model and would be going ahead with the Lasso model as it is performing slightly better than Ridge and takes care of feature selection by itself. We dont need to worry about high dimensionality issue with 'lasso'.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used 
- pandas
- numpy
- sklearn
- seaborn
- matplotlib
- statsmodels

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project is made as an assignment of upgrad's IIITB Executive Graduation in ML and AI.


## Contact
Created by [@ShivaniSarah] - feel free to contact me :) !


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
