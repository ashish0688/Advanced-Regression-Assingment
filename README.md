# Advanced-Regression-Assingment
> This assignment is a programming assignment wherein are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. You will need to submit a Jupyter notebook for the same. 

## Table of Contents
* [Problem Statement](#problem-statement)
* [Business Goal](#business-goal)
* [Steps Performed](#steps-performed)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

<!-- You can include any other section that is pertinent to your problem -->

## Problem Statement
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
	1. Which variables are significant in predicting the price of a house, and
	2. How well those variables describe the price of a house.

 

Also, determine the optimal value of lambda for ridge and lasso regression.

## Business Goal
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Dataset and Data Dictionary
The following files are present inside datasets folder:

    - train.csv (dataset)
	- Data Definition.txt

## Steps Performed
Assignment is divided into following parts:

	1 Reading and Understanding the Data
	2 Data Quality Check
	3 Data Cleaning
	4 Exploratory Data Analysis
	5 Creating Dummy Variables
	6 Splitting the Data into Training and Testing Sets
	7 Rescaling the Features
	8 Building the model
	9 Conclusion

## Conclusions
The optimal lambda value in case of Ridge and Lasso is as below:
	1. Ridge - 1
	2. Lasso - 0.0001

The Mean Squared error in case of Ridge and Lasso are:
	1. Ridge - 0.015813
	2. Lasso - 0.015777

The Mean Squared Error of Lasso is slightly lower than that of Ridge

Also, since Lasso helps in feature reduction (as the coefficient value of one of the feature became 0), Lasso has a better edge over Ridge.

Hence based on Lasso, the factors that generally affect the price are the Zoning classification, Living area square feet, Overall quality and condition of the house, Foundation type of the house, Number of cars that can be accomodated in the garage, Total basement area in square feet

Therefore, the variables predicted by Lasso in the above bar chart as significant variables for predicting the price of a house.

## Technologies Used
	a. Python - 3.7.11
	b. matplotlib - 3.4.3
	c. seaborn - 0.11.2
	d. pandas - 1.2.4
	e. numpy - 1.8.5
	f. sklearn - version 0.21.3
	g. statsmodels - version 0.10.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->
## Acknowledgements

## Contact
Created by [Ashish Kumar Singh](https://github.com/ashish0688) - feel free to contact me!



