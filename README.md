# 🏥 Medical Data Dashboard (Power BI)

This project is a **Power BI dashboard** built on a healthcare dataset (55,000+ records).  
It provides insights into **patient demographics, hospital admissions, financial costs, treatments, and trends over time**.

---

## 📄 Dashboard Pages

### Page 1 – Patient & Hospital Overview
- **Patient Demographics**
  - Age distribution (histogram)
  - Gender distribution (donut chart)
  - Blood type distribution (bar chart)
  - Top medical conditions (bar chart)
- **Hospital & Admission Insights**
  - Patients per hospital
  - Top 10 doctors
  - Admission types (emergency, urgent, elective)
  - Average length of stay
- **Financial Insights**
  - Total billing amount (KPI card)
  - Average billing per patient (KPI card)
  - Billing by condition
  - Billing by hospital/insurance provider
- **Top 10 High-Cost Admissions**
  - Table with patient demographics and billing

---

### Page 2 – Treatment & Time Trends
- **Treatment & Diagnosis**
  - Most prescribed medications (Top 10)
  - Test result distribution (normal/abnormal/inconclusive)
  - Conditions linked to abnormal tests
- **Time Trends**
  - Admissions over time (monthly)
  - Billing amount over time (with trendline)
  - Condition trends over years (multi-line chart)
  - Seasonal trends (Month vs Year heatmap)
- **Additional Insights**
  - Billing by gender
  - Department-wise costs

---

## 🎨 Design & Features
- Two-page design: **Page 1 → Who & Where, Page 2 → What, How Much & When**  
- **Custom PatientKey** column created to resolve duplicate names (Name + Age + Gender).  
- **KPI cards** for key metrics (total billing, avg billing).  
- **Heatmap via conditional formatting** for seasonal admission analysis.  
- **Top N filters** applied for doctors, medications, and high-cost patients.  

---

## 🚀 Tools & Technologies
- **Power BI Desktop** (visualization & dashboard design)  
- **DAX** (calculated columns, measures)  
- **Power Query** (data cleaning, transformations)  

---

## 📂 Repository Contents
- `/data/` → Healthcare dataset (CSV, anonymized/synthetic)  
- `/dashboard/` → Power BI (.pbix) file + exported PDF  
- `/images/` → Screenshots of dashboard pages  
- `README.md` → Project documentation  

---

## 📌 Key Insights
- Majority of patients are **middle-aged (21–40 years)**.  
- **Elective admissions** dominate, followed by urgent and emergency.  
- **Diabetes and Obesity** account for the highest total billing costs.  
- **Seasonal admission spikes** appear mid-year (possible seasonal illnesses).  
- Billing is nearly balanced across genders (~50% each).  

---

## 🔗 Links
- 📊 [LinkedIn Post](#)  
- 📂 [Full Dashboard PDF](Medical%20Dashboard.pdf)  
- 💻 [GitHub Repository](https://github.com/Joydip20/Medical-Dashboard/tree/main)  

---

## 🏷 Tags
`Power BI` `Healthcare Analytics` `Data Visualization` `Dashboard Design`
