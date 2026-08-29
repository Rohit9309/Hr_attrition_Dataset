# Enterprise Data Preparation for Employee Attrition

## 📌 Project Overview

This project focuses on preparing an HR employee dataset for employee attrition analysis and future machine learning prediction.

The dataset contains information about 5,000 employees and includes demographic, job-related, salary, satisfaction, work-life balance, and other HR-related features.

The main objective of this project is to clean, transform, and prepare the HR dataset for machine learning.

---

## 📊 Dataset

### Dataset Name

HR Attrition Indian Dataset

### Dataset Size

- Records: 5,000 employees
- Features: 22 columns
- Target Variable: `LeftCompany`

### Target Variable

`LeftCompany` indicates whether an employee left the company.

- `Yes` → Employee left the company
- `No` → Employee stayed with the company

---

## 🎯 Project Objectives

The main objectives of this project are:

- Import the HR dataset.
- Analyze the structure and quality of the data.
- Handle missing values.
- Identify and handle duplicate records.
- Detect potential outliers.
- Encode categorical variables.
- Scale numerical variables.
- Create meaningful derived HR features.
- Build a preprocessing pipeline.
- Export the processed dataset.

---

## 🧹 Data Preparation

The following data preparation activities are performed:

### 1. Missing Value Handling

The dataset was checked for missing values and an appropriate preprocessing strategy was applied where required.

### 2. Duplicate Handling

Duplicate records were checked and handled during the data-cleaning process.

### 3. Outlier Detection

Numerical features were analyzed using statistical methods and visualizations to identify potential outliers.

### 4. Categorical Encoding

Categorical variables are converted into numerical representations using encoding techniques so that they can be used by machine learning algorithms.

### 5. Numerical Scaling

Numerical variables are standardized using `StandardScaler` to bring features to a comparable scale.

---

## ⚙️ Feature Engineering

Additional HR-related features are created from existing variables to provide useful information for employee attrition analysis.

Derived features include:

- `TenureGroup`
- `OverallSatisfaction`
- `SalaryPerYearExperience`
- `RoleTenureRatio`

These features are created to capture additional relationships between employee experience, satisfaction, salary, and tenure.

---

## 🔄 Preprocessing Pipeline

The preprocessing workflow follows:

```text
Raw HR Dataset
      ↓
Remove Personal Identifiers
      ↓
Missing Value Handling
      ↓
Feature Engineering
      ↓
Categorical Encoding
      ↓
Numerical Scaling
      ↓
Processed Dataset
