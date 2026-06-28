# Titanic Exploratory Data Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset using Python and Jupyter Notebook. The goal is to understand the dataset, clean missing values, visualize important patterns, and identify the factors that influenced passenger survival.

## Dataset

The dataset contains passenger information such as:
- Passenger ID
- Name
- Age
- Gender
- Passenger Class
- Fare
- Embarked Port
- Survival Status

## Data Cleaning

The following preprocessing steps were performed:
- Missing values in the **Age** column were replaced with the median.
- Missing values in the **Embarked** column were replaced with the mode.
- The **Cabin** column was removed because it contained too many missing values.

## Exploratory Data Analysis

The notebook includes:
- Survival Count
- Survival by Gender
- Survival by Passenger Class
- Age Distribution
- Fare Distribution
- Correlation Heatmap
- Age vs Fare Scatter Plot

## Findings

The analysis shows that female passengers and first-class passengers had significantly higher survival rates. Passenger class and gender had the strongest influence on survival, while age had a weaker impact.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook