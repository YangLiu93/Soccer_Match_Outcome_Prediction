# Soccer_Match_Outcome_Prediction
This project is to predict whether in-home team will win a match or not, using logistic regression, SVM, random forest,etc. in R

The dependent variable is binary variable, describing whether in-home team wins the game or not. The draw outcome and lose outcome are classified into one category. We only care about the win outcome in this project.

The independent variables I use are soccer team attributes, such as speed, defence, pass and dribble.

The original data set can be downloaded here:
https://www.kaggle.com/hugomathien/soccer/data

It is a SQLite database consisting seven tables. It needs to be transformed into .csv file before using R to analyze. Besides, since the data about match, team attributes and player attributes are displayed in different tables, you need to merge these tables if you want to analyze the relationship between match outcome and team/player attributes.


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


