# Data-Analysis-Task-3
Project Overview
This project turns raw CSV data into an easy-to-understand, interactive report.
Anyone—whether a manager, analyst, or student—can click through the visuals and instantly see:
• Total Sales and Profit at a glance
• How sales change month by month
• Which regions and products perform best
• Detailed breakdowns with the ability to drill down into the numbers

Key Features
• Cards – Show high-level KPIs such as Total Sales, Total Profit, and Total Orders
• Stacked Column Chart – Compare regional or product sales contributions over time
• Line Chart – Reveal monthly or quarterly sales trends and seasonal patterns
• Matrix Table – Provide a detailed, filterable view of sales by product and region

Dataset
Format: CSV
Fields: Date, Product, Region, Sales, Profit, Quantity (and a few others)
Cleaning Steps: Removed duplicates, handled missing values, standardized column names.

Note for Non-Technical Readers:
The data is just a table—like a clean Excel sheet.
Power BI turns that table into interactive visuals without writing code.

How I Built It

Data Import: Loaded the CSV directly into Power BI

Data Prep: Used Power Query to remove nulls and format data types

Modeling: Set up relationships between tables if required

Visualization: Added Cards, Stacked Column Chart, Line Chart, and Matrix

Interactivity: Applied slicers and filters so users can explore by time, product, or region

Insights
• Region X consistently leads in sales
• Product A is the top revenue generator
• Noticeable sales dips occur in low-season months, suggesting marketing opportunities

How to View / Run

Quick View for Non-Technical Users
• Download the .pbix file from this repository
• Open with the free Power BI Desktop application
• Click through the visuals—no coding required
