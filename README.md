# Car Price Prediction using Linear Regression

This project demonstrates how to build a simple car price prediction model using **pandas** and **scikit-learn**.  
The dataset used (`audi.csv`) contains various features of Audi cars, including year, body type, mileage, engine size, power, gearbox type, fuel type, ownership details, and price.

## Dataset  
The dataset is sourced from Kaggle:  
[Audi A1 Listings - Kaggle](https://www.kaggle.com/datasets/jacklacey/audi-a1-listings)

## Project Overview
- Load and clean the dataset (`audi.csv`).
- Preprocess the data:  
  - Drop unnecessary columns.  
  - Rename columns for clarity.  
  - Convert engine size to numeric values.  
  - Encode categorical variables (`body type`, `gearbox`, `fuel type`) using one-hot encoding.
- Build a **Linear Regression** model to predict car prices.
- Evaluate model performance with train-test split and score the model.

## Requirements
- Python 3.x
- pandas
- scikit-learn

Install dependencies:
```bash
pip install pandas scikit-learn
