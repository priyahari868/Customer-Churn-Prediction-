# Customer-Churn-Prediction-
End-to-end Customer Churn Prediction system using Machine Learning to identify high-risk banking customers and provide actionable business insights.

# 🚀 Customer Churn Prediction (Banking Use Case)

## 🎯 Problem Statement
Customer churn is a major challenge in the banking sector. Retaining existing customers is more cost-effective than acquiring new ones.

This project aims to **predict which customers are likely to leave the bank** and identify the key factors influencing churn.

---

## 📊 Dataset
- Source: Kaggle – Churn Modelling Dataset
- Records: 10,000 customers
- Features include:
  - Credit Score
  - Age
  - Geography
  - Gender
  - Balance
  - Number of Products
  - Active Membership
  - Estimated Salary
- Target Variable:
  - `Exited` (1 = Churn, 0 = Retained)

---

## 🧰 Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Power BI (for dashboard)

---

## 🔧 Project Workflow

### 1. Data Preprocessing
- Removed irrelevant columns (CustomerId, Surname)
- Encoded categorical variables (Gender, Geography)
- Feature scaling applied to numerical columns
- No missing values found

---

### 2. Exploratory Data Analysis (EDA)
- Churn distribution analysis
- Correlation heatmap
- Feature vs churn comparison

📌 Key Observations:
- Inactive customers churn more
- Customers with low balance are more likely to leave
- Older customers show higher churn rate

---

### 3. Feature Engineering
- Created new features:
  - Balance per product
  - Customer activity score

---

### 4. Model Building

Models used:
- Logistic Regression
- Random Forest Classifier

---

### 5. Model Evaluation

Metrics used:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

📊 Random Forest performed better in identifying churn patterns.

---

### 6. Key Insights 💡

- Customers with **low balance + inactive status** are highly likely to churn
- Higher age group shows increased churn probability
- Engagement is a critical factor in retention

---

### 7. Business Recommendations 📈

- Provide personalized offers to low-balance customers
- Improve engagement for inactive users
- Introduce loyalty programs for long-term customers

---

### 8. Output Files

- `cleaned_churn_data.csv` → Processed dataset
- `high_risk_customers.csv` → Customers likely to churn

---

## 📊 Power BI Dashboard
Dashboard includes:
- Churn Rate KPI
- Customer Segmentation
- High-Risk Customer Identification

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
python main.py
