# Predicting_Car_Price
In this repository, there is an entire end-to-end machine learning project designed to predict prices of automobiles. This project utilizes a common approach adopted within data science, which involves importing, analyzing, cleaning, processing, building models, and extracting insights from the data. The project utilizes a public dataset on automobiles and comprises both regression and classification problems.
## Overview
The first objective of this project is to build a regression model that can predict the price of a vehicle through features like engine size, curb weight, horsepower, and fuel consumption rate. The second objective of the study is to create price category groups of vehicles using logistic regression analysis.
### Key Features:
EDA: Distribution analysis, correlation heatmap, and statistical summary.

Data Preprocessing: Dealing with missing data through mean/mode imputation.

Feature Engineering: Binning horsepower, normalize the length, and convert MPG to L/100km.

Regression Modeling: Perform linear regression analysis, random forest model evaluation on various split ratios.

Classification Modeling: Logistic regression analysis for price classification.

Model Evaluation: Measure using r-squared, MAE, MSE, RMSE, accuracy and confusion matrix.

Business Insights:  Identification of key price-influencing features  and provide relevant advice.

## Dataset
The database employed for this analysis is the Automobile Data Set available on the UCI Machine Learning Repository accessed through IBM Developer Skills Network. The data set comprises 205 observations and 26 variables which include the following characteristics about cars:

Technical Features: engine-size, horsepower, curb-weight, wheel-base, etc.

Efficiency Features: city-mpg, highway-mpg

Categorical Features: make, fuel-type, body-style, drive-wheels, etc.

Target Feature: price (continuous)

## Tasks Performed
### Loading Dataset and EDA
The dataset is loaded from a URL. Columns are named appropriately.

Conduct preliminary data analysis including shape, data types, missing values, and unique value counts in categorical variables.

Plot distribution of price and horse power. Plot boxplot of price according to body style.

Generate correlation matrix plot of numerical variables.

