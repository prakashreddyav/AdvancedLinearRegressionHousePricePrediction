# Project Name
> Advanced Linear Regression model for the prediction of house rates in Austrailia for US based company.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- This project is to build Multiple linear regression model for predicting house price in austarlia
- Once the model is build we should use Regularization techniques to arrive at the best model
- A US-based housing company named Surprise Housing has decided to enter the Australian market.The company is looking at prospective properties to buy to enter the market. We need to build a regression model using regularisation in order to predict the actual value of the prospective properties so that the company can decide to invest or not. The company wants to know:

    - Which variables are significant in predicting the price of a house.
    - How well those variables describe the price of a house.

## Conclusions
- Following are the different steps followed to arive at the Conclusions.
    - Problem Statement
    - Step1: Data Sourcing
    - Step 2: EDA
    - Step3: Preparing data for Linear Regression
    - Step4: Linear Regression Model Building
    - Step5: Ridge and Lasso Regression
    - Conclusion
	
- Following are inferences from EDAThe R Square test of both Ridge and lasso regressions are better than Linear regression
    - All the metrics of Lasso and Ridge regressions are same
    - Lasso regression has less variables compared to Ridge regression.
    - Hence selecting Lasso Regression as final regression.
    - Alpha for Ridge regression is 0.3 and Alpha for Lasso regression is 0.0001
    - Final Model is Lasso regression with 39 independent variables. Even though Ridge R2 is marginally better than Lasso I have selected Lasso the model is less comaplex with 39 variables as compared to ridge with 54 variables
    - Following are the top 10 significant variables in predicting the House price from Lasso Regression



## Technologies Used
- Python - version 3.0
- Pyhton libraries used - pandas, numpy, matplotlib.pyplot, seaborn, sklearn, statsmodels 

## Acknowledgements
Give credit here.
- This project was done as part of Upgrad, IIITB Master of Science in Machine Learning & AI course
- This project was based on [Master of Science in Machine Learning & AI](https://www.upgrad.com/masters-in-ml-ai-ljmu/).


## Contact
Created by [@prakashreddyav] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->