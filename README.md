# PR.4 Accenture HR Data Analytics (Power BI)

# HR Workforce Analytics — Power BI Dashboard

<p align="center">
  <img src="assets/workforce-overview.png" alt="HR Workforce Analytics — Workforce Overview" width="100%">
</p>

<p align="center">
  <b>Comprehensive HR analytics dashboard for workforce overview, attrition, compensation, hiring, and employee performance insights.</b>
</p>

---

## 📊 Project Overview

The **HR Workforce Analytics Dashboard** is an interactive Power BI solution designed to provide a comprehensive view of workforce performance and employee trends.

The project is divided into three analytical pages:

- **Workforce Overview** — Headcount, hiring trends, workforce composition, salary, performance, and department-level insights.
- **Attrition Analysis** — Employee turnover, attrition rate, terminations, hiring growth, and attrition by department and career level.
- **Compensation Analysis** — Salary benchmarking, salary bands, department salary ranking, training investment, and above/below-average salary distribution.

---

## 🖥️ Dashboard Pages

### 1. Workforce Overview

<p align="center">
  <img src="assets/workforce-overview.png" alt="Workforce Overview Dashboard" width="100%">
</p>

**Key Insights:**
- Total Headcount
- Active Headcount
- Attrition Rate
- Average Salary
- Average Tenure
- High Performance %
- Gender Diversity Ratio
- Total Training Cost
- Year-to-Date New Hires
- Annual Hiring vs Same Period Last Year
- Workforce Distribution by Career Level
- Active Headcount by Department
- Department Salary & Performance Ranking

---

### 2. Attrition Analysis

<p align="center">
  <img src="assets/attrition-analysis.png" alt="Attrition Analysis Dashboard" width="100%">
</p>

**Key Insights:**
- Overall Attrition Rate
- Terminated Employees
- Attrition Rate YTD
- New Hire YoY Growth
- Year-to-Date New Hires
- Terminated Employees by Career Level
- Terminated Employees by Year
- Attrition Rate by Department
- Interactive Year and Department Analysis

---

### 3. Compensation Analysis

<p align="center">
  <img src="assets/compensation-analysis.png" alt="Compensation Analysis Dashboard" width="100%">
</p>

**Key Insights:**
- Average Salary by Department
- Department Salary Ranking
- Training Cost by Department
- Above vs Below Average Salary
- Employee Distribution by Salary Band
- Career Level Band Analysis
- Salary Band Analysis
- Department Compensation Benchmarking

---

## 🎯 Business Questions Answered

1. What is the current workforce size?
2. How many employees are currently active?
3. What is the overall attrition rate?
4. Which departments have the highest attrition?
5. Which career levels experience the most employee turnover?
6. How has hiring changed year over year?
7. Which departments have the highest average salaries?
8. Which department ranks highest in salary?
9. Where is the organization spending the most on employee training?
10. What percentage of employees earn above or below average salary?
11. How is the workforce distributed across salary bands?
12. Which departments combine strong performance with competitive compensation?

---

## 📈 Key KPIs

| KPI | Description |
|---|---|
| **Total Headcount** | Total number of employees |
| **Active Headcount** | Number of currently active employees |
| **Attrition Rate** | Percentage of employees who left |
| **Average Salary** | Average employee salary |
| **Average Tenure** | Average employee tenure |
| **High Performance %** | Percentage of high-performing employees |
| **Gender Diversity Ratio** | Workforce gender diversity indicator |
| **Total Training Cost** | Total investment in employee training |
| **New Hire Growth %** | Year-over-year new hire growth |

---

## 🔍 Interactive Filters

- Year
- Department Type
- Career Level Band
- Salary Band

These filters allow users to drill down into specific employee groups and analyze workforce trends.

---

## 🛠️ Tools & Technologies

- Power BI Desktop
- DAX
- Power Query
- Excel
- Data Modeling
- Data Visualization
- Business Intelligence

### Power BI Features Used

- KPI Cards
- Bar Charts
- Column Charts
- Line Charts
- Donut Charts
- Tables & Matrices
- Slicers
- Conditional Formatting
- DAX Measures
- Time Intelligence
- Interactive Page Navigation
- Cross-filtering

---

## 🧮 Example DAX Measures

### Active Headcount

```DAX
ACTIVE HEADCOUNT =
COUNTROWS(Employees)
