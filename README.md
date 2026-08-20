# hr-analytics-employee-attrition
End-to-end HR Analytics project analyzing employee attrition using Python, SQL, and Power BI.

[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)](https://www.python.org/)
[![SQL](https://img.shields.io/badge/SQL-SQLite-blue?logo=sqlite&logoColor=white)](https://www.sqlite.org/)
[![Power%20BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c)](https://matplotlib.org/)
[![SQLite](https://img.shields.io/badge/SQLite-Database-003B57?logo=sqlite&logoColor=white)](https://www.sqlite.org/)

## Project Overview

This project analyzes employee attrition to identify the main factors associated with employee turnover and provide actionable insights for HR decision-making.

Using the IBM HR Analytics Employee Attrition & Performance dataset, the analysis combines **Python, SQL, and Power BI** to explore employee characteristics, identify attrition patterns, and develop an interactive dashboard.

The project follows a structured data analytics workflow, including **data cleaning, exploratory analysis, advanced SQL analysis, data visualization, and business recommendations**.

The main objective is to understand **which employee groups are more likely to leave the company and which factors may contribute to higher attrition**, supporting more informed HR strategies and retention initiatives.

## Business Questions

The analysis was guided by the following business questions:

1. What is the overall employee attrition rate?
2. Which departments and job roles experience the highest turnover?
3. Does employee age influence attrition?
4. Is there a relationship between monthly income and attrition?
5. How does overtime affect employee turnover?
6. Does job satisfaction influence the likelihood of leaving the company?
7. How long do employees typically stay before leaving?
8. Does the distance from home affect attrition?
9. What actions can HR take to improve employee retention?

## Methodology

The project followed a structured data analytics workflow:

1. **Data Understanding**
   - Reviewed the dataset structure, variables, data types, and initial data quality.

2. **Data Cleaning**
   - Cleaned and prepared the dataset using Python and Pandas.
   - Checked for missing values, duplicates, inconsistent data, and data types.

3. **Exploratory Data Analysis**
   - Analyzed employee attrition across demographic, job-related, compensation, satisfaction, and work-related factors.
   - Identified patterns and relationships associated with employee turnover.

4. **SQL Analysis**
   - Built a relational database using SQLite.
   - Used business and advanced SQL queries to summarize employee data and identify higher-risk groups.

5. **Power BI Dashboard**
   - Developed an interactive dashboard to communicate the main HR metrics and findings.
   - Applied DAX measures, visual interactions, and dashboard formatting to improve usability.

6. **Business Insights & Recommendations**
   - Translated analytical findings into actionable HR recommendations focused on employee retention and attrition reduction.


## Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| **Python** | Data cleaning, transformation, and exploratory data analysis |
| **Pandas** | Data manipulation and analysis |
| **Matplotlib** | Data visualization |
| **Seaborn** | Statistical visualization and exploratory analysis |
| **SQLite** | Database creation and SQL analysis |
| **SQL** | Business and advanced analytical queries |
| **Power BI** | Interactive dashboard and data visualization |
| **DAX** | Measures and calculations in Power BI |
| **Power Query** | Data preparation and transformation |
| **GitHub** | Project documentation and version control |
| **VS Code** | SQL development and project management |
| **Jupyter Notebook** | Python-based data analysis |


## Key Findings

The analysis identified several factors strongly associated with employee attrition:

- **Overall attrition:** Employee turnover represents a significant HR challenge, with attrition concentrated among specific employee groups.

- **Overtime:** Employees working overtime showed substantially higher attrition than employees who did not work overtime, making overtime one of the strongest observed risk factors.

- **Job Satisfaction:** Attrition decreased as job satisfaction increased. Employees with low job satisfaction had an attrition rate of **22.84%**, compared with **11.33%** among employees with very high job satisfaction.

- **Work-Life Balance:** Employees reporting poor work-life balance showed considerably higher attrition. The highest attrition rate was **31.25%** among employees in the lowest work-life balance category.

- **Tenure:** Employees with shorter tenure were more likely to leave. The **0–5 years** group had an attrition rate of **20.88%**, compared with **6.67%** among employees with 11–20 years at the company.

- **Distance From Home:** Attrition increased among employees living farther from the workplace. Employees living **21+ miles** away had an attrition rate of **22.06%**, compared with **13.77%** among those living 0–5 miles away.

- **Job Role:** Attrition varied considerably across job roles, with some positions showing substantially higher turnover than others. **Sales Representatives** showed the highest attrition among the analyzed roles.

- **Risk Segmentation:** The advanced SQL analysis identified clear differences between employee risk groups. High-risk employees represented a smaller segment of the workforce but showed a substantially higher attrition rate than medium- and low-risk groups.

Overall, the findings suggest that employee attrition is not driven by a single factor. Instead, it is associated with a combination of **workload, satisfaction, work-life balance, tenure, distance from work, and job characteristics**.


## HR Recommendations

Based on the findings, the following actions could help reduce employee attrition and improve retention:

1. **Review Overtime Policies**
   - Monitor excessive overtime and identify teams or roles with sustained high workloads.
   - Consider workload redistribution, staffing adjustments, and improved scheduling practices.

2. **Improve Employee Satisfaction**
   - Conduct regular employee feedback surveys to identify the main drivers of dissatisfaction.
   - Develop targeted engagement initiatives for groups with consistently lower satisfaction levels.

3. **Strengthen Work-Life Balance**
   - Promote healthier workload management and flexible work practices where operationally feasible.
   - Pay particular attention to employees reporting poor work-life balance.

4. **Focus on Early-Tenure Employees**
   - Strengthen onboarding, mentoring, and career development programs for employees in their first years at the company.
   - Monitor early-tenure attrition to identify potential retention issues before employees leave.

5. **Address Commuting Challenges**
   - Evaluate transportation support, flexible schedules, remote or hybrid work options, and other alternatives for employees with longer commutes.

6. **Target High-Risk Employee Groups**
   - Use the risk segmentation developed through SQL analysis to prioritize retention efforts.
   - Combine multiple risk factors rather than relying on a single indicator when identifying employees who may require additional support.

7. **Develop Role-Specific Retention Strategies**
   - Investigate the underlying causes of high attrition in specific job roles.
   - Adapt retention strategies according to workload, career progression, compensation, and working conditions.

These recommendations should be supported by continuous monitoring of HR metrics to evaluate their effectiveness and identify emerging attrition patterns.

## 9.7 Power BI Dashboard

The Power BI dashboard provides an interactive overview of employee attrition and highlights the main factors associated with employee turnover.

### Dashboard Preview

![HR Analytics Employee Attrition Dashboard](![alt text](image.png))

### Key Dashboard Components

- **Total Employees:** 1,470
- **Attrition Rate:** 16.12%
- **Average Monthly Income:** 6,503
- **Employees Left:** 237
- **Employees Left by Department**
- **Employees Left by Job Role**
- **Attrition Rate by Years at Company**
- **Attrition Rate by Overtime**
- **Attrition Rate by Job Satisfaction Level**
- **Attrition Rate by Distance From Home**
