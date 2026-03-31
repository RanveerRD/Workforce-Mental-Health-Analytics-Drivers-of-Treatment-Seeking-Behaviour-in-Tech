# 🧠 Workforce Mental Health Analytics — Drivers of Treatment-Seeking Behaviour in Tech

## 📊 Project Overview

This project analyses mental health trends within the tech workforce using survey data from the Open Sourcing Mental Illness (OSMI) initiative.

The objective is to identify the key factors influencing whether employees seek mental health treatment, helping organisations design more effective workplace wellbeing strategies.

---

## 🎯 Business Problem

Mental health challenges in the tech industry are often underreported, resulting in reduced productivity, increased absenteeism, and higher employee turnover.

Despite growing awareness, many organisations still lack clarity on:
- what drives employees to seek treatment,
- which workplace factors influence help-seeking behaviour, and
- how organisational policies impact mental health outcomes.

This project provides data-driven insights to support HR teams, people managers, and workplace wellbeing initiatives.

---

## 📊 Dataset

- **Source:** OSMI Mental Health in Tech Survey  
- **Size:** 1,259 records, 27 features  
- **Target Variable:** `treatment` (Yes/No)

### Key Features Analysed
- Age  
- Gender  
- Family history of mental illness  
- Employer-provided benefits  
- Care options availability  
- Workplace anonymity  
- Ease of taking leave  
- Work interference  

---

## 🛠 Tools & Technologies

- Python (Pandas, NumPy, Scikit-learn)
- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis (EDA)
- Data Visualisation (Seaborn, Matplotlib)
- Feature Engineering
- Classification Modelling

---

## 🚀 Key Takeaways

- Work interference is the strongest predictor of treatment-seeking behaviour  
- Access to mental health benefits significantly increases treatment uptake  
- Workplace anonymity and psychological safety influence willingness to seek help  
- Employees aged 21–30 show the highest treatment rates  
- Family history of mental illness strongly correlates with treatment behaviour  

---

## 🔍 Data Cleaning & Preparation

The dataset required several preprocessing steps before analysis:

- Missing values were handled using median imputation for Age and mode-based defaults for categorical variables  
- Unrealistic age values were corrected, and ages were grouped into meaningful ranges  
- Gender values were standardised from 50+ free-text entries into three broader categories  
- Categorical variables were label encoded for modelling  
- Post-cleaning checks confirmed zero null values across all features  

---

## 📊 Sample Visualisations

### 1. Age Distribution of Respondents

<img width="691" height="352" alt="570323679-404e03e5-0e84-4698-90d1-71ed5c49492e" src="https://github.com/user-attachments/assets/14f5f6ea-6d64-4df0-b544-a802f6a2c31b" />


**Insight:**  
The respondent base is concentrated heavily between ages 20 and 30, indicating that the dataset largely reflects a younger tech workforce. The right-skewed distribution suggests limited representation of older age groups.

---

### 2. Age Distribution by Treatment Status

<img width="691" height="352" alt="570323679-404e03e5-0e84-4698-90d1-71ed5c49492e" src="https://github.com/user-attachments/assets/d28e66fd-6d32-4043-ac8d-ac3ccbc54aea" />


**Insight:**  
Respondents who sought treatment are more concentrated in the 20–30 age range. This suggests that younger professionals may be more likely to seek support, potentially due to greater awareness and lower stigma around mental health.

---

## 📈 Key Findings

The analysis identified several factors strongly associated with treatment-seeking behaviour:

- **Work interference** emerged as the single strongest predictor  
- Employees with a **family history of mental illness** were more likely to seek treatment  
- **Employer-provided benefits and care options** were strongly associated with treatment uptake  
- **Workplace anonymity** influenced willingness to seek support  
- **Younger employees**, particularly those aged 21–30, showed higher treatment rates  
- **Gender** showed moderate association, with female respondents reporting higher treatment-seeking rates in this dataset  

---

## 💡 Business Recommendations

1. **Make mental health benefits visible, not just available**  
   Simply offering support is not enough; employees must clearly understand what services exist and how to access them.

2. **Build psychological safety and confidentiality**  
   Employees are more likely to seek treatment when they trust that disclosures will remain private.

3. **Target early-career employees with mental health programs**  
   Younger workers appear more receptive to mental health support and awareness initiatives.

4. **Monitor work interference as an early warning signal**  
   Self-reported work interference can help identify employees who may need support before issues escalate.

---

## 🤖 Modelling Summary

To validate the patterns identified during exploratory analysis, four classification models were trained and evaluated:

| Model | Test Accuracy |
|------|-------------|
| Random Forest | 81.2% |
| Decision Tree | 80.6% |
| Support Vector Machine | 77.5% |
| K-Nearest Neighbors | 75.6% |

**Random Forest** achieved the highest performance, with work interference, family history, and benefits access consistently appearing as the most influential features.

These models were used to support and validate analytical findings rather than serve as deployment-ready solutions.

---

## 📁 Repository Contents

- `Psychological.ipynb` — complete analysis notebook  
- `survey.csv` — source dataset  
- `environment.yml` — environment setup file  
- `age_distribution.png` — age distribution chart  
- `treatment_by_age.png` — treatment status age comparison chart  

---

## 🧾 Final Insight

This analysis highlights that the effectiveness of workplace mental health support depends not only on the existence of benefits, but also on visibility, trust, accessibility, and workplace culture.

The results suggest a clear gap between support availability and support utilisation — one that organisations can address through better communication, confidentiality, and proactive wellbeing strategies.

---

## 👤 Author

**Ranveer Reddy Deshmukh Pingili**  
Master of Business Analytics (Distinction) — University of Wollongong


