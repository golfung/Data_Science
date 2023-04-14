# Classification : Mobile Price

This project about use **Machine Learning** to estimate price of mobiles with **Python** programming.

The original project https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification

## About Dataset

#### Context
Bob has started his own mobile company. He wants to give tough fight to big companies like Apple,Samsung etc.

He does not know how to estimate price of mobiles his company creates. In this competitive mobile phone market you cannot simply assume things. To solve this problem he collects sales data of mobile phones of various companies.

Bob wants to find out some relation between features of a mobile phone(eg:- RAM,Internal Memory etc) and its selling price. But he is not so good at Machine Learning. So he needs your help to solve this problem.

In this problem you do not have to predict actual price but a price range indicating how high the price is

## Define the problem

The business problem is to develop a pricing classification model that can estimate the price range of the mobile phones produced by Bob's mobile company based on the phone's features such as RAM, internal memory, etc.

## Gather data
- Import library, Load data set

## Explore and clean the data
- Check NA data, Check correlation, What variable correlate to target 
- From the correlation values, I found that `ram` had a very strong positive correlation (0.92) to `price_range`.

## Split data
- X = feature variables, y = a target variable
- split data 70% for train data set

## Model fitting
- DecisionTree Classifier
- K-Nearest Neighbors (KNN) Classifier

## Model evaluation
- DecisionTree Accuracy score: 0.82
- K-Nearest Neighbors Accuracy score: 0.92

## Model Selection

![__results___24_0](https://user-images.githubusercontent.com/77894515/232127337-e7fce670-661b-4778-8311-7b10631786a8.png)

I have decided to use the K-Nearest Neighbors model to classify the mobile price range.

## Apply to real data

![__results___31_0](https://user-images.githubusercontent.com/77894515/232127522-26607197-825c-45e2-8033-42cebc016203.png)

## Please see on full paper : [Click Here](https://github.com/golfung/Data_Science/blob/main/Mobile_Price_Classification/classification-mobile-price.ipynb)

