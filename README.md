# Customer Churn Analysis


This project is focused on analyzing customer churn for a telecommunications company. The dataset contains customer information such as state	area_code , 
account_length, voice_plan,	voice_messages,	intl_plan, intl_mins, intl_calls, intl_charge, day_mins, day_calls, day_charge, eve_mins, eve_calls,	eve_charge,	night_mins,
night_calls,	night_charge,	customer_calls,	churn- whether they have churned or not.

The goal of this project is to build a model that can predict which customers are most likely to churn, and to identify which factors contribute 
most to customer churn.

##Dataset
The dataset used in this project is the Telcom Customer Churn dataset. 

## Files
### Customer Churn Prediction: 
Jupyter notebook containing the code for the project

### Churn.csv: 
Dataset used for the analysis

### README.md:  
Readme file explaining the project

## Requirements
This project requires the following Python libraries:

pandas
numpy
matplotlib
seaborn
sklearn

## Analysis
The analysis includes the following steps:

Exploratory Data Analysis (EDA): 
This step involves understanding the data, exploring the relationship between the features and the target variable,
and identifying any trends or patterns.

Data Preprocessing:
This step involves cleaning the data, handling missing values, encoding categorical variables, and scaling numerical variables.

Feature Selection: This step involves selecting the most important features that contribute to customer churn using statistical tests, correlation analysis,
and feature importance scores.

Model Selection: This step involves selecting the appropriate model for the dataset and problem, and tuning the hyperparameters to achieve better performance.

Model Evaluation: This step involves evaluating the performance of the model using various metrics such as accuracy, precision, recall, and F1 score.
It also involves analyzing the confusion matrix and ROC curve.

## Conclusion
The analysis shows that the most important factors that contribute to customer churn are international call,customer calls and voice plan. The best performing model was the 
XGBoost Classifier, which achieved an accuracy of 92% and an F1 score of 0.75.
