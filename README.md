# 🏥 Papollo Hospitals - Leads Flow Dashboard

This Power BI project visualizes patient flow and hospital performance metrics for **Papollo Hospitals**. The dashboard provides actionable insights on bed occupancy, patient diagnosis trends, doctor feedback, billing, and insurance impact. It is designed for hospital management teams to monitor operational efficiency and improve patient experience.

---

<img width="1156" height="713" alt="Screenshot 2025-11-07 211649" src="https://github.com/user-attachments/assets/861cca34-e12b-4aea-be0f-2c3448b64d97" />


## 📊 Key Dashboard Components

### 1. **Patient Timeline Overview**
| Metric | Description |
|-------|-------------|
| **Admit Date** | Date when the patient was admitted |
| **Discharge Date** | Date when the patient was discharged |
| **Follow-up Date** | Scheduled follow-up appointment date |
| **Bill Amount** | Total bill generated for the patient |
| **Date Range Filter** | Enables dashboard-wide time filtering |

---

### 2. **Bed Occupancy**
Displays the count of patients occupying:
- **Private Wards**
- **General Wards**
- **ICU Wards**

Helps analyze resource utilization and patient distribution.

---

### 3. **Feedback Volume per Doctor**
A donut chart showing feedback count received by each consulting doctor:
- Helps evaluate **patient satisfaction**
- Supports identifying **high-performing physicians**

---

### 4. **Diagnosis-wise Patient Count**
Funnel chart listing top diagnoses:
- Viral Infection
- Flu
- Malaria
- Typhoid
- Pneumonia
- Fracture

Useful to track seasonal or recurring illness patterns across the hospital.

---

### 5. **Insurance vs Billing Comparison (Bed Occupancy Cost Analysis)**
Line chart comparing:
- **Health Insurance Claim Amounts**
- **Total Billing Amount**

Across diagnostic services like:
- CT Scan
- Ultrasound
- MRI
- Blood Test
- X-Ray

This helps in evaluating:
- Cost utilization efficiency
- Insurance coverage gaps
- Patient affordability trends

---

## 🧩 Data Source Details
| Data Type | Source Format | Usage |
|---------|--------------|-------|
| Patient Records | Excel / SQL | Patient profile, dates, billing |
| Diagnosis Records | Excel / SQL | Medical condition classification |
| Doctor Feedback | Survey/Entry System | Patient satisfaction metrics |
| Insurance Claims | Hospital Finance DB | Reimbursement analysis |

---

## 🎯 Business Use Cases
- Monitor **hospital capacity and resource management**
- Track **disease trend patterns** for better planning
- Identify **key doctors improving patient experience**
- Optimize **billing & insurance claim processes**
- Enhance **patient satisfaction & service efficiency**

---

## 🛠 Tools Used
| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Dashboard & Visualization |
| **Power Query** | Data Cleaning & Transformation |
| **DAX** | Measures & Calculations |

---

## 📦 How to Use the Dashboard
1. Open the `.pbix` file in **Power BI Desktop**
2. Refresh the data sources (ensure correct path/connection)
3. Use the slicers (Date Range, Patient ID, Ward Type) for exploration
4. Review visual summaries for decision-making

---

## 📈 Future Enhancements
- Add **prediction models** for patient inflow
- Include **doctor performance KPI scorecards**
- Automate **real-time data refresh**

---

## 👨‍⚕️ Created By
**Your Name**  
Data Analyst / BI Developer

---

If you found this helpful, consider ⭐ starring your project repo 😊
