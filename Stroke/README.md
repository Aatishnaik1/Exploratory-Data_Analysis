# 🧠 Stroke Prediction Analysis & Machine Learning Project

This project performs Exploratory Data Analysis (EDA) and predictive modeling on a Stroke Prediction dataset.  
The goal is to understand the factors that contribute to stroke risk and build a machine-learning model capable of predicting whether a patient is likely to suffer a stroke based on medical and demographic features.

---

## 📌 Project Overview

This analysis focuses on:
- Understanding stroke-related factors
- Identifying which features most strongly influence stroke occurrence
- Data cleaning, preprocessing, and handling missing values
- Exploratory data visualizations
- Feature engineering
- Building ML classification models to predict stroke risk

The entire workflow is implemented in the notebook:

`Stroke.ipynb`

---

## 🗂️ Dataset Information

The dataset typically includes the following features:
- `gender`
- `age`
- `hypertension`
- `heart_disease`
- `ever_married`
- `work_type`
- `Residence_type`
- `avg_glucose_level`
- `bmi`
- `smoking_status`
- `stroke` (target label)

Each record represents a person with associated health and lifestyle factors.

---

## 🔧 Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 🧹 Data Cleaning & Processing

Steps performed:
- Handling missing values (especially BMI)
- Encoding categorical variables
- Checking class imbalance
- Scaling numerical features
- Splitting data into training & test sets
- Outlier detection and removal where necessary

---

## 📊 Exploratory Data Analysis (EDA)

The project includes visualizations such as:
- Distribution plots for age, BMI, glucose levels
- Count plots for hypertension, heart disease, marital status, smoking status
- Heatmap of feature correlations
- Boxplots for detecting outliers
- Stroke vs. non-stroke comparisons

Insights show how medical and lifestyle factors vary between stroke and non-stroke populations.

---

## 🤖 Machine Learning Modeling

Models used:
- Logistic Regression  
- Random Forest Classifier  
- Decision Tree  
- K-Nearest Neighbors  
- Support Vector Machine  

Evaluation metrics:
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

Oversampling (SMOTE) or class weighting may be used to address dataset imbalance.

---

## 📝 Key Insights

- Age and average glucose level strongly impact stroke likelihood.
- Hypertension and heart disease show higher stroke correlation.
- Individuals with unhealthy lifestyle factors (smoking, high BMI) have increased risk.
- There is a clear imbalance: very few positive stroke cases vs. many non-stroke cases.
- Tree-based models generally perform better for medical classification tasks.

---

## 🏁 Conclusion

This project provides a complete walkthrough of stroke risk analysis using data science.  
The findings help identify high-risk individuals and show which features contribute most to stroke prediction.  
The machine-learning models demonstrate the potential for early detection systems in healthcare applications.

---

## 📌 Future Scope

- Implement deep learning models
- Hyperparameter tuning for better model accuracy
- Deploy the model as a web app (Flask/Streamlit)
- Include additional medical features for stronger predictions
- Build a dashboard for hospital/clinical use

---

## 👤 Author

**Your Name**  
Stroke Prediction Project — 2025
