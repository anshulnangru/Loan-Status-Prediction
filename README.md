# 🏦 Loan Status Prediction using Machine Learning

Predict whether a loan application will be approved or rejected using Machine Learning based on applicant details such as income, credit history, education, employment status, and loan amount.

## 📌 Overview

Financial institutions receive thousands of loan applications every day. Manually evaluating each application is time-consuming and prone to inconsistencies.

This project uses Machine Learning classification algorithms to automate the loan approval process by predicting the loan status of an applicant based on historical loan data.

The model analyzes various applicant attributes and determines whether the loan is likely to be approved.

---

## 🚀 Features

- Data Cleaning & Preprocessing
- Handling Missing Values
- Categorical Feature Encoding
- Exploratory Data Analysis (EDA)
- Model Training & Evaluation
- Loan Approval Prediction System
- Classification using Machine Learning
- Performance Comparison of Models

---

## 📊 Dataset Information

The dataset contains applicant details such as:

| Feature | Description |
|----------|-------------|
| Loan_ID | Unique Loan Identifier |
| Gender | Male / Female |
| Married | Marital Status |
| Dependents | Number of Dependents |
| Education | Graduate / Not Graduate |
| Self_Employed | Employment Status |
| ApplicantIncome | Applicant Income |
| CoapplicantIncome | Co-applicant Income |
| LoanAmount | Loan Amount Requested |
| Loan_Amount_Term | Loan Repayment Term |
| Credit_History | Credit History Record |
| Property_Area | Urban / Semi-Urban / Rural |
| Loan_Status | Target Variable |

---

## 🛠️ Tech Stack

### Programming Language
- Python

### Libraries Used
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn

### Development Environment
- Jupyter Notebook

---

## ⚙️ Project Workflow

### 1️⃣ Data Collection
Collected historical loan application data containing applicant and loan information.

### 2️⃣ Data Preprocessing
- Handling missing values
- Encoding categorical variables
- Data cleaning
- Feature selection

### 3️⃣ Exploratory Data Analysis
Analyzed:
- Income distribution
- Credit history impact
- Loan approval trends
- Property area effects

### 4️⃣ Model Building
Applied Machine Learning classification techniques to predict loan approval status.

### 5️⃣ Model Evaluation
Evaluated model performance using:
- Accuracy Score
- Confusion Matrix
- Classification Metrics

### 6️⃣ Prediction System
Created a predictive system capable of classifying new loan applications.

---

## 📈 Machine Learning Pipeline

```text
Raw Dataset
      ↓
Data Cleaning
      ↓
Feature Engineering
      ↓
Encoding
      ↓
Train-Test Split
      ↓
Model Training
      ↓
Evaluation
      ↓
Loan Status Prediction
```

---

## 📂 Project Structure

```text
Loan-Status-Prediction/
│
├── Loan_Status_Prediction.ipynb
├── loan_data.csv
├── README.md
│
├── models/
│   └── trained_model.pkl
│
├── outputs/
│   ├── graphs
│   └── evaluation_results
│
└── requirements.txt
```

---

## 📊 Sample Prediction

### Input

```python
{
    "Gender": "Male",
    "Married": "Yes",
    "ApplicantIncome": 5000,
    "LoanAmount": 150,
    "Credit_History": 1
}
```

### Output

```text
Loan Approved ✅
```

---

## 🎯 Business Impact

This system can help financial institutions:

- Reduce manual verification effort
- Improve loan processing speed
- Maintain consistent decision-making
- Assist loan officers in eligibility assessment

---

## 📚 Key Learnings

- Data preprocessing techniques
- Feature engineering
- Classification algorithms
- Model evaluation
- Financial data analysis
- End-to-End Machine Learning workflow

---

## 🔮 Future Improvements

- Deploy using Streamlit or Flask
- Hyperparameter tuning
- Advanced ensemble models
- Real-time loan approval dashboard
- Cloud deployment using AWS

---

## 👨‍💻 Author

**Anshul Nangru**

- GitHub: https://github.com/anshulnangru
- LinkedIn: Anshul Nangru

---

## ⭐ If you found this project useful, consider giving it a star!
