# 💧 Maji Ndogo Water Improvement Project Dashboard

## 🎥 Project intro (Video)
---
[![Watch a quick video on maji Ndogo water crisis](https://img.youtube.com/vi/tEWnInICDHU/0.jpg)](https://youtu.be/tEWnInICDHU)All the credit goes to ALX Africa.

## Introduction
This is a power Bi project on friction imaginary water project in **Maji Ndogo**.
This project is to analyse the transformation journey of **Maji Ndogo** water crisis, and to track the impact of the National water source improvement initiative and spending across **Maji Ndogo**.
The dashboard was built in response to a need for public transparency and executive decision-making support.

**_Disclaimer_** : _All datasets and reports do not represent the real community but just a friction for learning and to show my skills in power Bi._

## ❓ Problem Statement
Despite significant funding, decision-makers and the public lacked a clear way to track:
1.  Where improvements were happening?
2.  How funds were being spent?
3.  Which vendors were responsible?
4.  What impact the upgrades in their town?
5.  What the money was spent on?
6.  How the project is going and which sources have been completed?

## 🧠 Skills/ concepts demostrated:
The following power Bi features were used:
- Data cleaning and transformation using power query editor.
- Updating the dataset using Data source setting.
- Advanced DAX calculations (e.g., project_progress %, budget vs. cost, basic access).
- Custom Map Visulalizations with shape JSON.
- Slicer interaction and drillthrough pages.
- Data Modelling (checking relationship and directionality).
- Performance optimization(removal of unused columns and tables).

 ## 🔍 Data Sourcing
  Data was provided via Excel spreadsheets:
 - Md_water_services_data.xlsx – core project dataset (containing 7 tables)
   1. Infrastructure_cost (12 rows and 3 columns)
   2. Location (39,650 rows and 4 columns)
   3. Projecct_progress (25398 rows and 13 columns)
   4. Visit (60,146 rows and 9 columns)
   5. Water_source (39,650 rows and 5 columns)
   6. Well _pollution( 17,383 rows and 2 columns)
 - External vendor data (95rows and 4 columns)
 - Updated completion and financial records (2023–2024).
 - Custom shape map JSON was used for geographic visualization at town, provincial, and national levels.
   
 ## 🧹 Data Transformation
  Key transformation steps:
- Removed unused or irrelevant columns and tables like 'address', 'comments', 'pollutant_ppm', 'date', 'queue_composition' and 'water_source_related_crime'
- Updated the dataset
- Merged vendor data using 'assigned_vendor' field.
- Fixing the budgeted_improvement_cost column in the project_progress table broken by the updated data using DAX
- Create a measure for total_number_of_improvement
  
 ##  🧱 Modeling
 Power Bi automatically connected related tables. 
 - create a connection between project_progress table and vendor
 - check the relationship and directionality between water_source and project_progress
 - Use of ALLEXCEPT() for filtering by town
 Key calculated Measure
- Total_improvement
- Pct_project_complete
- Population_now_access
- Cumulative_budget vs cumulative_cost

 ##  📊 Analysis & Actualization
 The dashboard consists of multiple pages:
📍 National Overview(Page 1)
- % of population now with basic water access
- Budget vs. Actual Spend (KPI card)
- Map of project progress by town
- Cost breakdown by improvement type and province

📌 Key Indicators (Page 2)
 - Vendor cost comparisons
 - High-cost vendors vs low-cost

Top contributing provinces to budget overrun
- Average Cost of Improvement (Page 3)
- Comparison by:
  Province
  Improvement Type
  Rural vs. Urban

 # Insights:
Sokoto province is nearly 40% over budget due to terrain and travel time.
48% of the population now has basic water access and 22% complete (up from 34%) in 5 years.
Most expensive vendors are operating in the toughest regions, not necessarily overcharging.

## 🔚 Conclusion
This dashboard bridges the gap between field operations and funding stakeholders by:
Making spending visible
Tracking improvements geographically and over time
Helping decision-makers allocate resources efficiently

   

