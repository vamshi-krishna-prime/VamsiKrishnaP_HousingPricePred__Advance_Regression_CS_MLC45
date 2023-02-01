# Project Name
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
The company is looking at prospective properties to buy to enter the market. The task is to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
+ Which variables are significant in predicting the price of a house, and
+ How well those variables describe the price of a house.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
These are the final features that should be selected for predicting the price of house, hence the equation:
```
Log(Y) = C + 1.305615(x1) + 1.172931(x2) + 1.088577(x3) + 1.069399(x4) + 0.576761(x5) + 0.355093(x6) + 0.350419(x7) + 0.334908(x8) + 0.327525(x9) + 0.321742(x10) + Error term(RSS + alpha * (sum of absolute value of coefficients))
```
> Inference: Keep a check on these predictors affecting the price of the house.
> + The higher values of positive coeeficients suggest a high sale value.
> + The higher values of negative coeeficients suggest a decrease in sale value.
> + So, when the market value of the property is lower than the Predicted Sale Price, its the time to buy.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - library - version 1.0
- Scikit - Learnlibrary - version 2.0
- Pandas - library - version 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was executed  by... vamshi krishna p
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->