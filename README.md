# UIDAI-DATA-HACKATHON-2026

# 🆔 Aadhaar as a Living Identity System

## 🔍 Overview
Aadhaar is often viewed as a one-time identity document. In reality, it continuously evolves as individuals move, age, and experience life events.  
This project analyses Aadhaar **enrolment**, **demographic updates**, and **biometric updates** together to understand Aadhaar as a **living identity system**, not a static record.

The focus is on extracting **policy-relevant insights** from UIDAI-provided datasets while respecting privacy and data integrity.

---

## 🎯 Objective
- Identify patterns, trends, and anomalies in Aadhaar enrolment and update behaviour  
- Understand identity interaction across **age, geography, and time**  
- Detect signals related to **delayed inclusion, mobility, operational stress, and access inequality**  
- Demonstrate how Aadhaar data can support informed planning and system improvement  

---

## 📂 Datasets Used
All datasets are **aggregated and provided by UIDAI**.

- 📝 **Enrolment Data** — New Aadhaar enrolments by age groups (0–5, 5–17, 18+)  
- 🧾 **Demographic Update Data** — Updates to demographic attributes  
- 🔐 **Biometric Update Data** — Biometric refresh activity (5–17 and 18+)  

Multiple CSV files per dataset were merged and analysed consistently.

---

## 🧪 Methodology
- Merged and cleaned raw CSV files with robust date parsing  
- Normalized state and district names for geographic consistency  
- Engineered features such as update intensity, age-based ratios, volatility, and spatial concentration  
- Applied:
  - **Univariate analysis** — distribution and intensity  
  - **Bivariate analysis** — age–geography relationships  
  - **Trivariate analysis** — age × geography × time interactions across datasets  

---

## 📊 Key Insights
- Aadhaar interactions occur in **episodic spikes**, not uniform patterns  
- Adult late enrolment highlights **delayed identity inclusion** in select regions  
- Demographic and biometric updates are **adult-dominated**, reflecting reactive identity maintenance  
- Pincode-level concentration indicates **persistent access inequality**  
- Delayed enrolment correlates with higher downstream update and biometric stress  

---

## 🔗 Cross-Dataset Analysis
By linking enrolment, demographic, and biometric datasets, the analysis shows that identity behaviour across Aadhaar stages is **interconnected and cumulative**, with early patterns propagating into later lifecycle stages.

---

## 🛠️ Code Structure
- `enrollment.ipynb` — Enrolment patterns and volatility analysis  
- `demographic.ipynb` — Demographic update intensity and age-based behaviour  
- `biometric.ipynb` — Biometric update stress analysis  
- `aadhar_cross_dataset_synthesis.ipynb` — Cross-dataset and trivariate analysis  

---

## 📈 Visualisation Approach
Visualisations are **purpose-driven** and used strictly to support analytical insights. The emphasis is on interpretability, reproducibility, and governance relevance rather than visual complexity.

---

## 🌍 Impact
The project demonstrates how aggregated Aadhaar data can be responsibly used as **decision-support intelligence** for outreach planning, infrastructure readiness, and inclusive governance.

---

## 🔒 Data Use & Privacy
Only UIDAI-provided, aggregated datasets are used. No personal or identifiable information is accessed or inferred.

---

## 👥 Contributors
- **Ankit Sarkar**  
- **Aayushmaan Chakraborty**
