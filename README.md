# HR Workforce Analytics Dashboard

## 📂 Project Deep Dive
### Project Overview
An interactive business intelligence report designed to explore employee engagement and workforce patterns. The project examines employee satisfaction, workload, performance evaluations, promotion patterns, and departmental differences to support exploratory analysis and inform data-driven workforce planning discussions.

## 🛠️ Tech Stack & Core Competencies
* **Languages & Frameworks:** DAX
* **Analytics & Visualization:** Power BI Desktop, Advanced Data Visualization, Dashboard Design
* **Domain Focus:** Strategic Workforce Planning, Exploratory Data Analysis, Employee Engagement Tracking

---
### Key Achievements & Objectives
* **Analyzed Workload & Engagement Variance:** Tracked how employee satisfaction levels fluctuate across low, medium, and high workload thresholds to isolate friction points.
* **Evaluated Departmental Performance:** Built comparative matrices crossing satisfaction indexes with performance evaluation scores across diverse organizational units.
* **Mapped Promotion Profiles:** Examined employee distribution and internal promotion velocities segmented by baseline satisfaction levels to identify workforce trends.
* **Uncovered Actionable Data Indicators:** Identified structural workforce patterns across the dataset to surface critical areas warranting deeper strategic investigation.

---
## 📊 Dashboard Pages & Previews
### 1. Overview
Provides a consolidated, executive view of employee headcount, departmental distributions, baseline satisfaction, project workloads, performance evaluations, and promotion trends.

![HR dashboard overview](visuals/dashboard-overview.png)

### 2. Workforce Trends
Provides a focused, deep-dive analytical view tracking:
* Average satisfaction scores plotted against defined workload levels.
* Cross-sectional views of satisfaction and performance evaluations by department.
* Employee headcount metrics and historical promotion patterns grouped by satisfaction layers.

![Workforce trends dashboard](visuals/workforce-trends.png)

---

## 💡 Selected Observations & Insights
* **The Workload Sweet-Spot:** Employees categorized within the medium-workload bracket demonstrate higher average satisfaction levels compared to colleagues in both low- and high-workload environments.
* **High-Workload Attrition Risk:** Staff members allocated to high-workload constraints reflect the lowest average satisfaction scores across all audited workload groupings.
* **Departmental Variances:** Performance evaluation metrics and average employee satisfaction scores vary visibly by department, indicating localized cultural or operational dynamics.

*Note: These observations describe descriptive patterns within the dataset and do not establish that workload or department assignment directly causes changes in satisfaction.*

---

## ⚙️ Repository Architecture & Usage

### Repository Contents
* `dashboard/`: Contains the primary Power BI report file (`HR-Workforce-Analytics.pbix`).
* `visuals/`: Contains high-resolution screenshots of the deployed report pages.
* `README.md`: Project overview, structured methodologies, and data documentation.

### How to View the Project
1. **Quick Preview:** Review the high-resolution dashboard screenshots embedded in the section above.
2. **Download File:** Clone this repository or download the `HR-Workforce-Analytics.pbix` file directly from the `dashboard` folder.
3. **Launch Environment:** Open the file locally using **Power BI Desktop**.
4. **Interactive Exploration:** Utilize native slicers and canvas tabs to navigate seamlessly between the **Overview** and **Workforce Trends** reports.

---

## 📋 Data Source & Technical Limitations

### Dataset Profile
This project utilizes the **Employee HR Dataset** published by Prisha Tank on Kaggle. The underlying data structure consists of individual employee records mapping:
* Employee satisfaction and performance evaluations
* Project workload, monthly working hours, and tenure metrics
* Historic promotions, organizational department, salary tiers, and attrition statuses

The source is verified as a simulated HR dataset devoid of personally identifiable information (PII). It is applied strictly for educational evaluation, technical portfolio demonstration, and exploratory analysis rather than to assert definitive findings about a live corporate entity.
* **Source:** [Employee HR Dataset — Prisha Tank via Kaggle](https://kaggle.com)
* **Dataset License:** CC BY-SA 4.0

### Limitations & Scope Constraints
* **Descriptive Scope:** The report delivers descriptive data patterns and historical reflections rather than prescriptive or validated predictive turnover modeling.
* **Data Dependency:** Analytical accuracy remains dependent on the source dataset’s inherent ingestion quality, structural definitions, and population coverage.
* **Non-Causal Insights:** Identified data associations represent correlations and should not be interpreted as absolute causal relationships.

---

## 🛡️ Academic & Data Integrity Notice
The materials hosted in this public repository represent independent applications of data analytics methodologies utilizing public-domain source code and synthesized data structures. They do not contain proprietary corporate materials, protected institutional data, or restricted commercial information.

**Author:** Takudzwa Melody Mazhambe

