# Employee Attrition Prediction using Machine Learning

## 📌 Project Overview
This project focuses on analyzing employee data to understand the key factors contributing to attrition and building a machine learning model to predict whether an employee is likely to leave the organization.

The goal is to assist organizations in identifying at-risk employees and enabling proactive retention strategies.

---

## 🎯 Objectives
- Analyze employee behavior and identify patterns leading to attrition  
- Perform Exploratory Data Analysis (EDA) to extract insights  
- Build a predictive model using Machine Learning  
- Evaluate model performance using multiple metrics  
- Optimize predictions using threshold tuning and cross-validation  

---

## 📊 Dataset
- HR dataset containing employee details such as:
  - Satisfaction Level  
  - Average Monthly Hours  
  - Number of Projects  
  - Time Spent in Company  
  - Salary  
  - Department  
  - Attrition (Target Variable: `left`)  

---

## 🔍 Exploratory Data Analysis (EDA)
- Identified **burnout patterns**:
  - Employees with low satisfaction and high working hours are more likely to leave  
- Analyzed relationships between:
  - Satisfaction level vs working hours  
  - Department and salary vs attrition  
- Used visualization techniques such as scatter plots and regression plots  

---

## ⚙️ Data Preprocessing
- Label Encoding for **salary (ordinal feature)**  
- One-Hot Encoding for **department (nominal feature)**  
- Feature selection and data cleaning  

---

## 🤖 Model Building
- Implemented **Random Forest Classifier**
- Reason for selection:
  - Handles non-linear relationships  
  - Robust to overfitting  
  - Provides feature importance  

---

## 📈 Model Evaluation
- Accuracy: **~99%**
- ROC-AUC Score: **~0.99**
- Used:
  - Classification Report  
  - Confusion Matrix  
  - ROC Curve  

---

## 🎯 Threshold Tuning
- Adjusted decision threshold to improve recall for employees likely to leave  
- Achieved better balance between false positives and false negatives  

---

## 🔁 Cross Validation
- Applied **5-Fold Cross Validation**
- Mean ROC-AUC Score: **~0.99**
- Ensured model stability and generalization  

---

## 📌 Key Insights
- **Satisfaction level** is the most important factor influencing attrition  
- High workload (projects & working hours) contributes to employee burnout  
- Salary and department have relatively lower impact compared to behavioral factors  

---

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

