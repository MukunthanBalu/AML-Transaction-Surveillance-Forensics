# 🚨 Paper Trail: AML Behavioral Intelligence & Risk Scoring Suite

## 📌 Project Overview
This project simulates a high-stakes **Anti-Money Laundering (AML)** monitoring environment. I engineered a synthetic dataset of 5,000 banking transactions to inject specific financial crime patterns—**Structuring (Smurfing)** and **Layering**—and built a multi-layered Tableau dashboard to identify, score, and rank suspicious activity.

## 📊 Dashboard Previews

### Executive Overview
Focuses on high-level KPIs including a 8.0% Flag Rate and €3.60M in suspicious volume.
![Executive Dashboard](dashboard_executive.png)

### Forensic Detail
Deep dive into "Smurfing" patterns (clustering below €10k) and high-risk country corridors like Cyprus to Malta.
![Forensic Dashboard](dashboard_forensic.png)

## 🔍 Key Forensic Insights Surfaced
- **The "Smurfing" Signal:** Identified a massive cluster of transactions sitting between €9,000 - €9,999, specifically designed to evade the €10,000 mandatory reporting threshold.
- **High-Risk Corridors:** Surface-level analysis identified Cyprus → Malta as a primary corridor for layering attempts.
- **Risk Efficiency:** Isolated an **8.0% flag rate** across **€3.60M** in suspicious volume.
- **Suspect Prioritization:** Generated a "Top 25" list of individual transactions ranked by a multi-factor Risk Score (Average Score: **25.3**).

## 🛠️ Tech Stack & Methodology
- **Data Engineering:** Python (Pandas, NumPy) used to generate 5,000 records and inject anomalies.
- **Risk Scoring:** Developed a behavioral logic to assign risk scores based on transaction amount and frequency.
- **Analytics:** Statistical distribution analysis to catch "clustering" behavior.

## 📂 Repository Navigation
- [Python Data Script](aml_data_engineering.py) - The logic used to build the "Fake Bank."
- [Transaction Dataset](transaction_dataset.csv) - The raw CSV used for analysis.
- [Tableau Workbook](AML_Forensic_Suite.twbx) - The full interactive dashboard.
- [Project PDF](Paper_Trail_Project_Summary.pdf) - A printable summary of the suite.

---
**Author:** Mukunthan Balu | Data Analyst
**Date:** 2026
