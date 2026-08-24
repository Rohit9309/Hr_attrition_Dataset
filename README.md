# Hr_attrition_Dataset
# Employee Attrition Analysis

## 📌 Project Overview

This project focuses on analyzing employee attrition using an HR dataset containing information about 5,000 employees.

The main objective is to understand the factors associated with employees leaving the company and use HR analytics to identify patterns that can support better employee retention strategies.

## 🎯 Objectives

* Understand the employee attrition business problem.
* Explore and understand the HR dataset.
* Identify important features related to employee attrition.
* Perform exploratory data analysis (EDA).
* Analyze the distribution of employee attrition.
* Study relationships between employee characteristics and attrition.
* Identify potential factors that may influence employee turnover.
* Formulate the problem as a machine learning classification problem.
* Prepare the dataset for future employee attrition prediction.

## 📊 Dataset

The project uses the **HR Attrition Indian Dataset**.

### Dataset Size

* **Records:** 5,000 employees
* **Features:** 22 columns
* **Target Variable:** `LeftCompany`

### Target Variable

`LeftCompany` indicates whether an employee left the company.

* `Yes` → Employee left the company
* `No` → Employee stayed with the company

## 📋 Dataset Features

The dataset contains information related to:

* Employee demographics
* Gender
* Department
* Designation
* Education qualification
* Monthly salary
* Date of joining
* Years with company
* Years in current role
* Appraisal rating
* Training hours
* Overtime
* Job satisfaction
* Work-life balance
* Marital status
* Previous companies
* Distance from home
* Leaves taken
* City
* Employee attrition status

## 🔍 Exploratory Data Analysis

The following analysis is performed on the dataset:

1. Dataset shape and structure
2. Data types
3. Statistical summary
4. Missing value analysis
5. Duplicate record analysis
6. Employee attrition distribution
7. Age distribution
8. Salary distribution
9. Department-wise attrition analysis
10. Overtime and attrition analysis
11. Job satisfaction and attrition analysis
12. Work-life balance and attrition analysis
13. Correlation matrix

## 🧠 Problem Formulation

The project is formulated as a **binary classification problem**.

### Input

Employee-related HR information such as:

* Age
* Department
* Designation
* Monthly salary
* Years with company
* Appraisal rating
* Training hours
* Overtime
* Job satisfaction
* Work-life balance
* Distance from home
* Other HR-related features

### Output

`LeftCompany`

The model will predict whether an employee is likely to leave the company.

## 🔄 Project Workflow

```text
Business Understanding
        ↓
Dataset Understanding
        ↓
Feature Dictionary
        ↓
Problem Formulation
        ↓
Data Cleaning
        ↓
Exploratory Data Analysis
        ↓
Feature Engineering
        ↓
Model Building
        ↓
Model Evaluation
        ↓
Business Insights
        ↓
Employee Retention Strategies
```

## 📁 Repository Structure

```text
employee-attrition-analysis/
│
├── HR_Attrition_Indian_Dataset.csv
│
├── notebooks/
│   └── Employee_Attrition_EDA.ipynb
│
├── reports/
│   ├── Business_Problem_Statement.md
│   ├── Feature_Dictionary.md
│   ├── Dataset_Report.md
│   ├── Problem_Formulation.md
│   ├── Workflow.md
│   └── Ethics_Report.md
│
├── README.md
│
└── requirements.txt
```

## 🔐 Ethical Considerations

Employee data should be handled responsibly and confidentially.

The project considers:

* Employee data privacy
* Protection of personally identifiable information
* Fairness in prediction
* Potential model bias
* Responsible use of prediction results
* Secure handling of HR information

Employee names and identifiers should not be used as predictive features.

## 🚀 Future Work

The next stages of this project will include:

* Data preprocessing
* Encoding categorical variables
* Feature engineering
* Train-test split
* Model training
* Logistic Regression
* Decision Tree
* Random Forest
* Model evaluation
* Model comparison
* Identification of important features
* Business recommendations for employee retention

## 📚 Project Deliverables

The project includes:

* Business Problem Statement
* Feature Dictionary
* Dataset Report
* Problem Formulation
* Workflow Diagram
* Ethics Report
* Exploratory Data Analysis

## 👨‍💻 Project Status

**Current Stage:** Dataset Understanding and Exploratory Data Analysis

The dataset has been uploaded to the repository and the initial project structure and analysis plan have been prepared.
