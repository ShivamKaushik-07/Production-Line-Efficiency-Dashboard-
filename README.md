Production Line Efficiency Dashboard – Tata Motors (OEE Analysis)
This project presents a real-world manufacturing analytics dashboard built using Power BI and SQL, focusing on Overall Equipment Effectiveness (OEE). It analyzes key metrics across production lines to uncover operational inefficiencies and improve manufacturing performance.

🧠 Objective
To measure and visualize OEE (Overall Equipment Effectiveness) by analyzing:

Availability

Performance

Quality

The goal is to help manufacturing teams at Tata Motors identify and reduce machine downtimes, track performance trends, and improve production outcomes using data-driven insights.

🏭 Why OEE?
OEE is a global benchmark used to determine how effectively a manufacturing operation is utilized.
OEE (%) = Availability × Performance × Quality

A score of 100% means perfect production with no downtime, optimal speed, and zero defects.

📁 Dataset
Simulated dataset representing Tata Motors’ production line:

Machine_ID

Shift

Date (Year, Month, Day)

Planned_Production_Time

Unplanned_Downtime

Ideal_Cycle_Time

Total_Units_Produced

Good_Units

Temperature_C

Pressure_bar

Downtime_Reason

🔧 Tools Used
Tool	Purpose
SQL	Data storage, cleaning, and queries
Power BI	Dashboard creation & visualization
Excel	Data formatting & simulation

🧪 Step-by-Step Workflow
📌 Step 1: Define Metrics
Calculated Availability, Performance, and Quality:

Availability = (Planned Time - Downtime) / Planned Time

Performance = (Ideal Cycle Time × Total Units) / Run Time

Quality = Good Units / Total Units

📌 Step 2: Database Setup
Created database: tata_motors

Created table: production_line

Inserted simulated production data via SQL queries

📌 Step 3: Data Cleaning & Preprocessing
Handled nulls and outliers

Converted datetime fields

Validated KPI columns (Availability, Performance, Quality)

📌 Step 4: Connect SQL to Power BI
Imported the cleaned table from the SQL server into Power BI for visualization

📌 Step 5: Dashboard Development in Power BI
📈 Visuals Implemented:
KPI Cards: Average OEE, Average Availability, Best Performing Machine

Line Chart: Average OEE over Time

Clustered Bar: Downtime Reason by Machine

Scatter Plot: Temperature vs Pressure per Machine

Slicers: Shift, Date, and Machine_ID filters

📊 Key Dashboard Screens
Production KPIs at a Glance

Monthly Trends of OEE

Machine Performance Overview

Downtime Analysis (Power Failure, Maintenance, Changeover, etc.)

Environmental Factors: Temperature & Pressure correlation

🖼️ Screenshots are available in the /screenshots folder or README image section

📌 Results & Insights
Average OEE ranged from 78% to 89%

Machines with frequent downtime had significantly lower availability

Power Failure and Changeovers were the most common downtime reasons

Higher pressure zones showed slightly reduced performance scores

✅ Conclusion & Key Takeaways
This project demonstrates how real-time monitoring and data analytics can transform manufacturing operations.

Power BI’s slicers and filters enable dynamic exploration of different machines, shifts, and time periods.

Even as a fresher, with a clear understanding of business metrics like OEE, we can build highly effective dashboards that drive insight and value.

Monitoring OEE consistently helps reduce unplanned downtimes and improve asset utilization in industrial setups.


✉️ Contact & Feedback
If you'd like to connect, collaborate, or offer feedback:

📧 scsofficial83@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/shivam-kaushik-856431228/

📁 GitHub: 

