# Medical_Insurance_Charges_Prediction

<img width="659" height="360" alt="image" src="https://github.com/user-attachments/assets/8362ef52-5a97-4ad4-8a89-85c5eb339e74" />

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1CNaQz3V8WbbgTnS9_guu1njWD1g_OVer?usp=sharing)

This project focuses on analyzing a Medical Insurance dataset and building a Machine Learning model to predict **insurance charges** based on customer details such as **age, BMI, number of children, sex, and smoking status**.  
The goal is to understand which factors impact insurance costs the most and create a model that can estimate charges for new customers.

---

## 📌 Problem Statement
Insurance companies need accurate cost estimation to set fair premiums and manage financial risk.  
In this project, we build a regression model to predict medical insurance charges using demographic and health-related features. This helps in pricing strategies and customer risk profiling.

---

## 📂 Dataset Information
The dataset contains the following columns:

- `age` → Age of the customer  
- `sex` → Gender (male/female)  
- `bmi` → Body Mass Index  
- `children` → Number of children/dependents  
- `smoker` → Smoking status (yes/no)  
- `region` → Residential area  
- `charges` → Medical insurance cost (Target Variable)

---

## 🛠 Tools & Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib  
- Scikit-learn  
- Google Colab / Jupyter Notebook  

---

## 🔍 Exploratory Data Analysis (EDA)
Key visualizations and insights:
- Charges distribution is right-skewed (many outliers)
- **Smoking status has the strongest effect on charges**
- Charges tend to increase with age and BMI
- Boxplot analysis shows smokers pay significantly higher insurance charges

---

## ✅ Data Preprocessing
- Converted categorical features using **One-Hot Encoding**
- Feature scaling using **StandardScaler**
- Applied **log transformation on charges** to reduce skewness and handle outliers better

---

## 🤖 Model Building
Models used:
- Linear Regression (Baseline)
- Ridge Regression (L2 Regularization)
- Lasso Regression (L1 Regularization)

---

## 📊 Model Evaluation Metrics
The regression model is evaluated using:
- **MAE (Mean Absolute Error)**
- **MSE (Mean Squared Error)**
- **RMSE (Root Mean Squared Error)**
- **R² Score**
- **Adjusted R² Score**

---

## 🎯 Results
- The Ridge Regression model achieved a strong performance with an R² score of approximately **0.77**
- Smoking status is the most important feature for predicting medical charges

---

## 🧪 How to Run This Project
1. Clone the repository:
   git clone
   
