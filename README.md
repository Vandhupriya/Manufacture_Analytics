# Manufacture Data Analytics Project

# Project Overview

This project involves analyzing manufacturing data using SQL, Excel, Tableau, and Power BI to derive insights and visualize key performance metrics.
The main objectives are to monitor production efficiency, track rejection trends, and provide a comprehensive overview of manufacturing performance across departments and machines.

# Tools and Technologies

**SQL**: For querying the manufacturing database to extract KPIs and operational insights.

**Excel**: For cleaning, merging, and analyzing data with pivot charts and filters.

**Power BI**: For building interactive dashboards to track production, rejection, and efficiency trends.

**Tableau**: For advanced visualization and trend analysis to support decision-making.

# Data Sources

Manufacturing Database — contains the following tables:

**Production Data** – Includes daily production quantity by machine and employee.

**Rejection Data** – Tracks rejected items and their reasons.

**Efficiency Data** – Measures overall equipment and workforce efficiency.

**Employee Data** – Contains employee IDs, departments, and assigned machines.

# SQL Queries

**Production KPI**: Calculates total production quantity per day, department, and machine.

**Rejection KPI**: Identifies daily rejection rates and reasons by department.

**Efficiency KPI**: Calculates efficiency based on machine uptime and output.

**Top Performing Machines**: Lists machines with the highest production efficiency.

**Low Efficiency Alerts**: Detects departments or machines falling below efficiency thresholds.

**Employee Contribution Report**: Shows production and rejection contribution by employee.

**Monthly Summary Report**: Summarizes production, rejection, and efficiency month-over-month.

# Excel Analysis

Pivot Charts were created for each SQL output to visualize the data effectively.
The charts include:

**Production Trend Analysis** – Daily and weekly output across machines.

Rejection Trend Analysis – Defects and rejections by department and reason.

**Efficiency Overview** – Comparison of machine and employee efficiency.

**Top Machines by Production** – Visual ranking of machine performance.

**Department-Wise Analysis** – KPIs filtered by department and date.

**Monthly Summary** – Overview of production and rejection trends month-over-month.

# Power BI Dashboard

This dashboard provides a comprehensive analysis of production output, rejection, and efficiency metrics.

**Visuals Included:**

**Clustered Bar Chart**: Displays total production vs. rejection by department.

**Line Chart**: Shows efficiency trends over time by machine.

**Donut Chart**: Highlights rejection percentage by department.

**Stacked Column Chart**: Compares production and rejection by employee.

**Cards**: Display total production, rejection count, and average efficiency rate.

**Trend Lines**: Indicate improvement or decline in production over time.

**Slicers**:

**Date Slicer**: Filters data by specific date or month.

**Department Slicer**: Filters dashboards by department.

**Machine Slicer**: Filters visuals by machine name.

**Toggle Buttons:**

Switch between Production View and Efficiency View in the charts.

# Tableau Dashboard

This dashboard focuses on a detailed breakdown of efficiency and rejection metrics.

**Visuals Included:**

**Decomposition Tree:** Breaks down efficiency by department → machine → employee.

**Table:** Displays production summary with columns such as:

Production Date

Department

Machine Name

Total Units Produced

Rejected Units

Efficiency %

**Toggle Buttons:** Switch between dashboards for comprehensive insights.

# How to Run the Project

**Database Setup:** 

Instructions for running the queries:

1.	Open MySQL Workbench
	
2.	Go to your schema list and create a new schema
	
3.	Right-click the schema you created → Table Data Import Wizard →name the table manufacturing_data.
	
4.	Select your .csv file → Select the attached manufacturing_data.csv file
   
5.	Name the table manufacturing_data

**Excel Analysis:** Import SQL query results into Excel and create pivot charts for analysis.

**Power BI and Tableau Dashboards:**

Import Excel data into Power BI and Tableau.

Create visualizations and set up filters, slicers, and toggle buttons.

**Interact with the Dashboards:**

Use slicers to explore department, machine, and date-specific trends.

Toggle between views to compare production, rejection, and efficiency.

# Conclusion

This project showcases how SQL, Excel, Tableau, and Power BI can be integrated to analyze and visualize manufacturing data effectively.
The insights derived from the dashboards help manufacturing managers optimize production, reduce rejections, and enhance operational efficiency through data-driven decisions.
