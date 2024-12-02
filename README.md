# **Students-Performance-Indicator**

## Project Description
This project aims to analyze and predict students' academic performance based on various features such as Gender, Ethnicity, Parental level of education, Lunch type, and Test preparation course. By leveraging machine learning models, specifically Linear Regression and Ridge Regression, we can understand the impact of these factors on students' test scores and make informed predictions about their future performance. The analysis helps identify patterns and insights that can be used to improve educational outcomes and provide targeted support to students.

## Context

Understanding the factors that influence student performance is crucial for educators, policymakers, and stakeholders in the education sector. By analyzing data from students, we can uncover how demographic and socio-economic factors affect their academic achievements. This project provides a comprehensive analysis of the impact of various attributes on students' test scores, enabling data-driven decisions to enhance educational strategies and interventions.

## Feature Information

The dataset contains the following attributes/features:

- **gender**: Gender of the student (e.g., male, female)

- **race/ethnicity**: The group to which the student belongs (e.g., Group A, Group B, etc.)

- **parental level of education**: The highest level of education achieved by the student's parent(s) (e.g., bachelor's degree, some college, master's degree, etc.)

- **lunch**: Type of lunch the student receives (e.g., standard, free/reduced)

- **test preparation course**: Whether the student completed a test preparation course (e.g., none, completed)

- **math score**: The math score of the student (0-100)

- **reading score**: The reading score of the student (0-100)

- **writing score**: The writing score of the student (0-100)

## Project Objective

The objective of this project is to:

- **Analyze** how different features impact students' test scores.

- **Build** predictive models using Linear Regression and Ridge Regression to forecast students' performance.

- **Identify** high-performing students based on a defined threshold (e.g., scores above 70).

- **Estimate** the percentage of students likely to perform well in the future.

- **Provide** actionable insights for educators and policymakers to enhance educational outcomes and support student success.

## Insights

- Both Linear Regression and Ridge Regression models have high predictive accuracy, with R2 scores of approximately 0.88.

- The percentage of students who actually performed well (scoring above 70) is 37.50%.

- The percentage of students predicted to perform well in the future is 39.00%.

- Other models such as Lasso Regression, K-Neighbors Regressor, Decision Tree, Random Forest Regressor, and XGBRegressor show varying degrees of performance, with some models indicating overfitting.