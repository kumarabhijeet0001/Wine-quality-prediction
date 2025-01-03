# Wine Quality Prediction

## Overview
This project focuses on predicting the quality of wine based on its physicochemical attributes using a machine learning model. The primary goal is to build a linear regression model to estimate wine quality and evaluate its performance.

---

## Dataset
The dataset contains physicochemical properties of wines such as:
- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol

### Target Variable
- **Quality**: A score (typically between 0–10) representing the quality of the wine.

### Source
The dataset can be downloaded from platforms like [Kaggle](https://www.kaggle.com/).

---

## Project Steps

### 1. Data Preprocessing
- Load the dataset.
- Handle missing or inconsistent data.
- Normalize and scale the features for better model performance.
- Split the data into training and testing sets.

### 2. Exploratory Data Analysis (EDA)
- Perform descriptive statistics to understand feature distributions.
- Visualize relationships using scatter plots and box plots.
- Generate a correlation heatmap to identify strongly correlated features.

### 3. Model Building
- Use linear regression to model the relationship between input features and wine quality.
- Evaluate the model using metrics like Mean Squared Error (MSE) and R² Score.

### 4. Model Evaluation
- Assess model accuracy on the testing data.
- Plot actual vs. predicted values to visualize performance.
