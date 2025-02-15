# HR Employee Attrition Analysis - Power BI
# Project Overview:
This project analyzes employee attrition trends within an organization using Power BI. The goal is to identify key factors contributing to attrition and provide data-driven insights to HR and management to improve employee retention strategies.
________________________________________
# Project Objectives:
✅ Identify key drivers of attrition (departments, gender, job roles, etc.).
✅ Develop a star schema for efficient data modeling.
✅ Create meaningful KPIs and measures (Attrition %, Total Employees, etc.).
✅ Build interactive dashboards to explore attrition trends.
✅ Provide actionable recommendations to reduce attrition.
________________________________________
# Dataset Description:
The dataset consists of employee records with attributes related to demographics, job roles, performance, and compensation.
Key Features:
•	Employee Information → Employee Number, Gender, Job Level, Job Role
•	Department Details → Department, Promotion Status
•	Job Status → Distance from Home, Business Travel
•	Performance Metrics → Environment Satisfaction, Performance Rating
•	Compensation & Tenure → Daily Rate, Service Years
•	Attrition Indicator → Whether the employee left the company
________________________________________
# Data Preparation & Modeling:
Data Cleaning:
•	Removed duplicate or inconsistent records.
•	Created conditional columns for categorization.
•	Standardized missing or incorrect values.
# Star Schema Design:
Fact Table: Fact_Attrition
Contains the key measures related to attrition, including employee ID, department ID, job role ID, and performance ID.
Dimension Tables:
•	Dim_Employees (EmpNum, Gender, Job Level, Job Role, etc.)
•	Dim_EmpDepartments (DeptID, Department, Promotion Status)
•	Dim_EmpJobStatus (Distance from Home, Business Travel)
•	Dim_EmpPerformance (Environment Satisfaction, Performance Level)
•	Dim_EmpRating (Daily Rate, Service Years)
________________________________________
# Measures & Key Metrics:
📌 #Attrition = Count of employees who left
📌 Attrition % = (#Attrition / Total Employees) × 100
📌 #Employees = Total number of employees
📌 #Departments = Count of unique departments
________________________________________
# Dashboard Insights & Visualizations:
# Key Insights on Attrition:
•	Attrition by Departments → Highest attrition in Research & Development
•	Attrition by Working Years → Higher attrition among employees with 0-10 years of experience
•	Attrition by Employee Satisfaction → Lower satisfaction correlates with higher attrition
•	Male vs. Female Attrition % → Male attrition rate is higher than female
•	Attrition by Distance to Work → Employees living farther from the workplace have a higher attrition rate
•	Attrition by Job Roles, Age, and Education → Younger employees and certain job roles show higher attrition rates
•	Attrition by Overtime and Work-Life Balance → Employees with frequent overtime and poor work-life balance tend to leave more
•	Attrition by Environment Satisfaction and Performance Levels → Lower environment satisfaction and low performance ratings contribute to higher attrition
•	Employees Due for Promotion vs. Not Due → Employees overdue for promotion are more likely to leave
________________________________________
# Recommendations to Reduce Attrition:
🔹 Enhance Work-Life Balance → Introduce flexible work models and reduce overtime.
🔹 Improve Employee Satisfaction → Conduct regular surveys and feedback sessions.
🔹 Offer Career Growth Opportunities → Implement mentorship and upskilling programs.
🔹 Reassess Compensation & Benefits → Ensure competitive salaries and incentives.
🔹 Targeted Retention Strategies → Identify high-risk employee groups and address concerns proactively.
________________________________________
# How to Use This Power BI Report:
1️⃣ Open the Power BI Dashboard to explore interactive insights.
2️⃣ Use slicers and filters (e.g., gender, department, job roles) to analyze different factors.
3️⃣ Hover over tooltips for additional insights on each visual.
4️⃣ Navigate using buttons for easy report access.
________________________________________
# Tools & Technologies Used:
•	Power BI → Data visualization & dashboard creation
•	DAX (Data Analysis Expressions) → Measure creation
•	Excel → Data pre-processing
________________________________________
# Conclusion:
This HR Employee Attrition Analysis provides valuable insights into why employees leave, helping HR and management reduce attrition, enhance employee satisfaction, and retain top talent. Implementing these recommendations will create a more sustainable and employee-friendly workplace.

