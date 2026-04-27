# 🫀 Early Prediction of Obesity-Related Cardiovascular Risk Using Machine Learning Models

---

## 📌 Project Overview
This project presents a machine learning-based system for the **early prediction of cardiovascular disease (CVD) risk associated with obesity**. The goal is to identify high-risk individuals at an early stage and support preventive healthcare interventions.

The system uses the **Framingham Heart Study dataset** and applies advanced preprocessing, feature engineering, and machine learning models to predict **10-year coronary heart disease (CHD) risk**.

---

## 👩‍🎓 Student Information
- **Name:** Archana Aavula  
- **Student Number:** U2961498  
- **Course:** MSc Computer Science  
- **Supervisor:** Damilola  

---

## 🎯 Aim & Objectives

### **Aim**
To develop and evaluate machine learning models for early prediction of obesity-related cardiovascular risk.

### **Objectives**
- Analyze obesity-related health data  
- Perform data preprocessing and feature engineering  
- Build multiple ML models for prediction  
- Evaluate models using performance metrics  
- Identify the best-performing model  

---

## 📊 Dataset
- **Dataset:** Framingham Heart Study Dataset  
- **Source:** Kaggle  
- **Target Variable:** `TenYearCHD` (10-year CHD risk)

### **Features Include:**
- Age, Gender  
- BMI (Body Mass Index)  
- Blood Pressure (Systolic & Diastolic)  
- Cholesterol Levels  
- Glucose  
- Smoking Habits  
- Diabetes Status  

---

## ⚙️ Methodology

### 🔹 Data Preprocessing
- Missing value handling:
  - Median Imputation  
  - KNN Imputation  
- Feature scaling using **StandardScaler**
- Encoding categorical variables  

### 🔹 Feature Engineering
- Pulse Pressure  
- Mean Arterial Pressure (MAP)  
- BMI Categories  

### 🔹 Data Balancing
- **SMOTETomek** (combination of over & under sampling)

---

## 🧠 Models Implemented
- Logistic Regression  
- Decision Tree  
- Random Forest  
- XGBoost  
- LightGBM  
- Convolutional Neural Network (CNN)  
- Stacking Ensemble Model  

---

## 📈 Results & Performance

### 🔥 Best Performing Model: **Tuned XGBoost**
- **Accuracy:** 82.31%  
- **Precision:** 31.57%  
- **Recall:** 13.95%  
- **F1 Score:** 19.35%  
- **ROC-AUC:** 0.645  

### 🧪 Observations
- Models perform well in overall accuracy  
- **Low recall indicates difficulty detecting positive cases**  
- Data imbalance remains a key challenge  

---

## 📊 Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- ROC-AUC  
- Confusion Matrix  

---

## 📂 Project Structure
