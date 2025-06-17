# HR Attrition Analysis Dashboard 🔍

## 📌 Project Overview

This project provides a comprehensive analysis of employee attrition using Python (data preprocessing + machine learning) and Power BI (interactive dashboard). The goal is to identify key drivers of attrition, predict future attrition risk, and present actionable insights through clear visuals.

---

## 🛠️ Tools & Technologies
- **Python (Pandas, Scikit-learn, Matplotlib, Seaborn)**
- **Machine Learning (Logistic Regression, Random Forest)**
- **Power BI (Data Modeling, Slicers, KPIs, Charts)**

---

## 📂 Project Structure

### 1. `HR Attrition Insights Dashboard.ipynb` (Python)
- Data cleaning & feature engineering
- Encoding categorical variables
- Training Logistic Regression and Random Forest models
- Evaluating performance (Accuracy, Recall, Confusion Matrix)
- Exporting risk scores for Power BI visualization

### 2. **Power BI Dashboard**
Key Components:
- **Slicer:** Filter by department
- **TreeMap:** Attrition count by gender
- **KPI Cards:** Average income, total attrition
- **Pie Chart:** Attrition by department
- **Line Chart:** Attrition trend by age
- **Matrix Table:** Detailed employee-level job info
- **Risk Analysis:** Visualizing `Attrition_Risk_Score` from ML

---

## 📊 Machine Learning Summary

### ✅ Logistic Regression
- Accuracy: **86.4%**
- Recall for Attrition: **36%**
- ✔️ Interpretable and better at identifying actual attrition cases

### ✅ Random Forest Classifier
- Accuracy: **87.4%**
- Recall for Attrition: **5%**
- ⚠️ Higher overall accuracy but underperformed on identifying minority class due to imbalance

👉 **Conclusion:** Although Random Forest had higher overall accuracy, Logistic Regression did better at identifying attrition cases. For simplicity and interpretability, we'll use Logistic Regression for insights and business recommendations.

---

## 📈 Key Insights

- Attrition is highest in **Sales Executive** and **Research Scientist** roles
- Younger employees (aged 25–35) have a higher attrition rate
- Department-wise, **Sales** shows the most exits
- Female employees show slightly higher attrition in certain roles
- Risk scores help identify potential future attrition for proactive HR action

---

## 🧠 Author
**Hassan**  
Machine Learning & BI Enthusiast

---

## 📎 Sample Screenshots
*(Insert Power BI dashboard image here)*

---
