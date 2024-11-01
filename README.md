# Car Price Analysis
This repository contains a comprehensive analysis of a car price dataset. 
The analysis includes data cleaning, feature engineering, hypothesis testing, and regression analysis.

## Introduction
The car price dataset contains information about various cars, including their prices, features, and specifications. 
The goal of this analysis is to identify the factors that influence car prices and to develop a predictive model that can accurately forecast car prices.

## Data
The dataset used in this analysis is a CSV file containing 1000 rows and 10 columns. The columns include:
* `sellingprice`: the selling price of the car
* `odometer`: the odometer reading of the car
* `condition`: the condition of the car (new, used, etc.)
* `mmr`: the manufacturer's suggested retail price (MSRP) of the car
* `year`: the model year of the car
* `make`: the make of the car (e.g. Toyota, Ford, etc.)
* `model`: the model of the car (e.g. Camry, Mustang, etc.)
* `trim`: the trim level of the car (e.g. base, sport, etc.)
* `category`: the category of the car (e.g. sedan, SUV, etc.)
* `price_mmr_ratio`: the ratio of the selling price to the MSRP

## Requirements
The following libraries are required to run the analysis:
* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `scikit-learn`

## Analysis
The analysis includes the following steps:
1. Data cleaning: removing missing values and outliers
2. Feature engineering: creating new features such as car age and price to MMR ratio
3. Hypothesis testing: comparing prices across different categories and brands
4. Regression analysis: developing a predictive model to forecast car prices

# Insights
Distribution of Selling Prices: The histogram and density plot show the distribution of selling prices, indicating whether the prices follow a normal distribution or if there is any skewness and kurtosis.
Correlations: The correlation heatmap highlights which features are strongly correlated with the selling price.
Outliers: Removing outliers ensures that the analysis is not skewed by extreme values.
Relationships: Scatter plots between selling price and other features (like odometer and condition) provide insights into how these features influence the selling price.
Feature Engineering: Creating new features like car age and price to MMR ratio can uncover additional insights.
Hypothesis Testing: T-tests and ANOVA help identify significant differences in prices across different categories or brands.
Regression Analysis: Linear regression models help understand the predictive power of selected features on the selling price.

## Conclusion
The car price analysis provides valuable insights into the factors that influence car prices. 
The analysis shows that car age, condition, and price to MMR ratio are significant predictors of car prices. 
The predictive model developed in this analysis can be used to forecast car prices with a high degree of accuracy.


