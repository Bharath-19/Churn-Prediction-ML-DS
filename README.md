# Churn Prediction Using Machine Learning

This project focuses on predicting customer churn using various machine learning models, with an added business-facing Power BI dashboard for visual insights. The dataset is based on a real-world telecom provider and includes customer demographics, account information, and service usage patterns.

The goal was to not just build models, but to also understand **what factors drive churn**, and **how we can visualize risk** in a way that non-technical users can act on.

---

## 📁 Project Structure
```
+---data
|   |__ Telco-Customer-Churn.csv
|
+---notebooks
|   |__ Churn_prediction.ipynb
|
+---outputs
|   |__ churn_cleaned.csv
|   |__ Churn_prediction_BI_Final.pbix
|
+---Images
    |__ dashboard.png
    |__ roc_curve.png
```
## 🚀 Key Highlights

- 🔍 **Exploratory Data Analysis** using Seaborn and Matplotlib
- 🔄 **Data Preprocessing** including encoding, scaling, and null handling
- 📊 **ML Models**: Random Forest, SVM, XGBoost
- 📈 **Evaluation**: ROC-AUC, F1, confusion matrices
- 📊 **Power BI Dashboard**: Highlights churn risk, service patterns, and user segments

## 🔧 Tools & Libraries

- Python, Pandas, NumPy
- Scikit-learn, XGBoost, SHAP
- Seaborn, Matplotlib
- Power BI (for dashboard)
- Git/GitHub for version control

## 📈 Sample Results

| Model         | Accuracy | F1 Score | ROC-AUC |
|---------------|----------|----------|---------|
| Random Forest | 78%      | 0.55     | 0.823   |
| SVM           | 79%      | 0.55     | 0.80    |
| XGBoost       | 77%      | 0.55     | 0.822   |

## 📊 Power BI Dashboard Preview

The dashboard provides a business-friendly summary:
- Churn by tenure, gender, and contract type
- Service subscription trends
- Risk distribution across customer segments

---
## ▶️ How to Run

1. Clone the repository
2. Install dependencies:
```bash
pip install -r requirements.txt
