# Rossmann-Retail-Stores-Sales-Prediction

## Project Summary :-

## Company's Introduction
![download](https://user-images.githubusercontent.com/122456255/230047191-40e65c88-80dc-4e2e-a509-d4f354756c9e.jpg)


Dirk Rossmann GmbH, commonly referred to as Rossmann, is one of the largest drug store chains in Europe with around 56,200 employees and more than 4000 stores.

The company was founded in 1972 by Dirk Rossmann with its headquarters in Burgwedel near Hanover in Germany. The Rossmann family owns 60% of the company. The Hong Kong-based A.S. Watson Group owns 40%, which was taken over from the Dutch Kruidvat in 2004.

The company logo consists of a red name and the symbol of a centaur integrated in the letter O: a mythical creature made of horse and man from Greek mythology, which symbolically stands for "Rossmann" (In English: "Horse man").

## Problem Overview:

## Problem Statement:

Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied.
You are provided with historical sales data for 1,115 Rossmann stores. The task is to forecast the "Sales" column for the test set. Note that some stores in the dataset were temporarily closed for refurbishment.


Rossman Sales Prediction data is a data set containing historical sales data for a retail chain. The data includes store information, such as competitor details, store type, holidays and sales transaction.
Using the data given we had to build a model for forecasting the sales in future.
To build a machine learning model, we first perform EDA with various plots for better visualization.
And then we split it into a training set and a test set and applied various machine learning algorithms using the training data to train the model. Finally, we evaluated the model's performance on the test data to see how well it predicted sales.

## Analysis Performed:
![download](https://user-images.githubusercontent.com/122456255/230047363-983e5e91-97a8-4de5-a66f-e778bf98d2eb.png)


Steps involved in building a ML Model:

Step 1: Data gathering and Understanding

Step 2: Data preparation

Step 3: Data Cleaning

Step 4: Exploratory data analysis

Step 5: Feature engineering and selection

Step 6: ML Model assumption and checks

Step 7: Data preparation for modelling

Step 8: Model Building

Step 9: Model Validation & Evaluation

Step 10: Predictions & Saving model using pickel library.

## Libraries used in EDA & Machine Learning:

1. Pandas
2. Numpy
3. Matplotib
4. Seaborn
5. Plotly
6. Sklearn
7. Scipy

## Graphs used for representation:

1. Bar plot
2. Pie plot
3. Box Plot
4. Grouped bar plot
5. Donut plot
6. Heatmap
7. Pair plot

## ML Models used for training & testing:

1. Linear Regression
2. Lasso Regression
3. Ridge Regression
4. Decision Tree Regressor
5. Extra Tree Regressor
6. XG Boost Regressor
7. Light GBM Regressor

## Insights from EDA impacting business:

The most selling and crowded store type is A.
More stores are opened during School holidays than State holidays.
Mondays have most sales since most of the Sundays are closed.
Promo 1 has given positive yields where as Promo 2 is a disaster.
Store type b has higher sales and customers per store than other store types.
Assortment b is available only at store type b and it has more sales and customers than any other assortment.
Suggestions provided to increase the Sales:

There are very few B type stores, few more can be opened as average sales are quite high as compared to other types.
Assortment B is only available with store type B which can be extended to other types as well to cater the demands of customers.
Promo 2 should be discontinued and Promo 1 can be extended futher as it shows better results.
Very few stores are opened during State Holidays, so it suggested to open a subsequent amount of stores to serve in emergency purposes.
ML Model selected for deployment: Light GBM

Light GBM is a fast, distributed, high-performance gradient boosting framework that uses a tree-based learning algorithm. It also supports GPU learning and is thus widely used for data science application development.

## Advantages:

Faster training speed and higher efficiency: Light GBM uses a histogram-based algorithm i.e it buckets continuous feature values into discrete bins which fasten the training procedure.

Lower memory usage: Replaces continuous values to discrete bins which results in lower memory usage.

**Better accuracy** : It produces much more complex trees by following leaf wise split approach rather than a level-wise approach which is the main factor in achieving higher accuracy.

**Good Compatibility with Large Datasets:** It is capable of performing equally well with large datasets with a significantly less training time as compared to XGBoost.

## Limitations:

Complexity: Light GBM split the tree leaf-wise which can lead to overfitting as it produces much complex trees.
Overfitting: Light GBM is sensitive to overfitting and thus can easily overfit small dataset.

## Suggestion:
When we are dealing with huge dataset & time is a constraint use Light GBM Model else when dataset is small than XGBoost can provide better results.
