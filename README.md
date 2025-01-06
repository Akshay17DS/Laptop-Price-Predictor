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

## 1. Data Cleaning

Dropped the unnecssary columns like, Unnamed: 0

Cleaned and formatted columns like Ram, Weight.

## 2. EDA

## Univariate Analysis

![download](https://github.com/user-attachments/assets/8d0eb0e1-c428-4494-bdde-90053ebc5478)

![download](https://github.com/user-attachments/assets/a1b253ac-c249-48fd-88f5-ede53b095d71)

![download](https://github.com/user-attachments/assets/40370b48-13bd-4c15-a0a2-9fa79f0eac9e)

![download](https://github.com/user-attachments/assets/ccb66db7-07bd-4092-b761-9b419664f943)

![download](https://github.com/user-attachments/assets/26262aa8-86c7-47cb-8b0d-166a6405b157)

Created new column called ppi from Screen Resolution

Created new column from Cpu, namely Cpu name, Cpu brand

Memory column coverted into, HDD , SSD , Hybrid , Flash Storage

Gpu converted Intel, Nvidia, AMD, ARM

OpSys converted to Windows, Mac, Others/No OS/Linux

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
