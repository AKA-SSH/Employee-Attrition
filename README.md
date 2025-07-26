## Employee Attrition Prediction using Logistic Regression

This project focuses on predicting employee attrition using a Logistic Regression classification model. By leveraging various employee-related features, the model aims to identify employees who are at a higher risk of leaving the company, enabling proactive HR interventions.

## Project Overview

Employee attrition is a critical concern for organizations, leading to increased recruitment costs, loss of institutional knowledge, and decreased productivity. This project develops a machine learning model to predict attrition, providing insights into key factors influencing an employee's decision to leave.

## Features

* **Data Preprocessing**: Handling of categorical variables, missing values, and feature scaling.
* **Exploratory Data Analysis (EDA)**: Insights into the dataset to understand relationships between features and attrition.
* **Model Training**: Implementation of a Logistic Regression Classifier.
* **Model Evaluation**: Assessment of model performance using key metrics like Precision and ROC AUC.

## Model Details

The core of this project is a **Logistic Regression** model. Logistic Regression is a statistical model that in its basic form uses a logistic function to model a binary dependent variable, although many more complex extensions exist. It is commonly used for predicting probabilities and classifying observations.

### Why Logistic Regression?

* **Interpretability**: The coefficients provide insights into the strength and direction of the relationship between predictors and the probability of attrition.
* **Efficiency**: It is computationally efficient and performs well on linearly separable data.
* **Baseline Model**: Often serves as a strong baseline for comparison with more complex models.

## Results

The **Logistic Regression** model achieved strong performance metrics:

* **Weighted Avg. Recall**: 77%
* **ROC AUC Score**: 82.04%

These results indicate that the model is highly effective in identifying employees prone to attrition while maintaining a good balance between true positive rate and false positive rate.
