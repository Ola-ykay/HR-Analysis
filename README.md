# HR Analysis

## Table of Content
- [Project Overview](#project-overview)
- [Problem Statement](#problem-statement)
- [Tools and Features Used](#tools-and-features-used)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [KPIs](#kpis)  
- [Insights](#insights)
- [Business Impacts](#business-impacts)
- [Data Snapshots](#data-snapshots)
- [Conclusion](#conclusion)

## 📌Project Overview
The HR Analytics Dashboard is an interactive Power BI report designed to analyze workforce composition, employee attrition, performance, and engagement metrics.
This project transforms raw HR data into actionable insights that support data-driven decision-making in areas such as retention, workforce planning, compensation alignment, and employee development.

The dashboard is structured into three analytical pages:
- Workforce Overview
- Attrition Analysis
- Performance

 ## Problem Statement
Many organizations face challenges such as:
- High employee turnover
-Low employee satisfaction
- Unclear promotion patterns
Without proper data analysis, it becomes difficult for HR teams to make informed decisions.

This project helps to:
- Identify why employees leave
- Understand employee distribution across departments
- Analyze job satisfaction and work-life balance
- Check if performance aligns with salary hikes
- Support better HR decision-making

## 🛠Tools and Features Used
Tool Used:
 Microsoft Power BI

I applied all these features in this project:
- Data cleaning and transformation
- DAX formulas (measures and calculated columns)
- Interactive slicers
- Page navigation buttons
- Conditional formatting

## Data Cleaning and Preparation
Before building the dashboard, I 
- Checked for duplicate 
- Checked for missing values
- Standardized column names making my data esay to understand
- Changed data types
- Converted numeric ratings (1–4 scale) into readable categories:
1. Job Satisfaction → Low, Medium, High
2. Performance Rating → Good, Excellent
3. Work-Life Balance → Poor, Moderate, Good
- Created calculated columns for:
1. Promotion statusPerformance Rating
2. Job Satisfaction levels
   Created DAX measures for:
1.  Male and female workers
2.  Total employees
3.  Overtime employees
4.  Attrition rate
5.  Active workers
6.  Average satisfaction level
7.  Average performance Rating

## 📊KPIs
- Total Employees
- Active Workers
- Male Employees
- Female Employees
- Employees Due for Promotion
- Employees Not Due for Promotion
- Employees in-service

Attrition & Retention Page

- Attrition Count
- Attrition Rate (%)
- Employees Working Overtime
- Active Employees

Performance & Engagement Page
- Average Performance Rating
- Average Job Satisfaction
- Average Work-Life Balance
- Excellent Performance
- Good Performance

## Insights
 - Employee by years of service: 196 employees have 5 years of service (highest group) and only 32 employees have 11 years of service (lowest group).
 - Employees by distance status: 64% of employees live close to work,and 16% live very far from work. However, the 16% living far may be more vulnerable to fatigue or attrition.
 - Employees by department: Research & Development has the highest headcount (824 employees). This means that the organization has a broad entry-level base with fewer employees in senior roles.
 - Attrition by department: Sales department has the highest attrition rate of 21.8%.
 - Attrition by job role: Sales Representatives have the highest attrition rate (40.2%). 
 - Overtime vs attrition: Employees working overtime show 54% attrition, non-overtime employees show 46% attrition. Overtime is positively associated with employee turnover, indicating workload stress.
 - Attrition vs job satisfaction: Low satisfaction has 19.7% attrition, Medium satisfaction has 16.5% attrition, High satisfaction has 11.3% attrition. Lower job satisfaction significantly increases attrition risk.
 - Employees by job satisfaction: 569 employees has low job satifaction covering 38.7% of total employees.
 - Performance rating by average salary hike: Excellent performers receive 61% of total average salary hikes while good performers receive 39%. Salary increments are performance-aligned, indicating a performance-based reward system.
 - 

Analysis:
A large proportion of employees fall into the low satisfaction category — this is a potential risk indicator.
 - Performance rating by average salary hike
 - Monthly income by job role
 - Employees by training time

## 💼Business Impacts

This dashboard helps HR teams to:
- Identify departments with high attrition
- Improve employee retention strategies
- Monitor employee satisfaction
- Ensure fair reward and promotion systems
- Make better workforce planning decisions
- It turns raw HR data into clear, meaningful insights for decision-makers.

  
