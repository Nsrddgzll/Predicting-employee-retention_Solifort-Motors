# Predicting employee retention

### Overview

The goal  of this project was to build a logistic regression and Tree based machine learning model(Random Forrest and XGBoost) to foresee who might leave, aiding in understanding and tackling the root causes. This project unulized dataset about employees gathered by HR department that includes 10 features. Final XGBoost model performed with 98 % accuracy, 95 % recall, 97% precision and 98% roc_auc 	determining what features were the most important to splitting employees who will leave and who will stay.

### Business Understanding 

There is a high rate of turnover among Salifort employees. (Note: In this context, turnover data includes both employees who choose to quit their job and employees who are let go). Salifort’s senior leadership team is concerned about how many employees are leaving the company. Salifort strives to create a corporate culture that supports employee success and professional development. Further, the high turnover rate is costly in the financial sense. Salifort makes a big investment in recruiting, training, and upskilling its employees. 

### Data Understanding

Hr Analytics Job Prediction data came from [Kaggle](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction?select=HR_comma_sep.csv). Dataset comprising 15,000 entries and featuring 10 columns, each representing different aspects of employee-related information. 

Variable  |Description |
-----|-----|
satisfaction_level|Employee-reported job satisfaction level [0&ndash;1]|
last_evaluation|Score of employee's last performance review [0&ndash;1]|
number_project|Number of projects employee contributes to|
average_monthly_hours|Average number of hours employee worked per month|
time_spend_company|How long the employee has been with the company (years)
Work_accident|Whether or not the employee experienced an accident while at work
left|Whether or not the employee left the company
promotion_last_5years|Whether or not the employee was promoted in the last 5 years
Department|The employee's department
salary|The employee's salary (U.S. dollars)




This repository contains the code and documentation for my capstone project for Google Advance Data Analytics Certificate, the HR Churn Predictor. The project focuses on predicting employee churn in a company based on a dataset from the HR department. The goal is to provide insights that can help organizations identify potential turnover risks and take proactive measures to retain valuable employees. 

In this lab, I have employed statistical model - Logistic regression,  and  Machine learning models - Random Forrest and XGBoost to predict Employee churn. 

Notebook consist of four phases:

**Plan**

Understanding data and Business problem

**Analyse**

This phase covers Data preprocessing, Explarotary Data Analysis, checking model assumptions and selecting models

**Construct**

In this phase, I constructed Logistic regression, Random Forrest and XGBoost and evaluated each model using appropriate metrics

**Execute**
This phase covers interpreting finding and sharing insights 



## Usage

1. Open notebook in a Jupyter environment.
2. Execute the cells sequentially to reproduce the analysis and results.

## Data

The dataset used for this project is located in this repository. It includes features such as employee satisfaction, performance, and other relevant attributes.

## Results

Detailed results and performance metrics are presented within the notebook.
