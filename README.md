# Strategic-Workforce-Retention
Workforce retention analysis leveraging Python &amp; Power BI to reduce a 16.1% attrition rate. Identifies root causes of turnover and targets high-risk employees through an interactive executive dashboard.

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

## Project Overview
High employee turnover poses a significant financial and operational risk to organizations. This project utilizes the **IBM HR Analytics dataset** to identify key churn drivers, visualize workforce demographics, and implement a **"Flight Risk" predictive flag** to help HR proactively retain talent.

The project demonstrates an **end-to-end data workflow**: from data cleaning and feature engineering in Python, to UI design in Figma, and interactive storytelling in Power BI.

---

## FILES INCLUDED

```text
├── 📁 Assets/               
│   ├── Dashboard_Page1_Overview.png        # Screenshot of the Overview Page
│   └── Dashboard_Page2_Details.png         # Screenshot of the Action Page
│
├── 📁 Datasets/
│   ├── HR_Analytics_Raw.csv                # Original Dataset (Before Cleaning)
│   └── HR_Analytics_Cleaned.csv            # Processed Dataset (After Python)
│
├── 📁 Notebooks/
│   └── Data_Cleaning_Feature_Engineering.ipynb  # Jupyter Notebook (Pandas code)
│
├── 📁 Reports/
│   └── Strategic_Retention_Case_Study.pdf  # Detailed Business Analysis & Insights Report
│
└── README.md
```

---

# The Business Problem

**Goal:** Reduce recruitment costs and improve employee retention.

The HR team lacked visibility into:

### 🔹 Who is leaving?
Demographics, tenure, departments, job roles.

### 🔹 Why are they leaving?
Salary stagnation, overtime, job dissatisfaction.

### 🔹 Who is at risk?
Predictive modeling to create a **“Flight Risk”** flag.

---

# Key Insights (From the PDF Report)

### 1. Overtime Burnout  
Employees working overtime with **low satisfaction** are **3× more likely** to leave.

### 2. Role Vulnerability  
Sales Representatives & Lab Technicians make up **~40% of all attrition**.

### 3. The “Year 2” Cliff  
Attrition spikes significantly between **1–2 years**, signaling onboarding or early development issues.

### 4. Income Stagnation  
Employees with **5+ years tenure** and **no recent promotion** show high risk of churn.

---
# Conclusion

The 16.1% attrition rate is driven by burnout and role-specific stress. The "Flight Risk" model allows us to predict departures, enabling proactive intervention. Focusing on the 127 high-risk employees could reduce attrition by 4–5% next year, saving recruitment costs and retaining critical knowledge.

---
# Dashboard Visualization

### Executive Overview Dashboard
![Executive Overview Dashboard](https://github.com/AltagiAbdallah/Strategic-Workforce-Retention/blob/main/Dashboard_Page1_Overview.png?raw=true)

### Employee Details & Action
![Employee Details & Action](https://github.com/AltagiAbdallah/Strategic-Workforce-Retention/blob/main/Dashboard_Page2_Details.png?raw=true)


