# Excel-Project-Hub

## Dataset Used
<a href="https://github.com/subhsuliya/Excel-Project-Hub/blob/main/Project.xlsm">Data Set</a>

## Dashboard screenshot
<a href="https://github.com/subhsuliya/Excel-Project-Hub/blob/main/Screenshot%202026-08-25%20113647.png">Dashboard image</a>


This repository features an interactive Excel analytics project that combines dynamic reporting dashboards, pie chart category breakdowns, and custom VBA macros. It is designed to transform raw datasets into clear visual insights while automating repetitive data processing tasks to streamline decision-making.

This repository features an interactive Excel dashboard for city-based sales analysis, utilizing VBA macros and pivot tables to track sales executive performance.
Key Features
Interactive City Filtering: Includes slicers to instantly filter data across major cities such as Chennai, Delhi, Mumbai, Nagpur, Patna, Pune, Ranchi, and Surat as shown in Screenshot 2026-08-25 113602.png.

##Looking for Dashboard Lets Connect!!!!!!!!!!!

<img width="1498" height="869" alt="Screenshot 2026-08-25 113647" src="https://github.com/user-attachments/assets/fa3d6187-b6e2-439d-8f21-b0acdda698ea" />

Dynamic View Controls: Features interactive checkbox toggles allowing users to switch between distinct dashboard modules (Dashboard 1 through Dashboard 4) directly on the sheet based on Screenshot 2026-08-25 113602.png.
Executive Performance Metrics: Tracks and displays exact figures for "Total Sales", "Target Hit % Wise", and "Away From Target %" for individual sales executives as seen in Screenshot 2026-08-25 113602.png.
Visual Analytics: Incorporates horizontal bar charts for total sales comparisons, pie charts for distribution, and line charts to track variance from sales targets as shown in Screenshot 2026-08-25 113602.png 

Technical Components
VBA Automation: The workbook contains an embedded VBA project (vbaProject.bin) to power the interactive checkboxes and automated data routines.  
Data Modeling: The backend utilizes multiple Pivot Tables (pivotTable1.xml through pivotTable4.xml) and Pivot Caches to efficiently aggregate and calculate the sales metrics.  
Slicer Integrations: The city filtering system is driven by underlying slicer caches (slicerCache1.xml) connected to the data models.  
Chart Objects: The visual elements are built using embedded, styled chart XML files (chart1.xml, chart2.xml, chart3.xml) that update dynamically as data is filtered.  
