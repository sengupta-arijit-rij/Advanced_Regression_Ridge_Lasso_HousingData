# Advanced Regression Techniques; Surprise Housing Company - Australia
# Features that affect Home/Property Sales Price 



## Table of Contents
* Data Exploration
* Data Transformation
* Data Analysis
* Modelling Train Dataset using Multiple Linear Regression 
* Predicting Test Dataset using Multiple Linear Regression
* Modelling Train Dataset using Advanced Regression - Ridge
* Predicting Test Dataset using Advanced Regression - Ridge
* Modelling Train Dataset using Advanced Regression - Lasso
* Predicting Test Dataset using Advanced Regression - Lasso
* Technology Used- Python PANDAS, Statsmodel, Scipy, Matplotlib, Seaborn
* Conclusion


<!-- You can include any other section that is pertinent to your problem -->

## General Information
#
## Surprise Housing, a US-based housing company has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.
## Given, the company is looking at prospective properties to buy to enter the Australian market, we Surprise Housing, a US-based housing company has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.
## The company is looking at prospective properties to buy to enter the Australian market, we are going to build a regression model using regularization to predict the actual value of the prospective properties so that the company can use our model to decide whether it would be profitable to invest in them or not.
#
#
## The Target Dataset here is SalePrice which is a continuous variable
## We are modelling using Ridge and Lasso regression techniques which employ cross-validation and apply a penalty to the Loss Function that the model is trying to minimize
#
## The dataset has a combination of Categorical and Continuous variables, we will apply all data preprocessing techniques, however we will not be doing any manual Feature elimination. We are employing Ridge and Lasso techniques that will work on feature elimination

#
## Finally we will pridict the Test Data set based on all three regression techniques and compare the metrics as well as choose the top predictors that Business can use for their forecasting.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

#
## Conclusions
- We see Ridge Performing better than Linear Regression due to its inherent Feature selection and independence including all features available
- We also see Lasso Performing better than Ridge Regression and providing us with the most relevant features available
- We have seen a very close R-Squared scored for both techniques between Train and Test sets 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - PANDAS 
- library - MATPLOTLIB 
- library - SEABORN
- library - STATSMODEL
- library - SCIKITLEARN

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was based on [https://learn.upgrad.com/course/4617/segment/27466/242409/740997/3737983]


## Contact
Created by [Arijit Sengupta @sengupta-arijit-rij@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->