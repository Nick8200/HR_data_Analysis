# Employee Analysis And Attrition Prediction

## Overview

### This project focuses on predicting employee attrition using logistic regression. The dataset comprises various features related to employee demographics, job roles, satisfaction levels, and performance metrics. By analyzing this data, we aim to gain insights into the factors that influence employee attrition and build a predictive model to identify employees who are likely to leave the company.

## Project Structure
### The project is organized into the following sections:

1.Data Exploration and Preprocessing

2.Exploratory Data Analysis (EDA)

3.Feature Engineering

4.Model Building and Evaluation

5.Conclusion and Insights

## Data
### The dataset used in this project contains the following columns:

* Age

* Attrition

* BusinessTravel

* DailyRate

* Department

* DistanceFromHome

* Education

* EducationField

* EmployeeNumber

* EnvironmentSatisfaction

* Gender

* HourlyRate

* JobInvolvement

* JobLevel

* JobRole

* JobSatisfaction

* MaritalStatus

* MonthlyIncome

* MonthlyRate

* NumCompaniesWorked

* OverTime

* PercentSalaryHike

* PerformanceRating

* RelationshipSatisfaction

* StockOptionLevel

* TotalWorkingYears

* TrainingTimesLastYear

* WorkLifeBalance

* YearsAtCompany

* YearsInCurrentRole

* YearsSinceLastPromotion

* YearsWithCurrManager

* AgeGroup

## Data Exploration and Preprocessing

### In this section, we load the dataset, handle missing values, and encode categorical variables. The columns BusinessTravel, Department, EducationField, Gender, JobRole, MaritalStatus, OverTime, and AgeGroup are one-hot encoded to convert them into numerical format suitable for model training.

## Exploratory Data Analysis (EDA)
### We perform EDA to understand the distribution of the data and the relationships between various features and employee attrition. Key steps include:

* Visualizing the distribution of employees who left versus those who stayed.
* Analyzing the correlation between different features and attrition.
* Identifying key factors that contribute to employee attrition.

![h R image](https://github.com/user-attachments/assets/7d930390-5d1c-4723-9cbc-d063b9613be0)

![newplot](https://github.com/user-attachments/assets/fd9e1ad3-73d7-451b-bc92-6c5d0acf4050) 

![newplot (1)](https://github.com/user-attachments/assets/8b71525f-ae3c-4730-a1a1-47df07b64b1b)

![newplot (2)](https://github.com/user-attachments/assets/e83c17bb-cde5-4b5e-9c3b-8cb78c87ac09)

![newplot (3)](https://github.com/user-attachments/assets/0fad1b4c-00ec-46b5-ba1f-143159cc1ae2)

![download (4)](https://github.com/user-attachments/assets/f4b27eb9-70c8-426b-9933-6300176adf2b)

![download (2)](https://github.com/user-attachments/assets/cb776022-c9ce-44cb-a5a7-62fa3b8681ac)

![download (3)](https://github.com/user-attachments/assets/e055f0ad-f3db-4720-9755-2c9b3472d779)

![download (1)](https://github.com/user-attachments/assets/f0af74e7-58f9-46fe-b70e-7d0487fd6480)

## Feature Engineering
### Feature engineering involves creating new features or modifying existing ones to improve model performance. In this project, we focus on:

* Creating age groups from the Age column.
* Encoding categorical variables.
* Normalizing numerical features.

## Model Building and Evaluation
### We use logistic regression to build a predictive model for employee attrition. The model is trained on the preprocessed dataset and evaluated using accuracy, precision, recall, and F1 score. Key steps include:

* Splitting the data into training and testing sets.
* Training the logistic regression model.
* Evaluating model performance on the test set.

## Conclusion and Insights
### In this section, we summarize the findings from our analysis and the performance of our predictive model. Key insights include:

* The most influential factors contributing to employee attrition.
* Recommendations for reducing attrition based on model insights.











