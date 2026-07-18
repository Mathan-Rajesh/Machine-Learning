# Customer Churn Prediction using Machine Learning

## 📌 Project Overview
This project aims to predict whether a bank customer will leave the bank (churn) or continue using its services based on customer information such as credit score, age, balance, number of products, and account activity.

Machine Learning classification algorithms are used to build a predictive model that helps banks identify customers who are likely to leave, enabling them to improve customer retention strategies.

---

## 📂 Dataset Information

**Dataset Name:** Customer Churn Prediction Dataset

### Features

| Column | Description |
|---------|-------------|
| customer_id | Unique customer ID |
| credit_score | Customer's credit score |
| country | Customer's country |
| gender | Male/Female |
| age | Customer's age |
| tenure | Years with the bank |
| balance | Bank account balance |
| products_number | Number of bank products used |
| credit_card | Has credit card (1 = Yes, 0 = No) |
| active_member | Active member (1 = Yes, 0 = No) |
| estimated_salary | Estimated yearly salary |
| churn | Target variable (1 = Customer leaves, 0 = Customer stays) |

---

## 🎯 Objective

Develop a Machine Learning model that predicts whether a customer will churn based on historical customer data.

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📋 Machine Learning Workflow

### Step 1
Import required libraries.

### Step 2
Load the dataset.

### Step 3
Perform Exploratory Data Analysis (EDA).

- Check dataset information
- Check missing values
- View summary statistics

### Step 4
Data Preprocessing

- Remove unnecessary columns
- Encode categorical variables
- Feature scaling

### Step 5
Split the dataset

- Training Set (80%)
- Testing Set (20%)

### Step 6
Train the Machine Learning model

Algorithm Used:

- Random Forest Classifier

### Step 7
Predict customer churn.

### Step 8
Evaluate model performance.

---

## 📊 Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Classification Report
- Precision
- Recall
- F1-Score

---

## 📈 Feature Importance

The Random Forest model identifies the most influential features affecting customer churn, such as:

- Age
- Balance
- Credit Score
- Active Member
- Number of Products
- Estimated Salary

---

## 📁 Project Structure

```
Customer-Churn-Prediction/
│
├── Churn_Modelling.csv
├── Customer_Churn_Prediction.ipynb
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

1. Download the dataset.
2. Open the Jupyter Notebook.
3. Install the required libraries.

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

4. Run all notebook cells.
5. View the model accuracy and evaluation metrics.

---

## 📌 Model Used

**Random Forest Classifier**

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

---

## 🎯 Expected Output

- Predict whether a customer will churn.
- Display prediction accuracy.
- Generate confusion matrix.
- Display classification report.
- Show feature importance.

---

## 📊 Expected Accuracy

| Model | Accuracy |
|---------|----------|
| Logistic Regression | 80–82% |
| Decision Tree | 79–84% |
| Random Forest | 84–88% |
| Gradient Boosting | 85–89% |

---

## 🚀 Future Enhancements

- Hyperparameter tuning using GridSearchCV
- Deploy the model using Flask or Streamlit
- Compare with XGBoost and LightGBM
- Build an interactive dashboard for predictions

---

## 👩‍💻 Author

**Mathan R**

BCA – Kamaraj College

Year of Passing: 2027

---

## 📄 License

This project is developed for educational and academic purposes.
