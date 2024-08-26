# Video Game Sales Prediction

## Overview
This project aims to predict video game sales based on various features like Rank, Platform, Year, Genre, Publisher, and regional sales. The goal is to build a machine learning model that can accurately forecast sales figures, helping stakeholders make informed decisions.

## Dataset
The dataset used in this project includes the following features:

- **Rank**: The ranking of the video game.
- **Platform**: The platform on which the game is released.
- **Year**: The release year of the game.
- **Genre**: The genre of the video game.
- **Publisher**: The publisher of the video game.
- **Regional Sales**: Sales figures for different regions.

## Feature Engineering
To improve the performance of the machine learning model, the following feature engineering steps were performed:

- **Handling Missing Values**: Strategies were implemented to address missing values in the dataset.
- **Encoding Categorical Variables**: Categorical features were converted into numerical format using techniques like label encoding.

## Modeling
The project explores a machine learning algorithm to predict video game sales:

- **Linear Regression**: A simple and interpretable model used to establish a baseline for prediction.

## Evaluation
Model performance is evaluated using the following metrics:

- **R-squared**: Measures the proportion of the variance in the dependent variable that is predictable from the independent variables.
- **Mean Absolute Error (MAE)**: Represents the average absolute difference between predicted and actual values.
