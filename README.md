# Project 2 - Ames Iowa: Alternative to the Boston Housing Data Set
#### By: Najiha Boosra: Github
## Problem Statement
For creating a regression model based on the Ames Housing Dataset. This model will predict the price of a house at sale.In this project, in particular, we will likely find that EDA, data cleaning,exploratory visualizations and finding RMSE, r^2 as metric will constantly feed back into each other. If the purpose in building the model is simply to allow a typical buyer or real estate agent to sit down and estimate the selling price of a house, such transformations may be unnecessary or inappropriate for the task at hand. We strongly make this point in the situation where data are being analyzed for research purposes that will be shared with a larger audience and the primary and secondary stakeholders.

## Executive Summary
After Loading necessary Libraries we check our data for cleaning like finding null values, replacing properly them and dropping unnecessary columns. In EDA & feature engineering process we put our data to create graphs to compare selected items, also to know about outliers.After that in modeling part we use linear Regression model, Lasso, Ridge and find out train-test-split, cross val score , RMSE, R^2 od the data.Then interpret and evaluate our models to select best one for data.And then we made a conclusion.
## Table of Contents
- **[Loading Libraries](#Data-import-read)**  

- **[Data Cleaning](#Data-Cleaning)**    

- **[EDA](#EDA-Exploratory-Data-Analysis)**  

- **[Modeling](#Modeling-Train-Test_Split-Baseline-Model)**  

- **[Model Prep:Scaling](#Linear-Regression-Ridge-Lasso)**  

- **[Model Selection & Evaluation](#Model-selection-Model-Evaluation)**      

- **[Conclusions and Recommendations](#Conclusions-and-Recommendations)**  

- **[References](#Reference)**   

- **[Kaggle Submission](#kaggle-submission)**

## Conclusion & Recommendations

Our analysis began with a relatively clean dataset of over 2,000 home sales in Ames, IA between 2007 and 2010. We applied a linear regression model which highlighted the properties above-ground square footage as the most heavily-weighted feature in predicting sale price. Basement square footage, the build year, an overall quality rating of “excellent,” and square footage of finished basement rounded out the most influential features. The model currently has an r2 score of .0.8665764 and an RMSE of 28784.8242.

## References
Review the [data description](http://jse.amstat.org/v19n3/decock/DataDocumentation.txt)
