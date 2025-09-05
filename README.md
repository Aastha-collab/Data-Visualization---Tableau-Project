# Data-Visualization- Project

##  Overview

This repository contains the solutions for the Deloitte Data Analytics Virtual Internship (Forage). The project focuses on analyzing telemetry data with Tableau and investigating employee pay equality with Excel.

---

##  Goal

* Apply **data visualization (Tableau)** and **data cleaning/analysis (Excel)** to solve real-world business problems.
* Extract insights for decision-making in **manufacturing operations** and **employee compensation fairness**.

---

##  Dataset

* **Task 1**: Daikibo Telemetry Data (`.json`) – machine health & downtime.
* **Task 2**: Equality Data (`.xlsx`) – employee compensation & equality scores.

---

##  Tools Used

* **Tableau** → Data visualization, dashboards.
* **Excel** → Data cleaning, calculated fields, classification.

---

##  Tasks

### Task 1 – Telemetry Data Dashboard (Tableau)

* Imported machine telemetry data (`.json`) into Tableau.
* Created calculated field **Unhealthy = 10 mins of downtime per unhealthy status**.
* Built dashboards with:

  * **Downtime per Factory (bar chart)**
  * **Downtime per Device Type**
  * **Interactive filters (factory-wise drill down)**
* **Insight**: Identified the factory with the highest downtime and device types causing delays.

![Task 1 Dashboard](https://github.com/Aastha-collab/Data-Visualization---Tableau-Project/blob/main/Tableau%20Dashboard.png)

---

###  Task 2 – Equality Pay Analysis (Excel)

* Imported employee equality dataset (`.xlsx`).
* Created a new column **Equality Class** based on score ranges:

  * `Fair` → between -10 and +10
  * `Unfair` → between -20 to -10 OR 10 to 20
  * `Highly Discriminative` → < -20 OR > 20
* **Insight**: Classified compensation fairness to detect pay inequality across factories and roles.

![Task 2 Excel](https://github.com/Aastha-collab/Data-Visualization---Tableau-Project/blob/main/Task%202_Equity%20Table.xlsx)

---

##  How to Run

1. **Task 1**:

   * Open `Task1/Deloitte_Task1_Dashboard.twbx` in Tableau.
   * Explore the dashboard to analyze downtime by factory and device type.

2. **Task 2**:

   * Open `Task2/Deloitte_Task2_Equality.xlsx` in Excel.
   * Review the Equality Class column and filter by factory/job role.

---

## 📌 Key Learnings

* Data preparation & calculated fields in Tableau.
* Building interactive dashboards for business insights.
* Data classification & analysis using Excel formulas.
* Applying **business context to analytics results**.


Would you like me to also prepare a **short 1–2 line summary version** of this for your resume (instead of the full README)?
