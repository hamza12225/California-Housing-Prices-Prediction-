# California Housing Prices Prediction

A machine learning project that predicts California housing prices using linear regression.

## Dataset

The dataset is sourced from Kaggle: [California Housing Prices](https://www.kaggle.com/datasets/camnugent/california-housing-prices?resource=download)

## Project Overview

This project implements a linear regression model to predict housing prices in California based on various features such as location, house age, rooms, population, and ocean proximity.

## Data Processing Steps

1. **Data Exploration**: Analyzed the dataset structure and statistics
2. **Missing Value Handling**: Identified and removed missing values from the dataset
3. **Feature Encoding**: Decoded the `oceanProximity` categorical variable for model compatibility
4. **Data Splitting**: Split the data into training and testing sets
5. **Model Training**: Trained a linear regression model on the processed data

## Model Performance

The linear regression model achieved a good R² score, indicating strong predictive performance for California housing prices.

## Features

The model uses the following features to predict housing prices:
- Longitude and Latitude
- Housing median age
- Total rooms and bedrooms
- Population and households
- Median income
- Ocean proximity (encoded)

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib (for visualization)

## Usage

1. Download the dataset from the Kaggle link
2. Run the data preprocessing script to clean and prepare the data
3. Train the linear regression model
4. Evaluate model performance using R² score

## Results

The model successfully predicts California housing prices with good accuracy, as measured by the R² score.
