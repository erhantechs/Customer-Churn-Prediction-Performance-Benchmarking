# 🏦 Bank Customer Churn Prediction & Performance Benchmarking

This repository contains a comprehensive end-to-end data science project focused on predicting customer churn for a banking institution. The goal is to identify high-risk customers and understand the underlying factors that lead to churn using various Machine Learning techniques.

## 📊 Project Overview
Customer churn occurs when customers stop doing business with a company. For banks, retaining existing customers is often more cost-effective than acquiring new ones. This project analyzes customer behavior and builds predictive models to anticipate potential churn.

### Key Features:
* **Exploratory Data Analysis (EDA):** Deep dive into demographics (Age, Geography, Gender) and financial behavior (Balance, Number of Products, Credit Score).
* **Data Preprocessing:** Handling outliers, feature encoding (OneHot & Label Encoding), and feature scaling.
* **Addressing Class Imbalance:** Applied **SMOTE** (Synthetic Minority Over-sampling Technique) to handle the skewed distribution of churned vs. non-churned customers.
* **Model Benchmarking:** Comparison of multiple algorithms including Gradient Boosting, Tree-based models, and Linear models.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, Imbalanced-learn
* **Algorithms:** XGBoost, CatBoost, LightGBM, Random Forest, AdaBoost, SVC, Logistic Regression

## 📈 Model Performance Comparison

The models were evaluated based on Accuracy, Precision, and Recall. Below are the results from the classifiers:

| Model | Accuracy | Precision | Recall |
| :--- | :---: | :---: | :---: |
| 🏆 **CatBoostClassifier** | 0.8665 | 0.7461 | 0.4860 |
| 🚀 **LGBMClassifier** | 0.8665 | 0.7316 | 0.5064 |
| ⚡ **XGBoostClassifier** | 0.8600 | 0.6865 | 0.5293 |
| 🛠️ **AdaBoostClassifier** | 0.8595 | 0.7205 | 0.4656 |
| 🌳 **DecisionTreeClassifier** | 0.8440 | 0.6695 | 0.4071 |
| 📍 **KNN** | 0.8295 | 0.5963 | 0.4097 |
| 📈 **Logistic Regression** | 0.8110 | 0.5524 | 0.2010 |

> **Note:** Models like RandomForest and ExtraTrees showed 0.0 recall in initial tests, indicating they struggled with the minority class (churners) before additional tuning or balancing.



## 🔍 Visual Insights
* **Age:** Customers between the ages of **40-60** show a significantly higher churn rate, suggesting mid-life transitions or changing financial needs.
* **Product Usage:** Customers with **3 or 4 products** have an extremely high probability of churning. This might indicate over-saturation or dissatisfaction with bundled services.
* **Geography:** **Germany** has a higher churn rate compared to France and Spain, suggesting region-specific market dynamics or competitor pressure.


---

## 👨‍💻 Author
**Erhan Er** 📧 [erhan.er7@std.yeditepe.edu.tr](mailto:erhan.er7@std.yeditepe.edu.tr)  
🎓 Yeditepe University
