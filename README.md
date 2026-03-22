# 🏥 Hospital Readmission Risk Analysis
### 📊 Turning 30,000 patient records into actionable hospital insights

![Python](https://img.shields.io/badge/Python-3.10-blue) ![pandas](https://img.shields.io/badge/pandas-EDA-green) ![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 🎯 Why This Project?
Hospitals in the US lose **millions of dollars** every year when patients are readmitted within 30 days of discharge. As a data analyst, I wanted to answer one simple but powerful question:

> 💬 **"Which patients are most likely to come back - and what should the hospital do about it?"**

Healthcare DA roles are growing **31% year over year** 🚀 and readmission analysis is at the core of hospital operations, insurance analytics, and clinical decision-making.

---

## 🔍 What I Did
Analyzed **30,000 real patient records** to uncover which factors actually predict 30-day hospital readmission.

| Step | What I did |
|------|-----------|
| 🧹 Clean | Split blood pressure into systolic & diastolic, encoded Yes/No columns |
| 🔎 Explore | Used shape, info, describe, isnull to understand the data |
| 📊 Visualize | Built 4 charts across pie, bar and line chart types |
| 📝 Report | Wrote a 1-page analyst memo for hospital administration |

---

## 💡 Key Findings

- 🔴 **Discharge destination is the #1 risk factor** - Nursing Facility & Rehab patients readmitted at nearly 40% higher rates than Home patients
- 🟡 **Age does NOT predict readmission** - all age groups sit at ~12%
- 🟡 **Length of stay does NOT predict readmission** - flat trend across 1-10 days
- 🟢 **Overall readmission rate is 12.2%** across 30,000 patients

---

## ✅ Recommendation
> Implement a **dedicated 7-day post-discharge follow-up program** for patients discharged to Nursing Facilities and Rehab centers. This single intervention targets the highest risk group and has the most potential to cut costs. 💰

---

## 🛠️ Tools Used
| Tool | Purpose |
|------|---------|
| 🐍 Python | Core analysis language |
| 🐼 pandas | Data cleaning & EDA |
| 📈 matplotlib & seaborn | Data visualization |
| ☁️ Google Colab | Development environment |

---

## 📁 Files in This Repo
| File | Description |
|------|-------------|
| 📓 `hospital_readmission_analysis.ipynb` | Full analysis notebook |
| 📂 `hospital_readmissions_30k.csv` | Dataset — 30,000 patient records |
| 📄 `analyst_memo.pdf` | 1-page findings report |

---

## 📌 Dataset
30,000 patient records including age, gender, blood pressure, cholesterol, BMI, diabetes, hypertension, medication count, length of stay and discharge destination.

---

*⚡ Project completed as part of a 7-day data analytics sprint - Spring Break 2026*
*👩‍💻 Built to demonstrate real-world healthcare analytics skills*
