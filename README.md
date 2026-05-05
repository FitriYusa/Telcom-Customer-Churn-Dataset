# Customer Churn Prediction using Machine Learning

## Overview

Customer churn is one of the most important challenges for subscription-based businesses. Retaining existing customers is often more cost-effective than acquiring new ones.

This project builds a machine learning model to predict whether a customer is likely to churn based on demographic information, account details, and service usage patterns.

The project includes:

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Machine learning model training
- Model evaluation
- Business insights generation

---

## Problem Statement

Customer churn negatively impacts revenue and business growth.

The objective of this project is to:

- Predict customer churn using historical customer data
- Identify key factors contributing to churn
- Provide actionable business insights for retention strategies

---

## Dataset

**Dataset Used:** Telco Customer Churn Dataset

The dataset contains customer-level information including:

- Demographics
- Subscription details
- Billing information
- Contract type
- Service usage
- Churn status

## Project Workflow

### 1. Data Collection
Loaded the dataset into Pandas for analysis.

### 2. Data Cleaning
Performed:

- Missing value handling
- Data type correction
- Removal of unnecessary columns

### 3. Exploratory Data Analysis
Analyzed:

- Churn distribution
- Feature relationships
- Correlation patterns

### 4. Feature Engineering
- One-hot encoding
- Feature scaling

### 5. Model Building
Built a **Logistic Regression** classification model.

### 6. Model Evaluation
Evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

### 7. Insight Extraction
Identified the most influential factors driving customer churn.

---

#### Result

- **Accuracy:** 79%
- **Precision (Churn = 1):** 62%
- **Recall (Churn = 1):** 52%
- **F1-score (Churn = 1):** 56%

Based on the above evaluation, the model performance on churn prediction (Class 1) shows: 
- Lower recall (52%) which indicates that some churn cases are missed.
- Precision (62%) shows a relatively okay correctness when predicting churn

On the bussiness perspective, this model is useful for general churn trends but for real-world use, missing a churn customer indicates a loss for business.