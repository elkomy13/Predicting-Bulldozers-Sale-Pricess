Predicting Bulldozer Sale Prices - Machine Learning Project 🚜




Overview
you'll find the code and documentation for my latest machine learning project, focused on predicting the sale prices of bulldozers. The project's primary goal was to develop a robust model capable of forecasting bulldozer prices based on their unique characteristics and historical sales data.

Project Structure
Problem Definition:

The central challenge was to predict the future sale price of a bulldozer by analyzing its distinctive features and drawing insights from previous sales data.
Data:

The dataset is sourced from the Kaggle Bluebook for Bulldozers competition and includes three main components:
Train.csv: Training set with data up to the end of 2011.
Valid.csv: Validation set featuring data from January 1, 2012, to April 30, 2012.
Test.csv: The test set, revealed in the competition's final week, includes data from May 1, 2012, to November 2012.
Evaluation:

The project's success is gauged using the RMSLE (root mean squared log error) metric, aligning with regression analysis standards. The objective is to minimize the RMSLE, as per the competition's evaluation criteria.
Learn more about the evaluation criteria

Features and Techniques:

Working with a substantial dataset of 412,698 entries, the project delves into time series data. A key aspect involves parsing the sale date into distinct components: sale year, sale month, sale day, sale day of the week, and sale day of the month. Feature engineering techniques were applied to enhance the model's predictive capabilities.
Explore the data dictionary for detailed features from here : https://www.kaggle.com/c/bluebook-for-bulldozers/overview/evaluation

![WhatsApp Image 2024-01-13 at 4 02 22 PM (1)](https://github.com/elkomy13/Predicting-Bulldozers-Sale-Pricess/assets/97259226/51b65c70-a652-4c3c-8d65-7dd7166d0c83)
