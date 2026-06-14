# church-operations-analytics-powerbi.
An end-to-end data analytics solution transforming church operations from manual tracking into an automated Power BI pipeline. Features interactive dashboards for membership demographics, attendance trends, and visitor retention analytics using cloud-connected data sources.


# End-to-End Church Operations & Growth Analytics Dashboard
Using Power BI & Google Cloud Databases to drive administrative efficiency and visitor retention.

---

## 1. Project Overview
This repository features an end-to-end data analytics solution developed for a regional church congregation ("The Stone Church UI Area"). The goal of this project was to transition the organization from fragmented, manual tracking systems into a centralized, automated cloud analytics pipeline. 

By connecting operational data directly to interactive dashboards, church leadership can now make data-driven decisions regarding resource allocation, volunteer engagement, and visitor retention.

### Key Dashboards Developed:
1. **Congregation Profile Dashboard:** Tracks membership demographics, spiritual milestones, and departmental distributions.
2. **Attendance Profile Dashboard:** Visualizes weekly and monthly attendance trends across Sunday and mid-week services.
3. **First-Timers Profile Dashboard:** Analyzes visitor demographics, occupation status, and direct retention/follow-up intent.

---

## 2. Problem Statement vs. Business Solution

| The Manual Challenge | The Analytical Solution |
| :--- | :--- |
| **Data Silos:** Membership details, first-timer cards, and attendance logs were scattered across paper records and separate spreadsheets. | **Centralized Data Hub:** Modeled 3 relational databases in Google Sheets acting as a unified cloud source of truth. |
| **Visitor Churn:** No systematic way to track first-time visitors, leading to gaps in follow-up and lower retention. | **Retention Funnel:** Isolated visitor intent (Yes/Maybe/Visiting) against age cohorts to optimize follow-up strategies. |
| **Operational Blindspots:** Difficulty evaluating mid-week vs. Sunday service engagement or identifying demographic trends. | **Trend Analysis:** Automated monthly averages and service-specific gauge charts to optimize volunteer staffing. |

---

## 3. Tech Stack & Data Architecture
* **Data Sources:** Google Sheets (Cloud Relational Databases)
* **ETL & Data Transformation:** Power Query (M Language)
* **Data Modeling & Analytics:** Power BI Desktop, DAX (Data Analysis Expressions)
* **Visualizations:** KPI Cards, Gauges, Time-Series Line Charts, Cross-filtering Donut/Pie charts.

### Data Pipeline Architecture:
`Google Sheets (Live Cloud Data)` ➡️ `Power Query (Data Cleansing & Reshaping)` ➡️ `Power BI Star Schema Model` ➡️ `Interactive Dashboard UI`

---

## 4. Dashboard Visuals & Insights

### A. Congregation Profile
Comprehensive breakdown of the church's core demographics, including employment profiles, marital status, and ministry department distribution.
![Congregation Profile]<img width="1274" height="749" alt="Church_Database_PowerBI" src="https://github.com/user-attachments/assets/5d4ec324-33bf-42e3-a163-aec127445109" />


### B. Attendance Trends
Tracks monthly attendance trajectories and isolates average turnouts for Sunday vs. Wednesday services using target gauge visuals.
![Attendance Profile]<img width="1277" height="746" alt="Attendance_Profile" src="https://github.com/user-attachments/assets/9ca1efd6-ad40-4475-b48f-da80f57aaf9c" />


### C. First-Timers Profile & Retention
Monitors incoming visitors by week/month, highlighting conversion intent ("Yes" to joining vs. "Visiting") to empower the evangelism team.
![First Timers Profile]<img width="1279" height="755" alt="First_Timers_Dataset" src="https://github.com/user-attachments/assets/b9ec7977-dd5a-4b66-a062-eac0a5963f19" />


---

## 5. Key Technical Implementations
* **Data Cleansing:** Used Power Query to eliminate structural anomalies, filter out survey noise from open-ended text fields, and categorize continuous age data into specific cohorts.
* **DAX Analytics:** Developed custom measures to dynamically compute monthly rolling averages, attendance targets, and demographic ratios across changing temporal filters.

---
*Note: To protect the privacy of the congregation, all personally identifiable information (PII) has been fully anonymized or masked in the screenshots and sample datasets.*
