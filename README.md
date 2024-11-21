# Health Prediction Model

This project aims to predict the health status of an organism based on biological sensor data, utilizing machine learning techniques. The project implements regression models to predict the health status using bio-marker measurements and evaluates the models' performance based on key metrics.

## Problem Statement

The goal of this project is to build a **regression model** that predicts the health of an organism based on two biological sensor measurements. The challenge is to predict the health status using measurements, where negative values represent levels lower than the average. The task involves training regression models and evaluating their performance.

Key features include:
- **Data Retrieval**: Load and prepare data from CSV files.
- **Data Cleaning**: Handle missing values, remove duplicates, and preprocess data types for modeling.
- **Regression Modeling**: Use regression models to predict the health status.
- **Model Evaluation**: Evaluate model performance using Mean Squared Error (MSE) and Mean Absolute Error (MAE).
- **Feature Visualization**: Visualize data distributions and correlations.

## Workflow

1. **Data Loading**: Load the training (`p1-train.csv`) and test (`p1-test.csv`) data from CSV files.
2. **Data Cleaning and Preprocessing**: Clean the dataset by handling missing values and performing necessary transformations.
3. **Feature Engineering**: Apply transformations to improve data quality and scale the features.
4. **Model Training**: Train multiple regression models, including Linear Regression and Support Vector Regression (SVR), to predict the target variable (health status).
5. **Model Evaluation**: Evaluate the models on the test dataset using performance metrics such as Mean Squared Error and Mean Absolute Error.
6. **Reporting**: Provide a detailed performance analysis of the models, including their strengths and weaknesses.

## Features

- **Data Understanding and Cleaning**:
  - Identifies types of variables, handles missing values, and removes any duplicates.
  - Standardizes the data types for compatibility with the machine learning models.

- **Data Preprocessing**:
  - Handles missing values by using statistical methods such as mean, median, or mode imputation.
  - Uses scaling techniques to standardize the features and optimize model performance.
  - Applies transformations to address any skewness in the data, particularly for continuous variables.

- **Exploratory Data Analysis (EDA)**:
  - Visualizes data distributions, correlations, and outliers to understand the dataset better.
  - Utilizes visualizations such as histograms and boxplots to detect outliers and skewness in the data.

- **Model Building and Evaluation**:
  - Trains both **Linear Regression** and **Support Vector Regression (SVR)** models.
  - Evaluates model performance using **Mean Squared Error (MSE)** and **Mean Absolute Error (MAE)** on the test set.

- **Results Reporting**:
  - Compares the performance of the different models and provides insight into their relative effectiveness.
  - Reports MSE and MAE for each model trained.

## Technologies Used

- **Python**: The main programming language used for data processing and model development.
- **Pandas/Numpy**: For data manipulation and analysis.
- **Scikit-learn**: For machine learning model development and evaluation.
- **Matplotlib/Seaborn**: For data visualization.

## Results  
The models' performance on the test set is summarized below:  

| Model                   | Mean Squared Error (MSE) | Mean Absolute Error (MAE) |  
|--------------------------|--------------------------|----------------------------|  
| **Linear Regression**    | *5.045760259110827*      | *1.7988557623211774*       |  
| **Support Vector Regression** | *5.41848217630018*      | *1.8567562894704273*       |  

## References

- **Python**: [https://docs.python.org/3/](https://docs.python.org/3/)
- **Scikit-learn Documentation**: [https://scikit-learn.org/stable/](https://scikit-learn.org/stable/)

