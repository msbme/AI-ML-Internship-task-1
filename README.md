# AI/ML Internship - Heart Disease Prediction

## 📌 Project Objective
The goal of this project is to build a binary classification pipeline using health data to predict whether a patient is at risk of heart disease.

## 📊 Dataset
The project utilizes the **Heart Disease UCI Dataset**. It contains patient clinical features such as age, sex, chest pain type (`cp`), maximum heart rate achieved (`thalach`), and target status.

## 🛠️ Models Applied
- **Logistic Regression** (with StandardScaler feature normalization)
- **Decision Tree Classifier** (with max_depth=4 to optimize generalization)

## 📈 Key Results & Metrics
* **Logistic Regression Accuracy:** [85.19%]
* **Decision Tree Accuracy:** [79.63%]
* **Top Predictors:** Based on the Logistic Regression coefficients, the most critical features impacting prediction were found to be `[number of vessel fluro]`, `[sex]`, and `[chest pain type]`.

*Detailed confusion matrices and ROC curves are plotted cleanly inside the Jupyter Notebook.*
