# 🏦 Customer Churn Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen?style=for-the-badge)

---

# 📌 Project Overview

This project predicts whether a customer will leave the bank (**Churn = 1**) or remain with the bank (**Churn = 0**) using Machine Learning.

The model is trained using customer information such as credit score, balance, age, salary, country, and account activity.

---

# 🎯 Objective

✔ Predict Customer Churn

✔ Improve Customer Retention

✔ Compare Customer Behaviour

✔ Build an Accurate ML Classification Model

---

# 📂 Dataset

| Feature | Description |
|---------|-------------|
| Credit Score | Customer Credit Score |
| Country | France / Germany / Spain |
| Gender | Male / Female |
| Age | Customer Age |
| Tenure | Years with Bank |
| Balance | Account Balance |
| Products Number | Number of Products |
| Credit Card | Yes / No |
| Active Member | Yes / No |
| Estimated Salary | Annual Salary |
| **Churn** | Target Variable |

---

# ⚙️ Machine Learning Workflow

```text
Dataset
   │
   ▼
Data Preprocessing
   │
   ▼
Label Encoding
   │
   ▼
Feature Scaling
   │
   ▼
Train-Test Split
   │
   ▼
Random Forest Model
   │
   ▼
Prediction
   │
   ▼
Model Evaluation
```

---

# 🛠 Technologies Used

| Tool | Purpose |
|------|---------|
| 🐍 Python | Programming Language |
| 📊 Pandas | Data Analysis |
| 🔢 NumPy | Numerical Computing |
| 🤖 Scikit-Learn | Machine Learning |
| 📈 Matplotlib | Visualization |
| 📉 Seaborn | Graphs |

---

# 📊 Model Used

✅ Random Forest Classifier

---

# 📈 Evaluation Metrics

- ✅ Accuracy Score
- ✅ Precision
- ✅ Recall
- ✅ F1-Score
- ✅ Confusion Matrix
- ✅ Classification Report

---

# 📊 Expected Accuracy

| Algorithm | Accuracy |
|------------|----------|
| Logistic Regression | 80% |
| Decision Tree | 82% |
| **Random Forest** | **86%** |

---

# 📁 Project Structure

```
Customer-Churn-Prediction
│
├── Churn_Modelling.csv
├── Customer_Churn_Prediction.ipynb
├── README.md
├── requirements.txt
└── images
```

---

# ▶️ Installation

```bash
git clone https://github.com/yourusername/Customer-Churn-Prediction.git
```

Install Packages

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Run Notebook

```bash
jupyter notebook
```

---

# 📷 Output

## Confusion Matrix

<img src="images/confusion_matrix.png" width="600">

---

## Feature Importance

<img src="images/feature_importance.png" width="700">

---

## Accuracy

```
Accuracy : 86%
```

---

# 🚀 Future Scope

- Hyperparameter Tuning
- XGBoost
- LightGBM
- Streamlit Deployment
- Flask API

---

# 👩‍💻 Author

**Mathan R**

🎓 BCA Student

🏫 Kamaraj College

📅 Year of Passing: 2027

---

# ⭐ If you like this project, don't forget to Star the repository.
