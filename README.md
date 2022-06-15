# Bike Sharing Assignment

Datasets were collected and processed for further consumption. This included Removing the null values, Duplicates, Imputation, and correction of outliers. 
EDA method used to analyse the datasets very well for the better understanding.
The analysis was visualised clearly. This included pair plot, box plots, heat map. 
Creating the test and training data to build the model
Then, create the model and evaluvare the models


## Table of Contents
* Problem Statement
* Reading and Understanding the Data
* Creating Dummy Variables
* creating training and testing data set.
* Visualising the Data
* Rescaling the Feature
* Building a linear model
* Residual Analysis of the train data
* Model Evaluation
* Final Result


## General Information

BoomBikes is a US based Bike Sharing company which has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

Essentially, the company wants —
    To identify the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19

Datasets Inputs: 
Dataset1 = day.csv (Contains ample amount of features of the bike sharing count for 2 years)
Dataset2 = Readme.txt (Description of the features present in the Dataset1)


## Conclusions
Based on the model, the below predictor variables that influenced the bike renting. So these variables are utmost importent when planning for the after pandamic business.
- Temperature: When temperature increase one units, the bike renting numbers will increase 0.5499 units
- Weather: When weathersit - 3 increase one units, the bike renting numbers will decrease by 0.288 units Note: weathersit - 3 is Light Snow, Light 		Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
- Year: Based on this model outcome, the bike renting numbers will decrease by 0.233 units on every year
- Season: Season =4 increase a unit, the bike renting number will increase by 0.132 units.
- Windspeed: Bike renting is decreasing 0.155 units if the windspeed increase a unit.

## Technologies Used
- library - pandas
- library - matplotlib
- library - seaborn
- library - sklearn
- library - statsmodels.api

## Driving factors
- yr
- workingday
- temp
- windspeed
- season_2
- season_4
- mnth_9
- weekday_6
- weathersit_2
- weathersit_3

## Acknowledgements
Thanks to upgrad for letting us work with the real world datasets. 


## Contact
Created by [@Pandimuneeswara] - feel free to contact me!
