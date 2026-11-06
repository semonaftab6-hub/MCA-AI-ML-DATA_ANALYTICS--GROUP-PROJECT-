<div align="center">

# 🏥 Healthcare Analytics & Patient Intelligence
### *Multi-Platform Business Intelligence & Data Pipeline Suite*

[![MCA AI & ML](https://img.shields.io/badge/Degree-MCA%20AI%20%26%20ML-blueviolet?style=for-the-badge)](https://github.com/)
[![Invertis University](https://img.shields.io/badge/University-Invertis%20Bareilly-blue?style=for-the-badge)](https://github.com/)
[![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)](https://github.com/)
[![Patients](https://img.shields.io/badge/Records-1%2C000%20Patients-informational?style=for-the-badge)](https://github.com/)
[![Revenue](https://img.shields.io/badge/Total%20Revenue-%E2%8b%b939.42%20Cr-orange?style=for-the-badge)](https://github.com/)

</div>

---

## 📖 About the Project

This repository contains an end-to-end data analytics and business intelligence project developed as part of the **Master of Computer Applications (MCA) in Artificial Intelligence & Machine Learning** curriculum at **Invertis University, Bareilly**[cite: 1, 14]. 

The project transforms raw, synthetic hospital records into actionable visual dashboards across **Microsoft Excel, Power BI, and Python (Jupyter Notebook)**, tracking **1,000 patient records** from October 2025 to October 2026[cite: 3, 4, 11].

---

## 📊 Executive Summary & Key Performance Indicators

* 🏥 **Total Patients Tracked:** 1,000 (Primary Key linked via `Patient ID` `P0001` - `P1000`)[cite: 3, 4]
* 💰 **Total Revenue Generated:** ₹39.42 Cr[cite: 4]
* 💵 **Average Treatment Cost:** ₹3.94 Lakh per patient[cite: 4]
* ⏱️ **Average Length of Stay:** 15.1 days[cite: 4]
* 🚨 **Critical Case Load:** 157 patients (15.7%)[cite: 10, 12]
* 🩺 **Domain Coverage:** 10 Diseases, 6 Specialist Doctors, 3 Ward Types, 8 Cities[cite: 3, 4]

---

## 📂 Modular Dataset Architecture

The project data is normalized into five connected relational entities:

1. **`1_Hospital_Operation.xlsx`**: Tracks admissions, discharges, length of stay, ward allocation (`General`, `Private`, `ICU`), and clinical status (`Normal`, `Critical`, `Observation`)[cite: 3, 23].
2. **`2_Patient_Analytics.xlsx`**: Analyzes demographic distributions, exact age metrics, age cohorts (`0-20`, `21-40`, `41-60`, `60+`), gender split, and city-wise trends[cite: 3, 4, 23].
3. **`3_Disease_Analytics.xlsx`**: Maps disease prevalence across 10 major categories and correlates severity rates[cite: 3, 23].
4. **`4_Doctor_Performance.xlsx`**: Evaluates patient load, specialist attribution, and revenue generation across 6 doctors[cite: 3, 23].
5. **`5_Cost_and_Revenue.xlsx`**: Captures financial transaction records, itemized treatment cost spreads, and payment modes (`Insurance`, `Cash`, `UPI`, `Credit Card`)[cite: 3, 23].

---

## 💡 Key Findings & Strategic Insights

* 🔴 **ICU Revenue Concentration:** While the ICU accommodates only **12.9% of patients** (129 admissions), it drives **63.9% of total hospital revenue** (₹25.20 Cr) with an average bill of ₹19.53 Lakh compared to ₹1.14 Lakh in General wards[cite: 5, 29].
* 🦠 **Disease Burden:** **Viral Fever** is the most frequent diagnosis (182 patients, generating ₹7.93 Cr), whereas **Dengue** exhibits the highest critical risk ratio at **19.3%**[cite: 7, 13].
* 💳 **Payment Preferences:** **Insurance** is the primary financial settlement mode, covering **38.6%** (₹15.20 Cr) of total earnings, followed by Cash (28.4%) and UPI (21.6%)[cite: 9, 29].
* 👨‍⚕️ **Consultant Performance:** **Dr. Singh (Pulmonology)** leads revenue generation at **₹8.08 Cr** (avg. ₹4.87 Lakh/patient), while **Dr. Verma (Physician)** handles the highest patient volume (**189 patients**)[cite: 8, 28].
* 👥 **Demographic Spread:** Senior citizens aged **60+** form the largest patient group at **32%** (320 individuals)[cite: 6, 13].

---

## 🛠️ Technology Stack & Tools

* **Microsoft Excel:** Power Query, Pivot Tables, interactive slicers, and KPI visual cards[cite: 3, 18].
* **Power BI:** Multi-page dynamic BI report suite with custom measure metrics[cite: 3, 11].
* **Python (Jupyter Notebook):** Automated preprocessing, merging pipelines, and visualizations via **Pandas** and **Matplotlib**[cite: 3, 11, 24].

---

## 📁 Repository Directory Structure

```text
├── Excel/                  # Individual topic workbooks & Major Excel Dashboard
├── jupyter notebooks/      # Python scripts & automated analytics notebook
├── powerbi/                # Power BI interactive BI dashboard file (.pbix)
├── report and ppt/         # Comprehensive project report (PDF) & presentation slides
└── README.md
