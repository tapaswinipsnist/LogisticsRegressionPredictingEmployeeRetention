# 👩‍💼 Employee Retention – Logistic Regression Project

## 📌 Project Overview
This project focuses on developing a **Logistic Regression model** to analyze and predict binary outcomes.  
The assignment provides hands‑on experience with data preprocessing, feature engineering, model building, and evaluation.  
By applying logistic regression, the project aims to classify employee attrition and interpret the factors influencing retention.

Project is completed as art of IIITB course work. My contributions included EDA, Feature Engineering and Model evaluation.
---

## 🎯 Objectives
- Build and evaluate a **logistic regression model**.  
- Explore **data preprocessing techniques** and **feature selection**.  
- Understand logistic regression assumptions and implementation.  
- Apply **model evaluation and optimization strategies**.  
- Enhance predictive performance and interpretability.  

---

## 🛠️ Assignment Tasks
1. **Data Understanding** – Explore dataset structure and variables.  
2. **Data Cleaning** – Handle missing values, outliers, and inconsistencies.  
3. **Train‑Validation Split** – Divide data for training and evaluation.  
4. **EDA on Training Data** – Identify distributions, correlations, and patterns.  
5. **EDA on Validation Data (Optional)** – Validate findings.  
6. **Feature Engineering** – Encode categorical variables, scale numerical features.  
7. **Model Building** – Train logistic regression model.  
8. **Prediction & Model Evaluation** – Assess performance using accuracy, precision, recall, F1‑score, and ROC‑AUC.  

---

## 📑 Dataset Description
The dataset contains **74,610 rows and 24 columns**.  
It includes employee demographics, job‑related features, and attrition status.

| Column Name | Description |
|-------------|-------------|
| Employee ID | Unique identifier for each employee |
| Age | Employee age (18–60 years) |
| Gender | Gender of the employee |
| Years at Company | Tenure at the company |
| Monthly Income | Monthly salary in USD |
| Job Role | Department/role (Finance, Healthcare, Technology, Education, Media) |
| Work-Life Balance | Perceived balance (Poor, Below Average, Good, Excellent) |
| Job Satisfaction | Satisfaction level (Very Low, Low, Medium, High) |
| Performance Rating | Performance rating (Low, Below Average, Average, High) |
| Number of Promotions | Total promotions received |
| Overtime | Number of overtime hours |
| Distance from Home | Commute distance (miles) |
| Education Level | Highest education attained (High School → PhD) |
| Marital Status | Divorced, Married, Single |
| Number of Dependents | Number of dependents |
| Job Level | Entry, Mid, Senior |
| Company Size | Small, Medium, Large |
| Company Tenure (Months) | Total industry experience |
| Remote Work | Yes/No |
| Leadership Opportunities | Yes/No |
| Innovation Opportunities | Yes/No |
| Company Reputation | Very Poor, Poor, Good, Excellent |
| Employee Recognition | Very Low, Low, Medium, High |
| Attrition | Target variable – whether the employee left the company |

---

## Actual Insights
-- ➔ Sensitivity of the model turned out to be 0.89
-- ➔ Specificity of the model turned out to be 0.52
-- ➔ Precision of the model turned out to be 0.63
-- ➔ Recall of the model turned out to be 0.89

--CONFUSION MATRIX:
<img width="275" height="46" alt="image" src="https://github.com/user-attachments/assets/a393900b-10e9-4a91-b1c7-47050017d6ed" />

Analysis identified work-life balance, compensation, and career growth as the top three drivers of employee attrition. Based on these findings:
•	Employees with low work-life balance scores were significantly more likely to leave — organizations should consider flexible work policies and workload audits for high-risk departments.
•	Compensation dissatisfaction emerged as a strong attrition predictor — a structured salary benchmarking exercise every 6–12 months is recommended for roles flagged as high-risk.
•	Employees with stagnant career progression (3+ years in same role, no promotion) showed elevated churn probability — introducing clear promotion timelines and mentorship programs can reduce this risk.
•	The model can be used to proactively flag at-risk employees before they resign, enabling HR teams to intervene early with targeted retention measures.

  --**ROC Curve**
  <img width="597" height="457" alt="image" src="https://github.com/user-attachments/assets/1dc9479d-e200-409b-b31e-c638553be9d3" />
--**PRECISION RECALL Curve**
  <img width="576" height="447" alt="image" src="https://github.com/user-attachments/assets/59dd1a64-a41b-4ba1-affe-264d800e30b2" />

---

## 🧰 Tech Stack
- **Python** (Pandas, NumPy, Scikit‑learn, Matplotlib, Seaborn)  
- **Machine Learning:** Logistic Regression  
- **Data Source:** Public dataset (Kaggle)  

---
