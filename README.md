# Laptop Price Predictor 💻📈

## Project Overview
This project predicts laptop prices based on specifications like brand, screen size, processor, RAM, and more. It showcases the end-to-end process of building a machine learning model, from data preprocessing to evaluation.

## Dataset

The dataset contains 1,303 rows with the following key columns:

Company: Brand of the laptop.

TypeName: Type/category of the laptop.

Inches: Screen size.

Cpu, Ram, Memory, Gpu: Specifications of the laptop.

Weight: Laptop's weight.

Price: Target variable (price in numerical format).

## Steps

## 1. Data Preprocessing

Cleaned and formatted columns like Cpu, Memory, and ScreenResolution to extract meaningful features.

Converted weight values into numerical format.

Encoded categorical variables like Company, TypeName, and OpSys using label encoding.

## 2. Feature Engineering

Extracted numerical values from Ram, Weight, and ScreenResolution.

Engineered new features like pixel density and storage type counts.

## 3. Exploratory Data Analysis (EDA)

Analyzed the distribution and trends in the dataset.

Identified features with high predictive power.

## 4. Model Building

Algorithms Used:

Linear Regression

Random Forest Regressor

XGBoost Regressor

## 5. Model Evaluation

Evaluated models using the following metrics:

Mean Absolute Error (MAE)

R² Score

## Installation
Clone the repo:
git clone https://github.com/yourusername/laptop-price-predictor.git

Install dependencies:
pip install -r requirements.txt

## Future Improvements
Add features like battery life and screen refresh rate.

Deploy as a web app using Flask or Streamlit.
