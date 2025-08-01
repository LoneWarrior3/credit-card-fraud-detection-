# 💳 Credit Card Fraud Detection using Classification & Regression

This project is a comprehensive machine learning solution to identify and analyze fraudulent credit card transactions. It integrates both **classification** to detect whether a transaction is fraudulent, and **regression** to predict risk levels associated with the fraud.

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

bash
Copy
Edit
cd credit-card-fraud-detection
Install required dependencies

bash
Copy
Edit
pip install -r requirements.txt
Launch the notebook

bash
Copy
Edit
jupyter notebook credit_card_fraud_detection.ipynb
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
You can install them using:

bash
Copy
Edit
pip install -r requirements.txt
📌 Dataset
File: application_data.csv

Make sure it is in the same directory as the notebook.

(Note: Due to privacy and size, dataset is not included. Use any synthetic or anonymized credit card transaction dataset.)

📈 Exploratory Data Analysis
Handled class imbalance using techniques like SMOTE

Visualized fraud vs. non-fraud patterns

Checked correlations and feature importances

🙋‍♂️ Author
Shiva Kumar Uppara
🎓 CSE Undergrad | Data Science & ML Enthusiast
📫 Email: [your-email@example.com]
🔗 GitHub: https://github.com/your-username

📃 License
This project is licensed under the MIT License. Feel free to use, modify, and share.

vbnet
Copy
Edit

Let me know if you want a `.pdf` version or if you're submitting this somewhere and want a more
