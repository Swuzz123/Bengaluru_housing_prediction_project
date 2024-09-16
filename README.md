# Bengaluru House Prices Prediction

## Description
This project aims to predict house prices in Bengaluru based on factors such as location, size, number of bedrooms, and other relevant features. We applied machine learning models to understand more deeply the relationship between these factors and house prices.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Steps Implemented](#steps-implemented)
- [Technologies Used](#technologies-used)
- [Results](#results)
- [Conclusion](#conclusion)

## Project Overview
In this project, I focus on building a model to predict the price of houses in Bengaluru using historical data. The dataset was cleaned and preprocessed to remove inconsistencies and outliers before applying machine learning models like Linear Regression, Decision Trees, and KNeighborsRegressor.

## Dataset
The dataset contains information about various features of houses in Bengaluru, such as:
- Area (size in square feet)
- Number of bedrooms
- Location
- Price (target variable)

The dataset was sourced from Kaggle.

## Steps Implemented
1. *Data Cleaning*: Removed duplicates and handled missing values.
2. *Feature Engineering*: Created new features and transformed existing ones.
3. *Removing Outlier*: Used mean and standard deviation to evaluate and extract those outliers
4. *Model Selection*: Applied three models - Linear Regression, Decision Trees, and KNeighborsRegressor.
5. *Evaluation*: Compared the models using R² score and identified the best-performing model.
6. *Export Tested Model*: Exported this model to a pickle file and export location, column information to a file that will be usefull later on my prediction application

## Technologies Used
- *Programming Language*: Python
- *Libraries*: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## Results
Among the models tested, *Linear Regression* provided the best results with an R² score of *0.83*. This model was more effective at predicting house prices compared to Decision Trees and KNeighborsRegressor.

## Conclusion
Throught making this project, my result showed that Linear Regression model demonstrated the best performance in predicting house prices in Bengaluru. The model captured the main relationships between the features and the target variable effectively. This analysis can help both buyers and sellers in making more informed decisions in the real estate market. After complete the project, I learned a lot of ways, suitable analystical thinking to clean and feature engineering the datasets. Moreover, the removing outlier is the most difficult part, I saw the difference especially based on the drawing as well as the data after cleaning to remove outliers because I know that outliers will reduce the model's prediction a lot and affect buyers and sellers.
