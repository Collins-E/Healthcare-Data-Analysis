# Healthcare Data Analysis

## Objective

Analyze and preprocess a healthcare dataset to understand patient characteristics and prepare the data for machine learning applications.

## Tools Used

* Python
* pandas
* scikit learn
* seaborn
* matplotlib

## Dataset Overview

* 55,500 patient records
* 15 original features
* Includes demographics, medical conditions, billing, and admission details

## Key Analysis Performed

* Data cleaning and column standardization
* Data type identification (categorical vs numerical)
* Descriptive statistics and variance analysis
* Missing value check (no missing values found)
* Categorical analysis (Admission Type, Gender)
* Data visualization (Gender distribution)

## Feature Engineering

* Created dummy variables for:

  * Test Results
  * Medical Condition
  * Admission Type
* Increased dataset from 15 to 24 features

## Data Preprocessing

* Applied StandardScaler to normalize Age
* Achieved mean = 0 and standard deviation = 1

## Model Preparation

* Split dataset into:

  * Training set: 38,850 records (70%)
  * Testing set: 16,650 records (30%)

## Key Insights

* Billing Amount has the highest variance among numerical features
* Gender distribution is balanced across patients
* Admission types are evenly distributed across three categories
* Dataset is clean and ready for machine learning

## Conclusion

This project demonstrates a complete data preprocessing workflow, including cleaning, transformation, feature engineering, and preparation for modeling. The dataset is well structured and suitable for predictive analytics.
