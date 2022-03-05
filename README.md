# Project Name
> Housing Price Prediction


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them at a higher price. The company wants to know

* Which variables are significant in predicting the price of a house, and
* How well those variables describe the price of a house
* Determine the optimal value of lambda for ride and lasso regression 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The optimal lambda value in case of Ridge and Lasso is as below: Ridge - 10 Lasso - 0.0004
- The Mean Squared error in case of Ridge and Lasso are: Ridge - 0.013743 Lasso - 0.013556 
- The Mean Squared Error of Lasso is slightly lower than that of Ridge Also, since Lasso helps in feature reduction (as the coefficient value of one of the feature became 0), Lasso has a better edge over Ridge.  Hence based on Lasso, the factors that generally affect the price are the Zoning classification, Living area square feet, Overall quality and condition of the house, Foundation type of the house, Number of cars that can be accomodated in the garage, Total basement area in square feet and the Basement finished square feet area

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - version 1.20.3
- pandas - version 1.3.4
- matplotlib - version - 3.4.3
- seaborn - version - 0.11.2
- sklearn - version - 0.24.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



## Contact
Created by [@libvenus] - feel free to contact me!
