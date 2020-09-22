# HyperMarkets-Prediction
Prediction and Analysis of products across different stores and locations.

## Introduction
Hypermarkets are basically chains of supermarkets where their stores are set up at various centers across many cities, with n number of products and huge costs which goes into the setup. The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Using this model, BigMart will try to understand the properties of products and stores which play a key role in increasing sales.

## Overview of Data
There are many variables which come into play when we try to analyze the sales of supermarkets. Here I will be predicting the Item Outlet Sales. 

- Item Identifier
- Item Weight
- Item Fat Content
- Item Visibility
- Item Type
- Item MRP
- Outlet Identifier
- Outlet Establishment Year
- Outlet Size
- Outlet Location Type
- Outlet Type
- Item Outlet Sales

## Data Pre-Processing

The dataset is loaded with 60% training data and 40% testing data, there were some missing vales and it is been filled. In the dataset we also have catogerical features which may cause error while modeling hence that has been converted to the numeri value so as to smoothen the analysis. This is done by Encoder.

## Exploratory Data Analysis

Once the data is cleaned before training we have to visualize the variables to have a better understanding, all the factors are visualized graphically with respect to the Item Outlet Sales.

## Model

To get the prediction data we are using RMSE. RMSE is a measure of how spread out these residuals are. In other words, it tells you how concentrated the data is around the line of best fit. We have used Regression modle to predict and the better improvement on RMSE was given by Random Forest Regressor.
