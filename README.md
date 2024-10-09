# House Sales in King County

This project provides an analysis of house sales in King County, exploring various factors that influence house prices. The analysis uses Python libraries such as Pandas, Matplotlib, and Seaborn for data manipulation and visualization.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Description](#data-description)
- [Requirements](#requirements)
- [Results](#results)

## Project Overview
The objective of this project is to analyze and visualize house sales data from King County to identify key factors affecting house prices, such as location, size, number of bedrooms, and other relevant attributes.

## Data Description
The dataset used in this project includes information on house sales in King County, covering features like:
- House prices
- Number of bedrooms and bathrooms
- Square footage
- Location (latitude and longitude)
- Year built and renovation status

## Requirements
Ensure you have the following libraries installed:
- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Results
The analysis includes:
## Results

### Key Results
- **Model Comparisons**:
  - **Model C (Quadratic)** has an \( R^2 \) value of approximately **0.7948** and a Mean Squared Error (MSE) of **0.0587**.
  - Comparisons between different models showed that Model C performed better in terms of higher \( R^2 \) and lower MSE values.

- **Other Models**:
  - **Lasso Regression (Model D)**: \( R^2 \) of **0.7882** with MSE of **0.0594**.
  - **Ridge Regression (Model E)**: \( R^2 \) of **0.7883** with MSE of **0.0568**.

### Conclusions
- The quadratic model (Model C) outperformed other models like lasso and ridge regression.
- Despite addressing issues like heteroscedasticity and residual distribution, the best model remains Model C, indicating that the real-world data may inherently contain complexities that no single perfect model can fully capture.
