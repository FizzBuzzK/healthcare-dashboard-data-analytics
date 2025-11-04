# Healthcare Diabetes Readmission Dashboard

**Data analytics project combining Python (pandas, matplotlib, seaborn) and Power BI to explore hospital readmission trends among 130-US Hospitals with 100k+ encounters.**


---

## Dashboard Preview

| Page | Screenshot |
|------|-------------|
| Overview | ![Overview Page](images/overview_page.png) |
| Admissions Insights | ![Admissions Insights](images/admissions_page.png) |
| Demographics Insights | ![Demographics Insights](images/demographics_page.png) |
| Medications Insights | ![Medications Insights](images/medications_page.png) |

## Project Overview

The goal is to uncover **insights into hospital readmissions** among diabetic patients by exploring relationships between demographics, admissions, and medication patterns.


This project demonstrates an **end-to-end healthcare analytics workflow** — from **massive data wrangling (100k+ observations and approximately 50 features) with Pandas** to **interactive visualization in Power BI** — using the **Diabetes 130-US Hospitals** dataset from [Kaggle](https://www.kaggle.com/datasets/brandao/diabetes).


The project analyzes the **Diabetes 130-US Hospitals dataset** from Kaggle to uncover key patterns in **readmission rates**, **patient demographics**, and **treatment insights**.  
The final outcome is an **interactive Power BI dashboard** that allows healthcare stakeholders to explore insights that can improve patient outcomes and reduce readmissions.

---

## Tech Stack

| Tool | Purpose |
|------|----------|
| **Python (pandas, matplotlib)** | Data cleaning, wrangling, and exploratory data analysis |
| **Power BI** | Interactive visualization and dashboard creation |
| **GitHub** | Version control and portfolio showcase |

---

## Data Cleaning & Preparation

**Files Used**
- `diabetic_data.csv` (original Kaggle dataset)
- `IDs_mapping.csv` (for decoding ID columns)

**Data Wrangling (pandas):**
1. Cleaned and merged ID mapping tables.
2. Dropped irrelevant columns and handled missing values.
3. Encoded categorical values and computed new columns like `age_median`.
4. Created clean datasets for Power BI modeling.

**Output Files:**
- `diabetic_data_final.csv`
- `admission_type_id.csv`
- `discharge_disposition_id.csv`
- `admission_source_id.csv`

---

## Exploratory Data Analysis (Python)

Visualizations created with `matplotlib`:
- **Readmission Status Distribution**
- **Readmission by Gender**
- **Readmission Rate by Age Group**
- **Average Length of Stay by Readmission**
- **Top 10 Medical Specialties**
- **Readmission Rates by Medical Specialty**

_All EDA scripts are included in `notebooks/data_cleaning_eda.ipynb`._

---

## Power BI Dashboard

The dashboard was designed in four pages to simulate a **real-world healthcare analytics report**.

### **Page 1 — Executive Overview**
- KPIs: Total Encounters, Total Patients, Readmission Rate, Average Length of Stay  
- Slicers: Age Group, Gender, Race, Insulin, Diabetes Medication  
- Visuals:
  - Grouped Column Chart: Readmission Rate by Medical Specialty  
  - Grouped Column Chart: Count of Insulin by Gender  
  - Donut Chart: Avg. Length of Stay by Age Group  

### **Page 2 — Admissions Insights**
- Column Charts:
  - Readmission Rate by Admission Source  
  - Readmission Rate by Age Group  
  - Readmission Rate by Gender  
  - Readmission Rate by Race  
- Matrix Table: Admission Source Type, Encounters, Readmission Rate  

### **Page 3 — Demographics Insights**
- Donut Charts: Patients by Age Group, Gender, Race  
- 100% Stacked Bar Chart: Gender Ratio by Medical Specialty  

### **Page 4 — Medications Insights**
- Column Charts: Readmission Rate by Insulin, Diabetic Med Change  
- Scatter Plot: Average Medications vs. Readmission Rate by Age Group  


---

## Key Insights

- Patients aged **60–79** show the **highest readmission rates**.  
- **Females** have slightly higher readmission ratios than males.  
- Readmissions are more common in patients with **longer hospital stays** and **multiple diagnoses**.  
- Medical specialties such as **Internal Medicine** and **Cardiology** show the **highest recurrence**.


---

## Dataset Source

[Kaggle — Diabetes 130-US hospitals for years 1999–2008 Data Set](https://www.kaggle.com/datasets/uciml/diabetes-130-us-hospitals-for-years-19992008)
[UCI Machine Learning Repository  — Diabetes 130-US Hospitals for Years 1999-2008](https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008)

---

## Author

**Euikyun. Ko.**  
Data Analyst / Developer  
📧 [eko004@fiu.edu]
📧 [koek0507@gmail.com] 
🌐 [www.linkedin.com/in/euikyun-ko]

---

