# 💧 Maji Ndogo Water Improvement Project Dashboard

## 🎥 Project intro (Video)
---
[![Watch a quick video on maji Ndojo struugle](https://img.youtube.com/vi/tEWnInICDHU/0.jpg)](https://youtu.be/tEWnInICDHU)All the credit goes to ALX Africa.

## Introduction
This is a power Bi project on friction imaginary water project in **Maji Ndojo**.
This project is to analyse the transformation jouney of *Maji Ndojo** water crisis,and to track the impact of the National water source improvement initiative and spending across **maji Ndojo.
The dashboard was built in response to a need for public transparency and executive decision-making support.
**_Disclimar_** : _All datasets and reports do not represent the real community but just a friction for learning and to show my skills in power Bi._

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
 - Md_water_services_data.xlsx – core project dataset.
 - External vendor data.
 - Updated completion and financial records (2023–2024).
 - Custom shape map JSON was used for geographic visualization at town, provincial, and national levels.
   
 ## 🧹 Data Transformation

Key transformation steps:
- Removed unused or irrelevant columns and tables like 'address', 'comments', 'pollutant fields', 'queue_composition' and 'water_source_related_crime'.
- Standardized town names by appending province codes.
- Merged vendor data using 'assigned_vendor' field.
- Handled missing dates and blank records with conditional logic in DAX


