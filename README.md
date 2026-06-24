# Customer-Churn-Prediction-ML
# Customer Churn Prediction Using Machine Learning

## Overview

Customer churn is a major challenge for subscription-based businesses, especially in the telecommunications industry. Acquiring new customers is often more expensive than retaining existing ones. This project focuses on predicting customer churn using machine learning techniques to help businesses identify customers who are likely to leave and take proactive retention measures.

The project involves data preprocessing, exploratory data analysis (EDA), feature engineering, handling class imbalance, model training, and performance evaluation using multiple machine learning algorithms.

---

## Business Problem

Telecom companies face significant revenue loss when customers discontinue their services. By accurately predicting churn, organizations can:

* Improve customer retention strategies
* Reduce customer acquisition costs
* Increase customer lifetime value
* Enhance customer satisfaction
* Make data-driven business decisions

---

## Dataset Information

**Dataset:** Telco Customer Churn Dataset

The dataset contains customer demographic information, account details, subscribed services, and churn status.

### Dataset Features

#### Customer Information

* Gender
* Senior Citizen
* Partner
* Dependents

#### Service Information

* Phone Service
* Multiple Lines
* Internet Service
* Online Security
* Online Backup
* Device Protection
* Tech Support
* Streaming TV
* Streaming Movies

#### Account Information

* Tenure
* Contract Type
* Paperless Billing
* Payment Method
* Monthly Charges
* Total Charges

#### Target Variable

* Churn (Yes / No)

---

## Project Objectives

* Understand customer behavior patterns
* Perform data cleaning and preprocessing
* Conduct exploratory data analysis
* Handle missing values and categorical variables
* Address class imbalance using SMOTE
* Train multiple machine learning models
* Evaluate model performance
* Identify key factors influencing churn

---

## Technology Stack

### Programming Language

* Python

### Libraries Used

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Imbalanced-Learn (SMOTE)
* Joblib

### Development Environment

* Jupyter Notebook

---

## Project Workflow

### 1. Data Collection

Imported the Telco Customer Churn dataset and examined its structure, dimensions, and data types.

### 2. Data Cleaning

* Checked for missing values
* Handled inconsistent data
* Converted data types where required
* Removed unnecessary formatting issues

### 3. Exploratory Data Analysis (EDA)

Performed comprehensive analysis to understand:

* Customer demographics
* Service subscription patterns
* Churn distribution
* Relationship between features and churn

### 4. Data Preprocessing

* Label Encoding
* Feature Transformation
* Data Preparation for Machine Learning

### 5. Handling Class Imbalance

Applied **SMOTE (Synthetic Minority Oversampling Technique)** to balance churn and non-churn classes.

### 6. Model Building

Implemented multiple machine learning algorithms including:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier

### 7. Model Evaluation

Evaluated model performance using:

* Accuracy Score
* Confusion Matrix
* Classification Report

### 8. Prediction System

Built a prediction pipeline capable of predicting whether a customer is likely to churn based on input features.

---

## Key Insights

### Customer Retention Findings

* Customers with month-to-month contracts are more likely to churn.
* Long-tenure customers tend to remain loyal.
* Higher monthly charges show a stronger association with churn.
* Customers using additional support services are generally less likely to leave.
* Contract type significantly impacts customer retention.

---

## Machine Learning Models

| Model               | Purpose                       |
| ------------------- | ----------------------------- |
| Logistic Regression | Baseline Classification Model |
| Decision Tree       | Rule-Based Prediction         |
| Random Forest       | Ensemble Learning Model       |

---

## Project Structure

```bash
customer-churn-prediction-ml/
│
├── Customer_Churn_Prediction_using_ML.ipynb
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── README.md
├── requirements.txt
│
└── images/
```

## Installation

### Clone Repository

```bash
git clone https://github.com/your-username/customer-churn-prediction-ml.git
```

### Move to Project Folder

```bash
cd customer-churn-prediction-ml
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```bash
Customer_Churn_Prediction_using_ML.ipynb
```

---

## Future Improvements

Planned enhancements include:

* Hyperparameter Tuning
* XGBoost Implementation
* Feature Importance Analysis
* Streamlit Deployment
* Interactive Dashboard Development
* Real-Time Prediction System

---

## Skills Demonstrated

### Data Analytics

* Data Cleaning
* Exploratory Data Analysis
* Statistical Analysis
* Data Visualization

### Machine Learning

* Classification Models
* Model Evaluation
* Feature Engineering
* Handling Imbalanced Data

### Tools

* Python
* Jupyter Notebook
* Scikit-Learn
* GitHub

---

## Learning Outcomes

Through this project, I gained hands-on experience in:

* End-to-end machine learning workflow
* Customer behavior analysis
* Churn prediction techniques
* Data preprocessing strategies
* Business-focused analytical thinking

---

## Author

**Upputholla Gnanendra**

Aspiring Data Analyst | Python | SQL | Power BI | Machine Learning

LinkedIn: Add Your LinkedIn URL

GitHub: Add Your GitHub Profile URL

---

## License

This project is intended for educational and portfolio purposes.
