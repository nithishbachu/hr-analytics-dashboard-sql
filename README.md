# hr-analytics-dashboard-sql

## 📌 Overview

This project performs comprehensive **Human Resources (HR) data analytics** on a dataset containing **22,214 employee records**. Using **MySQL** for data storage, **SQL** for analysis, and **Power BI** for visualization, the project uncovers key insights related to employee demographics, turnover patterns, departmental trends, and organizational workforce distribution.

The goal is to help HR teams make **data-driven decisions** in hiring, retention, and workforce planning.

---

## 🎯 Project Objectives

* Clean, preprocess, and structure HR data in a relational database.
* Perform exploratory and statistical analysis on employee demographics.
* Analyze turnover, tenure, and department-level workforce behaviour.
* Visualize KPIs and trends using Power BI dashboards.
* Identify actionable insights to support HR strategy.

---

## 📂 Dataset Description

The dataset consists of **22,214 rows × 13 columns** with employee-level information.

### **Key Columns**

| Column Name      | Description                                   |
| ---------------- | --------------------------------------------- |
| Employee ID      | Unique identifier for each employee           |
| Name             | Full employee name                            |
| Age              | Employee age                                  |
| Gender           | Gender identity                               |
| Race/Ethnicity   | Racial/ethnic group                           |
| Department       | Department name                               |
| Location         | Geographic location                           |
| Hire Date        | Date employee was hired                       |
| Termination Date | If applicable, date employee left the company |
| Status           | Active / Terminated                           |

---

## 🧹 Data Cleaning & Preprocessing

Steps performed:

* Handling missing and inconsistent values
* Removing duplicate records
* Converting columns to appropriate data types
* Standardizing date formats
* Validating categorical attributes
* Removing obvious outliers
* Ensuring relational integrity in MySQL

Scripts are available in the `sql/` directory.

---

## 📈 Power BI Dashboard

The dashboard includes:

* Employee headcount overview
* Hires vs terminations trend
* Turnover rate by department
* Age, gender, race/ethnicity demographics
* Location-wise workforce distribution
* Tenure patterns

Visualizations include bar charts, line charts, maps, KPIs, and heatmaps.

---

## 🧾 Conclusion

This HR Data Analytics project provides a clear, data-driven understanding of workforce structure, diversity, tenure trends, and departmental turnover. The insights derived can help HR teams in:

* Improving hiring strategies
* Targeting retention efforts
* Enhancing workforce planning
* Identifying high-risk departments
* Understanding long-term demographic trends

The project can be extended with predictive modelling to forecast attrition and staff performance.
