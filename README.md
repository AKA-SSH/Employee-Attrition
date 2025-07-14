## Employee Attrition Prediction using Random Forest
This project focuses on predicting employee attrition using a Random Forest classification model. By leveraging various employee-related features, the model aims to identify employees who are at a higher risk of leaving the company, enabling proactive HR interventions.

## Project Overview
Employee attrition is a critical concern for organizations, leading to increased recruitment costs, loss of institutional knowledge, and decreased productivity. This project develops a machine learning model to predict attrition, providing insights into key factors influencing an employee's decision to leave.

## Features
- Data Preprocessing: Handling of categorical variables, missing values, and feature scaling.

- Exploratory Data Analysis (EDA): Insights into the dataset to understand relationships between features and attrition.

- Model Training: Implementation of a Random Forest Classifier.

- Model Evaluation: Assessment of model performance using key metrics like Precision and ROC AUC.

## Model Details
The core of this project is a Random Forest Classifier. Random Forest is an ensemble learning method that operates by constructing a multitude of decision trees during training and outputting the class that is the mode of the classes (classification) or mean prediction (regression) of the individual trees.

### Why Random Forest?
- High Accuracy: Generally performs well on many datasets, including those with non-linear relationships.

- Robustness to Overfitting: By averaging multiple decision trees, it reduces the risk of overfitting.

- Feature Importance: Provides a way to rank the importance of input features, offering insights into which factors most influence attrition.

## Results
The Random Forest model achieved strong performance metrics:

- Precision: 94.0%

- ROC AUC Score: 93.8%

These results indicate that the model is highly effective in identifying employees prone to attrition while maintaining a good balance between true positive rate and false positive rate.
