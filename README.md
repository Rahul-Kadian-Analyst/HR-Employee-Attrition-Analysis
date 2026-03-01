# HR Employee Attrition Analysis 👥

# Overview
This project analyzes HR employee data to understand why employees are leaving the company. The goal was to help the HR team identify which departments, age groups, job roles and salary levels have the highest attrition so they can take action to retain employees.

# Tools Used
- Microsoft Excel — Data cleaning and feature engineering
- Microsoft Power BI — Interactive dashboard and visualizations

# Dataset
- 1,470 rows of IBM HR employee data
- 35+ columns including Age, Attrition, Department, Gender, JobRole, MonthlyIncome, OverTime, PerformanceRating, WorkLifeBalance, YearsAtCompany and more

# Data Cleaning (Excel)
- Converted all columns to correct data types
- Verified no null or blank values exist
- Formatted data as Excel Table for structured analysis

# Feature Engineering (Excel)
New columns created:
- Attrition Flag = 1 if employee left, 0 if still active
- Age Group = Young / Mid Age / Senior
- Income Group = Low / Medium / High based on Monthly Income
- Experience Level = Junior / Mid Level / Senior based on Total Working Years
- Years At Company Group = New / Early / Experienced / Veteran

# Dashboard (Power BI)
The dashboard contains 4 pages:

# Page 1 — HR Overview
- KPI Cards: Total Employees, Total Attrition, Active Employees, Attrition Rate, Average Age, Average Monthly Income
- Attrition Rate by Gender
- Total Employees by Department
- Attrition Rate by JobRole
- Attrition Rate by MaritalStatus
- Department Slicer for filtering

# Page 2 — Attrition Analysis
- Attrition Rate by Age Group
- Attrition Rate by Experience Level
- Attrition Rate by BusinessTravel
- Attrition Rate by Income Group
- Attrition Rate by OverTime
- Attrition Rate by Years At Company Group
- Department Slicer for filtering

# Page 3 — Employee Demographics
- Average Monthly Income by JobRole
- Average Monthly Income by Department
- Total Employees by Age Group
- Total Employees by EducationField
- Total Employees by WorkLifeBalance
- Total Employees by JobSatisfaction

# Page 4 — Key Business Insights
Summary of all major findings and recommendations

# Key Insights
- 👥 Total Attrition Rate is 16.12% — roughly 1 in 6 employees is leaving
- 🏢 Sales department has the highest attrition rate of 20.63%
- 👤 Young employees have the highest attrition — likely due to better opportunities
- 💰 Low income employees have the highest attrition — salary is a key driver
- ⏰ Employees working OverTime are significantly more likely to leave
- 💼 Sales Representatives is the job role with highest attrition
- 💍 Single employees leave more than married or divorced employees
- ✈️ Employees who Travel Frequently have higher attrition than non-travelers

# Business Recommendations
- Increase salary for low income employees to reduce attrition
- Reduce overtime especially in the Sales department
- Create retention programs for young and single employees
- Investigate why Sales Representatives are leaving at such high rates
- Consider travel allowances or benefits for frequently traveling employees

# Author
Rahul
- Connect with me on [https://www.linkedin.com/in/rahul-kadian-0a282828a/](#)
