# Surprise Housing - Regression model for the prediction of the house rate

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. 

We are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Overall Approach](#overall-approach)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

This is a an assignment done as part of Executive PG Programme in Machine Learning & AI - January 2023, offered by IIIT - Bangalore in association with Upgrad.

Name: Bharat Hegde

Email: bharathhegde2005@gmail.com

19th May 2023

Suprise Housing.ipynb : Contains the Python code used for building the model

AssignmentQuestions.pdf : contains the answers to the additional questions.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Overall Approach

Housing Price Prediction will use Linear, Ridge and Lasso Regression
T
he solution is divided into the following sections:

* Data understanding and exploration

* Data cleaning

* Data preparation

* Model building and evaluation

The python language is used for all above steps. The libraries used as numpy, panda, matplotlib and seaborn


## Conclusions

Summarizing model details and recommendations for the company.

We will chose the Lasso regression as the final model since the metric of R2_score is slightly better compared to Ridge. For Lasso R2 Score (Train) = 0.946219 and R2 Score (Test) 0.892180

The following are the top features which influence the SalePrice ( as determined by the Lasso coefficients )

* GrLivArea 0.084268
i.e as Above grade (ground) living area square feet increases the sale price increases.

* TotalBsmtSF 0.054251
i.e As total basement Sqft area increases, the sale price increases.

* OverallQual 0.049741
i.e As Overall Quality of the house increases ( Excellent, Very Excellent, etc ) the sale price increases.

* OverallCond 0.037623
i.e As the overall condition of the house increases ( Excellent, Very excelent) etc the sale price increases.

* 2ndFlrSF 0.028755
As 2nd Floor Sqft area increases, the sale price increases.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 
- numpy
- panda
- matplotlib
- seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@bharathhegde] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->