## House Price Prediction Model using Linear Regression

### Overview

This repository contains a **Linear Regression** model developed to predict **house sale prices** based on various house-related features. The dataset includes multiple attributes about the houses sold, and the target variable is the **Sale Price**.

### Dataset Features

The dataset contains the following features:

- **ID**: Unique identifier for each house.
- **Date House was Sold**: The date when the house was sold.
- **No of Bedrooms**: Number of bedrooms in the house.
- **No of Bathrooms**: Number of bathrooms in the house.
- **Flat Area (in Sqft)**: The total area of the house (excluding the lot area).
- **Lot Area (in Sqft)**: The area of the plot on which the house is built.
- **No of Floors**: Number of floors in the house.
- **Waterfront View**: Whether the house has a view of the waterfront (1 if yes, 0 if no).
- **No of Times Visited**: The number of times the house was visited before being sold.
- **Condition of the House**: Condition of the house at the time of sale (categorical).
- **Overall Grade**: A grade given based on the overall construction quality and design of the house.
- **Area of the House from Basement (in Sqft)**: The area of the house including the basement space.
- **Basement Area (in Sqft)**: The specific area of the basement.
- **Age of House (in Years)**: The age of the house in years when it was sold.
- **Renovated Year**: The year when the house was last renovated (if applicable).
- **Zipcode**: The postal code where the house is located.
- **Latitude**: Geographic coordinate for the house's latitude.
- **Longitude**: Geographic coordinate for the house's longitude.
- **Living Area after Renovation (in Sqft)**: The living area after any renovation work.
- **Lot Area after Renovation (in Sqft)**: The plot area after any renovation work.

### Target Variable

- **Sale Price**: The price at which the house was sold (dependent variable).

### Model

The model used is **Linear Regression**, which aims to predict the **Sale Price** based on the features listed above. The model fits a linear equation to the dataset, and the performance of the model is measured using the **R² (R-squared)** score, which indicates how well the independent variables explain the variability of the target variable.

### Model Performance

- The **R² score** for this model is **0.8119**, meaning that the model explains 81.19% of the variance in the house sale prices. This indicates a strong model fit.

### Repository Structure

- **Data**: The dataset used for training and testing the model.
- **Model**: Code for building, training, and evaluating the linear regression model.
- **Notebooks**: Jupyter notebooks containing the exploratory data analysis (EDA), feature engineering, and model development process.
- **README**: This file providing an overview of the project.


