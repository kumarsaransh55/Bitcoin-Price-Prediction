Bitcoin(Cryptocurrency) Price Prediction Using Machine Learning
This notebook looks into using various Python-based machine learning and data science libraries in an attempt to build a machine learning model capable of predicting the closing prices of bitcoin with its historical data.

We're going to take the following approach:

Problem defination
Data
Evaluation
Features
Modelling
Experimentation
1. Problem Defination
In a Statement,

Given historical data of bitcoin , can we predict the closing prices of our Bitcoin for Current Dataset as well as for near future.

2. Data
The Data came from the Kaggle Dataset Section:

https://www.kaggle.com/varpit94/bitcoin-data-updated-till-26jun2021

And we, updated the dataset with the latest values of the current market.

3. Evaluation
If we can reach 90% Accuracy at predicting the closing prices of bitcoin till then, we'll pursue the project.

4. Features
This is where you'll get different information about each of the features in your data. You can do this via doing your own research (such as looking at the links above) or by talking to a subject matter expert (someone who knows about the dataset).

Create data dictionary

Date- Date at which the data was recorded.
Open- Price from the first transaction of a trading day.
High- Maximum price in a trading day.
Low- Minimum price in a trading day.
Close - Price from the last transaction of a trading day.
Adj Close - Closing price adjusted to reflect the value after accounting for any corporate actions.
Volume - Number of unites traded in a day.
