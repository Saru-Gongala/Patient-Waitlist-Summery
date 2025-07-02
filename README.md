# 🏥 Patient Waitlist Summary Dashboard

## 📊 Project Overview

This Power BI dashboard presents a **comprehensive summary of patient waitlist trends** over time, segmented by **case type, age profile, and medical specialty**. It is designed to help healthcare administrators, analysts, and decision-makers monitor and manage waitlist backlogs more efficiently.

---

## 📁 Data Scope

- **Timeframe:** January 31, 2018 – January 21, 2021
- **Metrics Covered:**
  - Total number of patients on the waitlist
  - Segmentation by **case type**: Outpatient, Inpatient, Day Case
  - Age group stratification: 0–15, 16–64, 65+
  - Medical specialties (e.g., Paediatric Orthopaedic, A&E, Cardiology, Dermatology)

---

## 📈 Key Visuals Used

1. **KPI Tiles**
   - `679K` — Latest Month Waitlist Count
   - `620K` — Previous Year’s Latest Month Waitlist Count

2. **Donut Chart**
   - **Average / Median Waitlist** by `Case_Type` (Outpatient, Day Case, Inpatient)

3. **Bar Chart**
   - **Average Waitlist** by `Time_Bands` (0–3 months, 3–6, ..., 18+ months)
   - Segmented by `Age_Profile` (0–15, 16–64, 65+)

4. **Line Charts**
   - **Trend of Total Waitlist Count** by `Archive_Date` for:
     - **Inpatient & Day Case**
     - **Outpatient**
  
5. **List View**
   - **Top Specialties** by `Avg / Median Waitlist Time` (e.g., Paed Orthopaedic, A&E)

6. **Slicers/Filters**
   - `Date Range` selector
   - Case Type filter
   - Speciality filter
   - Average/Median toggle

---

## 💡 Key Insights

- 📈 **Significant Increase in Total Waitlist** from early 2018 to late 2020, with a peak observed post mid-2020.
- ⏱️ **Outpatients dominate the waitlist volume** (visualized via donut chart).
- 👵 **Older age groups (65+) tend to have longer average waiting times**, especially in the 18+ months band.
- 🏥 **Certain specialties like Paed Orthopaedic and A&E have the highest average wait times**, exceeding 100+ days.
- 📉 **Inpatient and Day Case volumes remained relatively stable**, while outpatient cases surged significantly.

---

## ⚙️ Tools & Technologies Used

- **Power BI**
  - Data modeling
  - DAX Measures (Average/Median calculations)
  - Interactive slicers and filters
  - Time-series visualization

- **Excel/CSV** (assumed as data source)

---

## 🚀 How to Use

1. Open the `.pbix` file in Power BI Desktop.
2. Use the date slicer and filters to explore trends by case type or specialty.
3. Toggle between `Average` and `Median` views for detailed analysis.
4. Analyze peak load months and aging patient segments for targeted action.

---

## 📌 Future Enhancements

- Include filters for **hospital location** or **facility type**.
- Add **forecasting trends** based on historical patterns.
- Implement **conditional alerts** for specialties breaching SLA wait times.

---

## 📷 Screenshot

![Patient Waitlist Dashboard](./2ca8845b-dbea-4aa6-87d3-469dff509fd3.png)

---

## 📬 Contact

For questions, feedback, or collaboration:
**Name:** Saru Gongala  

---

