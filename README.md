# Predicting_Car_Price
In this repository, there is an entire end-to-end machine learning project designed to predict prices of automobiles. This project utilizes a common approach adopted within data science, which involves importing, analyzing, cleaning, processing, building models, and extracting insights from the data. The project utilizes a public dataset on automobiles and comprises both regression and classification problems.
## Overview
The first objective of this project is to build a regression model that can predict the price of a vehicle through features like engine size, curb weight, horsepower, and fuel consumption rate. The second objective of the study is to create price category groups of vehicles using logistic regression analysis.
### Key Features:
- **EDA :** Distribution analysis, correlation heatmap, and statistical summary.
- **Data Preprocessing :** Dealing with missing data through mean/mode imputation.
- **Feature Engineering :** Binning horsepower, normalize the length, and convert MPG to L/100km.
- **Regression Modeling :** Perform linear regression analysis, random forest model evaluation on various split ratios.
- **Classification Modeling :** Logistic regression analysis for price classification.
- **Model Evaluation :** Measure using r-squared, MAE, MSE, RMSE, accuracy and confusion matrix.
- **Business Insights :** Identification of key price-influencing features  and provide relevant advice.

## Dataset
The database employed for this analysis is the Automobile Data Set available on the UCI Machine Learning Repository accessed through IBM Developer Skills Network. The data set comprises 205 observations and 26 variables which include the following characteristics about cars:
- Technical Features: engine-size, horsepower, curb-weight, wheel-base, etc.
- Efficiency Features: city-mpg, highway-mpg
- Categorical Features: make, fuel-type, body-style, drive-wheels, etc.
- Target Feature: price (continuous)

## Tasks Performed
### Loading Dataset and EDA
- The dataset is loaded from a URL. Columns are named appropriately.
- Conduct preliminary data analysis including shape, data types, missing values, and unique value counts in categorical variables.
- Plot distribution of price and horse power. Plot boxplot of price according to body style.
- Generate correlation matrix plot of numerical variables.

### Data Cleaning and Feature Engineering
- Imputation of missing values in numeric columns using their mean and in categorical columns using their modes.
- Change data type of “price” and “horsepower” to numeric.
- Create new features: “city-L/100km”, “horsepower-binned” [Low / Medium / High] and “length normalized”.

### Regression Models
- Train Linear Regression and Random Forest Regressor on selected features.
- Test model performance using 80-20 and 70-30 split train-test datasets.
- Model Performance Measures: R², MAE, MSE, RMSE.
- Important Note: Random Forest performs better than Linear Regression.

### Classification Model
- Classify prices into three classes, Low, Medium, and High using quantiles binning.
- Train a Logistic Regression algorithm with the normalized input features.
- Evaluation Measures Accuracy, Classification Report and Confusion Matrix.
- Classification Accuracy: ~80%.

### Actual v. Predicted Plot 
- Scatter plot showing actual and predicted prices for the best Random Forest regression (80/20 train/test ratio).
- Plot feature importance for Random Forest to determine the top contributing predictors.
- Top Features: engine size (46.6%), curb weight (36.5%), highway mpg (6.9%), etc.

### Business Insights
State actionable insights for the manufacturer and consumers:
- Increased engine displacement, higher curb weight, and larger horsepower will result in increased pricing.
- Fuel economy also comes into play because lower mpg usually indicates that the car will be larger and have greater power.
- The manufacturer needs to consider engine efficiency, size of the car, body type, and fuel efficiency when placing the car in various pricing tiers.
- Consumers will be able to determine if the price of a car is reasonable given the car's technical aspects.





