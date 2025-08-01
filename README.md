# 💳 Credit Card Fraud Detection using Classification & Regression

This project is a comprehensive machine learning solution to identify and analyze fraudulent credit card transactions. It integrates both **classification** to detect whether a transaction is fraudulent, and **regression** to predict risk levels associated with the fraud.

---
## 📊 Dataset

The dataset used is `Application_data.csv`, which includes transaction records with features like transaction amount, location, device type, etc. The label indicates whether the transaction was legitimate (0) or fraudulent (1).

> **Note:** Due to privacy and security reasons, the dataset is not publicly available in this repository. If you are interested in the data, please contact the author directly or use similar open datasets like those from [Kaggle](https://www.kaggle.com).

---

## 🎯 Objectives

- Understand and clean the dataset.
- Explore patterns that distinguish fraud from legitimate transactions.
- Train and evaluate classification and regression models.
- Optimize model performance using tuning techniques.
- Compare model outputs and choose the best one.

---

## 🧠 Techniques Used

- **Exploratory Data Analysis (EDA)** using `seaborn`, `matplotlib`
- **Feature Engineering** (e.g., encoding, scaling)
- **Modeling** using:
  - Logistic Regression
  - Random Forest Classifier
  - XGBoost
  - Support Vector Machine (SVM)
  - Linear & Ridge Regression for fraud scoring
- **Performance Evaluation** with:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - Confusion Matrix

---
## 📌 Project Overview

- **Goal**: Detect fraudulent transactions and assess the level of fraud risk.
- **Techniques Used**: Supervised learning – Classification & Regression
- **Model Types**: Logistic Regression, Random Forest, XGBoost, Linear Regression

---

## 📁 Files in this Repository

| File                             | Description                                              |
|----------------------------------|----------------------------------------------------------|
| `credit_card_fraud_detection.ipynb` | Main Jupyter notebook with preprocessing, modeling, and evaluation |
| `requirements.txt`              | Python dependencies for running the notebook             |
| `README.md`                     | Overview and instructions                                |

---

## 📊 Model Performance (Classification)

| Metric         | Value     |
|----------------|-----------|
| Accuracy       | 0.9981    |
| Precision      | 0.9969    |
| Recall         | 0.9994    |
| F1-Score       | 0.9982    |
| Confusion Matrix | `[[3867, 12], [2, 3854]]` |

---

## ⚙️ How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/credit-card-fraud-detection.git
Navigate to the project folder


🧠 Machine Learning Approach
Classification:

Models used: Logistic Regression, Random Forest, XGBoost

Output: Fraud (1) or Not Fraud (0)

Regression:

Predicts severity or financial impact of a fraud

Models used: Linear Regression

📦 Requirements
Here are the main libraries used in this project:

nginx
Copy
Edit
pandas
numpy
scikit-learn
matplotlib
seaborn
xgboost
jupyter

🙋‍♂️ Author
Shiva Kumar Uppara
🎓 CSE Undergrad | Data Science & ML Enthusiast
📫 Email: [u.shivakumar3333@gmail.com]
🔗 GitHub: https://github.com/LoneWarrior3


