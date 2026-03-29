# 📊 Customer Churn Prediction & Risk Segmentation

## 🧾 Project Overview

Customer churn is a major challenge for businesses, as losing customers directly impacts revenue and growth. This project focuses on building a machine learning model to predict whether a customer is likely to churn based on their demographic and service usage information.

The goal of this project is to help businesses identify high-risk customers early and take proactive retention actions to reduce churn and improve customer satisfaction.

---

## 🎯 Objective

✔ Predict customer churn using machine learning models
✔ Compare multiple algorithms to select the best-performing model
✔ Provide actionable business insights to reduce customer churn
✔ Demonstrate an end-to-end data analysis and machine learning workflow

---

## 📂 Dataset Description

The dataset contains customer information including:

📌 Customer demographics
📌 Account information
📌 Service usage details
📌 Payment methods
📌 Contract type
📌 Monthly and total charges
🎯 Target variable: **Churn (Yes / No)**

---

## ⚙️ Project Workflow

### 🔹 1. Data Collection

* Loaded dataset using **Pandas**
* Inspected data structure and data types

### 🔹 2. Data Preprocessing

✔ Handled missing values
✔ Encoded categorical variables
✔ Scaled numerical features using **StandardScaler**
✔ Split dataset into training and testing sets

---

### 🔹 3. Exploratory Data Analysis (EDA)

📊 Analyzed customer behavior patterns
📈 Visualized churn distribution
🔍 Identified key factors affecting churn

#### 🔎 Key Insights

* Customers with shorter tenure are more likely to churn
* Higher monthly charges increase churn probability
* Contract type significantly impacts churn behavior

---

### 🔹 4. Model Building

The following machine learning models were trained and evaluated:

🤖 Logistic Regression
🌳 Decision Tree
🌲 Random Forest
📍 K-Nearest Neighbors (KNN)
📐 Support Vector Machine (SVM)
⚡ XGBoost

---

## 📏 Model Evaluation Metrics

Models were evaluated using:

📌 Accuracy
📌 Precision
📌 Recall
📌 F1 Score
📌 ROC-AUC Score

---

## 📊 Model Performance Summary

| Model               | Accuracy | F1 Score | ROC-AUC  |
| ------------------- | -------- | -------- | -------- |
| Logistic Regression | 0.79     | 0.60     | 0.85     |
| Decision Tree       | 0.79     | 0.55     | 0.84     |
| Random Forest       | **0.80** | 0.61     | **0.86** |
| KNN                 | 0.76     | 0.55     | 0.79     |
| SVM                 | 0.80     | **0.62** | 0.85     |
| XGBoost             | 0.80     | 0.61     | 0.86     |

---

## 🏆 Best Model Selection

**🌲 Random Forest** was selected as the final model because it achieved the highest overall performance based on Accuracy and ROC-AUC score.

### 📌 Best Model Performance

✔ Accuracy: **80.48%**
✔ ROC-AUC Score: **0.861**
✔ Strong generalization and reduced overfitting

---

## 💼 Business Recommendations

📌 Identify high-risk customers using the churn prediction model
📌 Provide personalized retention offers and loyalty programs
📌 Improve customer support and service quality
📌 Monitor customers with high monthly charges
📌 Implement proactive engagement strategies

These actions can help reduce customer churn and improve long-term profitability.

---

## 🛠️ Technologies Used

🐍 Python
📊 Pandas
🔢 NumPy
📈 Matplotlib
📉 Seaborn
🤖 Scikit-learn
⚡ XGBoost
📓 Jupyter Notebook

---

## 📁 Project Structure

```
Customer-Churn-Prediction/
│
├── Customer_Churn_Prediction.ipynb
├── dataset.csv
├── README.md
└── model_results.csv
```

## 👩‍💻 Author

**JINITHA P S**
📊 Data Analyst | 🤖 Machine Learning Enthusiast

---

## 📌 Project Status

✅ **Completed**
