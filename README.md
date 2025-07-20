# 🧠 Week 4 – Predicting Employee Attrition with Machine Learning

This project was completed as part of the **NSP Internship – Week 4**.  
The goal is to analyze employee data from IBM and build predictive models that can identify whether an employee is likely to leave the organization.

---

## 📌 Project Overview

Understanding employee attrition is essential for any organization. In this project, we use HR data to explore patterns behind attrition and apply machine learning techniques to build accurate prediction models.

---

## 📂 Dataset Information

- **Name**: IBM HR Analytics Employee Attrition & Performance  
- **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)  
- **Attributes**: Age, JobSatisfaction, MonthlyIncome, OverTime, etc.

---

## 🧰 Tools & Technologies

- **Programming Language**: Python  
- **Libraries**:
  - `pandas`, `numpy` – data manipulation
  - `matplotlib`, `seaborn` – data visualization
  - `scikit-learn` – machine learning

---

## 🔎 Steps Performed

### 1. Data Loading & Inspection
- Imported the dataset using `pandas`
- Inspected column types, value counts, and nulls

### 2. Preprocessing
- Encoded categorical columns
- Scaled numerical features
- Checked class distribution of the `Attrition` target

### 3. EDA (Exploratory Data Analysis)
- Used visualizations to analyze relationships between features and attrition
- Found significant factors like:
  - OverTime status
  - JobSatisfaction
  - MonthlyIncome

### 4. Model Building
- Split dataset into training and testing sets (80/20)
- Built 3 classification models:
  - Logistic Regression
  - Decision Tree
  - Random Forest

### 5. Model Evaluation
- Compared model metrics: Accuracy, Precision, Recall, F1-score
- Selected the best-performing model

---

## 🏁 Final Results

- **Best Model**: Random Forest Classifier  
- **Accuracy**: ~85%  
- **Key Features**:
  - OverTime
  - JobSatisfaction
  - EnvironmentSatisfaction

---




