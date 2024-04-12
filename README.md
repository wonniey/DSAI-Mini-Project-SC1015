# DSAI-Mini-Project-SC1015

This is our Mini-Project for SC1015, Intro do Data Science and Artificial Intelligence, for Nanyang Technological Univerisity (NTU).
We used our dataset airbnb listings from https://www.kaggle.com/datasets/chadra/ab-nyc-2019.

## Content
1. Data Extraction and clean up
2. Data Visualization
3. Splitting Data Samples
4. Linear Regression
5. Ridge Regression
6. Random Forest Regressor
7. Model Analysis
8. Practical Application & Conclusion

## Problem Definition
1. Prediction of Prices using Variables of AirBnB Listings
2. Analysis of Actual Prices to deduce whether listings are overpriced or underpriced

## Models Used
1. Linear Regression
2. Ridge Regression
3. Random Forest Regressor

## Conclusion
1. Among the variables, room_type and location (longitude and latitude) affect the predicted pricing the most
2. Random Forest Regressor is the best model for prediction among the models used
3. When errors are not taken into account, more airbnb listings are underpriced than overpriced
4. When errors are taken into account, most airbnb listings are well priced and small number of listings are overpriced. However, none of the listings are underpriced!

## What did we learn from this project?
1. Dfferent methods to handle preliminary dataset by analysing the data and decide what needs to be done for our regressor model to make use of the data effectively
2. Different models that can be used to predict the prices of airbnb listings using predictors (Ridge Regression, Random Forest Regression)
3. Collaboration on GitHub site
4. Usage of LIME and SHAP to determine the importance of each predictor in predicting the response

## Referencees
Tuning the random forest in python: https://towardsdatascience.com/hyperparameter-tuning-the-random-forest-in-python-using-scikit-learn-28d2aa77dd74

