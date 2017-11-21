# Soccer_Match_Result_Prediction
This project is to predict whether in-home soccer team will win a match againt away-home team or not. Algorithms such as logistic regression, SVM and random forest are used to analyze in R. 


The dependent variable is a binary variable, describing whether in-home team wins the game or not. The draw outcome and lose outcome are classified into one category. We only care about the win outcome in this project.

The independent variables are soccer team attributes, such as speed, defence, pass and dribble.

----------------------------------------------------------------------------------------------------------------------------
The original data set can be downloaded here:
https://www.kaggle.com/hugomathien/soccer/data


It is a SQLite database consisting seven tables. It needs to be transformed into .csv file before using R to analyze. Besides, since the data about match, team attributes and player attributes are displayed in different tables, you need to merge these tables if you want to analyze the relationship between match outcome and team/player attributes.


____________________________________________________________________________________________________________________________
To run the codes, please follow the number frequency. Because some changes are made to variables in each part, it will cause error if you run later part without running all previous parts first.


Required packages to successfully execute the script:

library(readr)
library(leaps)
library(glmnet)
library(neuralnet)
library(randomForest)
library(gbm)
library(class)
library(ISLR)
library(tree)
library(arules)
library(arulesViz)
library(e1071)


Recommended System Environment:
R version 3.3.2 (2016-10-31), RStudio Version 1.0.136, MacOS Sierra Version 10.12.1


