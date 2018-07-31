# Price_Suggestion_E-Commerce


In this project I am dealing with the data provided by Mercarri e-commerce company, which is mainly operated in japan. The problem here is I have to predict the prices of the products which have been provided by Mercarri.  This project follows CRISP-DM architectecture and also satisfies PEP-8 Convention.

## Libraries used

* scipy and numpy: SciPy and Numpy are free and open-source Python library used for scientific computing and technical computing.

* pandas: Pandas is a software library written for the Python programming language for data manipulation and analysis.

* sklearn and lightgbm: Machine learning library for the Python programming language. It features for classification and regression.

* Wordcloud: Used for plotting words with thier frequency taken into account

* matplotlib: Matplotlib is a plotting library for the Python programming language and its numerical mathematics extension NumPy.


## Motivation

Generally, Right choice of pricing a product can never be static, it has to be varying based on the market demand for that,I build a model that automatically suggests the right product prices. There are various factors which can effect the price of product. Let's dive in detail this in data understanding section.

## Data

You can find the data used in this project in [Data](https://www.kaggle.com/saitosean/mercari)

Let us understand the each attribute present in the data more carefully. We have total of 8 attributes and 6 million records in train data.


* train_id  — the id of the listing


* name   —  the title of the listing


* item_condition_id   —  the condition of the items provided by the sellers


* category_name  —  category of the listing


* brand_name  —  the name of the brand


* price  —  the price that the item was sold for. This is target variable that we will predict


* shipping  —  1 if shipping fee is paid by seller and 0 by buyer


* item_description  —  the full description of the item


## Files in repository

This repository contains two files notebook which covers the python code for solving predict the prices of the products which have been provided by Mercarri. It also contains **HTML** version of it.

## Summary

We have choosen 3 questions to answer bussiness needs by doing modelling with data what we are given with and predict the price of product given the attributes of product in complete automated manner


## Acknowlwdgements

* https://www.kaggle.com/jagangupta/stop-the-s-toxic-comments-eda
* https://pythonspot.com
* https://pandas.pydata.org/
