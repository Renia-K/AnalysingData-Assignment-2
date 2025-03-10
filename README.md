# Analysing Data | Assignment 2

## Overview
This project aims to predict fanfiction story success from various literary quality indicators through Simple Linear Regression. The data are real research outcomes of the GOLEM KG consisting of fanfiction stories' success in the form of “kudos”. We explore the correlation between this success and various indicators of literary quality such as Automated Readability Index (ARI), Flesch Grade (FG), Flesch Ease (FE), Mean Segmental Type-Token Ratio (MSTTR), word count, and comment count.


## Data

Data is provided in the data_full.csv file and contains the following columns:

`kudos (num)`: Success of the fanfiction story (dependent variable)

`ARI`: Automated Readability Index

`FG`: Flesch Grade

`FE`: Flesch Ease

`MSTTR`: Mean Segmental Type-Token Ratio

`words`: Number of words in the fanfiction story

`comm`: Number of comments on the fanfiction story


## Objective

Our aim here is to determine which, if any, of the literary quality metrics are good predictors of fanfiction success. 


## Analysis steps

The following are performed:

1. Simple Linear Regression for all the independent variables (literary quality metrics) with kudos as the dependent variable
   
2. Plot of data with scatterplots to identify which of the variables might have a high correlation with success (kudos)
   
3. Linear regression model and plot of the regression line for every variable
   
4. Verification of the performance of every model using the R-squared score
   
5. Verification of residuals to identify if the linear regression assumptions are met
    
6. Shapiro-Wilk tests on the residuals to see if they are normal




## Creator
This dataset was created and curated by Theodora-Stavroula Korma on behalf of the course Analysing Data, for the MA Digital Humanities.

**Contact Information:** email: t.s.korma@student.rug.nl

## Usage
This dataset is provided for educational purposes, intended to support the final individual assignment for the course Analyzing Data, of 2a semester of MA Digital Humanities.
