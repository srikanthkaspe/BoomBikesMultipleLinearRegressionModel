# Boom Bikes Multiple Linear Regression Case Study


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
#### Background
A bike-sharing system is a facility that offers bicycles for temporary use, either for a fee or free of charge. Numerous bike-sharing platforms enable users to rent a bicycle from a "dock", typically managed by a computer. Here, the user provides their payment details, and the system releases the bike. The user can then return this bike to any other dock within the same network.

### Problem Statement
- BoomBikes, a bike-sharing company based in the US, has recently experienced significant revenue losses due to the ongoing Corona pandemic. The current market conditions are proving challenging for the company to maintain its operations. As a result, they have decided to devise a strategic business plan to boost their revenue as soon as the ongoing lockdown is lifted, and the economy returns to a stable state. In this endeavor, BoomBikes aims to gauge the demand for shared bikes among the public once the nationwide quarantine due to Covid-19 concludes. They have strategized this to equip themselves to meet the people's requirements once the situation improves universally, differentiate themselves from other service providers, and generate substantial profits.

#### Business Goal
- You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

### Data
- The data set is a csv file with the bike rentals data for the Boom Bikes.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- The primary steps incorporated in the Python notebook encompass understanding the data, visualising the data, pre-processing the data, training the model, selecting the features, analysing the residuals, and evaluating the model on the test set.

- Techniques such as Exploratory Data Analysis (EDA), p-value, Variance Inflation Factor (VIF), Recursive Feature Elimination (RFE) were employed, and the model was constructed using the statsmodels library.

- The R-squared value for the training set is 84.0%, while the test set has a value of 80.8%. The adjusted R-squared value for the training set is 83.6%, whereas the test set has a value of 78.7%. The difference in R^2 between the training and test sets is 3.1%, and the difference in adjusted R^2 between the training and test sets is 4.8%, which is less than 5%. This indicates that our model accurately explains the variance on the test set to a large extent, leading us to conclude that it is a robust model.

### Strategic Objectives:
- BoomBikes, a bike-sharing provider in the US, could concentrate more on the impact of Temperature on bike rentals.
- There was a noticeable increase in bike demand in 2019 compared to 2018. Despite the current revenue dips due to the Corona pandemic, the company can strategize based on this trend, anticipating a recovery once the pandemic subsides.
- The company could pay more attention to the Summer and Winter seasons, as well as the months of August and September. Weekends and working days also seem to have a significant influence on bike rentals.
- The Spring season has been observed to have negative coefficients and is negatively correlated with bike rentals. To boost demand during this period, the company could consider offering special deals or promotions.
- Regarding the 'weathersit' variable, negative coefficients have been observed for Mist + Cloudy and Light Snow weather conditions. Offering incentives during these weather conditions could potentially increase demand.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - version 1.24.3
- pandas - version 2.0.3
- matplotlib - version 3.7.2
- seaborn - version 0.12.2
- scipy - version 1.11.1
- sklearn - version 1.3.0
- statsmodels - version 0.14.0
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This project was inspired by UpGrad IITB Programme as a case study for the Machine Learning and Artificial Intelligence course.



## Contact
Created by [@srikanthkaspe] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
