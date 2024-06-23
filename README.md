# Car Price Prediction Project

## Project Overview

The used car sales service "Not Damaged, Not Painted" is developing an application to attract new customers by allowing them to determine the market value of their cars. 
Your task is to build a model that can predict the market price of a car based on its technical specifications, equipment, and prices of other cars.

## Project Objectives

- Build a model that accurately predicts the market price of cars.
- Optimize the model for training time and prediction time.

## Data Description

The data is stored in the file `/datasets/autos.csv`.

### Features
- `DateCrawled`: Date when the listing was crawled from the database.
- `VehicleType`: Type of vehicle body.
- `RegistrationYear`: Year of vehicle registration.
- `Gearbox`: Type of gearbox (manual/automatic).
- `Power`: Power of the car in horsepower (hp).
- `Model`: Car model.
- `Kilometer`: Mileage of the car in kilometers.
- `RegistrationMonth`: Month of vehicle registration.
- `FuelType`: Type of fuel the car uses.
- `Brand`: Car brand.
- `Repaired`: Whether the car has been repaired or not.
- `DateCreated`: Date when the listing was created.
- `NumberOfPictures`: Number of pictures of the car.
- `PostalCode`: Postal code of the listing owner (user).
- `LastSeen`: Date of the last user activity.

### Target Variable
- `Price`: Price of the car in euros.

## Criteria Important to the Customer

- Prediction Quality: The model should accurately predict car prices to meet customer expectations.
- Training Time: Efficient training to handle potentially large datasets.
- Prediction Time: Fast prediction times to provide quick responses to users.

## Steps to Complete the Project

1. **Data Loading and Exploration**:
   - Load the dataset and perform initial exploratory data analysis.
   - Handle missing values and outliers appropriately.
   - Convert categorical variables into a suitable format for modeling.

2. **Data Preprocessing**:
   - Perform feature engineering if necessary, such as creating new features or transforming existing ones.
   - Split the data into training and testing sets.

3. **Model Selection and Training**:
   - Choose appropriate machine learning models for regression tasks.
   - Train the models on the training dataset and optimize hyperparameters.

4. **Model Evaluation**:
   - Evaluate the models using metrics such as RMSE (Root Mean Squared Error) to assess prediction accuracy.
   - Compare different models based on their performance and select the best one.

5. **Deployment**:
   - Deploy the chosen model into a production environment where it can predict car prices based on user input efficiently.
