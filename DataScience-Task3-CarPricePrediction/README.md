# Task 3 - Car Price Prediction with Machine Learning

## Project Overview
This project focuses on predicting the selling price of used cars using machine learning techniques. The dataset contains information such as car name, manufacturing year, kilometres driven, fuel type, seller type, transmission and ownership details.

## Objectives
- Perform data cleaning and preprocessing.
- Explore the dataset using Exploratory Data Analysis (EDA).
- Identify important factors affecting car prices.
- Build and evaluate machine learning regression models.
- Compare model performance.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Project Workflow
1. Data loading and inspection
2. Data cleaning and duplicate removal
3. Feature engineering (car age and brand extraction)
4. Exploratory Data Analysis and visualization
5. Categorical feature encoding
6. Model training and evaluation
7. Feature importance analysis

## Machine Learning Models

Two regression models were trained:

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 180194.99 | 385606.09 | 0.5384 |
| Random Forest Regressor | 158587.07 | 365133.53 | 0.5861 |

Random Forest Regressor performed better than Linear Regression across all three evaluation metrics.

## Conclusion
This project provided practical experience in data preprocessing, visualization and machine learning model development. The Random Forest model achieved the best performance, with an R² score of 0.5861. The analysis highlighted transmission type, car age and kilometres driven as important features in predicting used car prices.

## Internship
**Oasis Infobyte Data Science Internship - Task 3**
