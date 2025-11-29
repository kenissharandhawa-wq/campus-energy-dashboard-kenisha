# Campus Energy-Use Dashboard - Kenisha Randhawa

**Capstone Project** | Programming for Problem Solving using Python  
## Objective
Built a complete end-to-end energy monitoring dashboard for campus facilities using simulated real meter data.

## Dataset
- Source: Synthetic hourly energy consumption data (2015–2018)  
- Buildings: A (Academic), B (Hostel), C (Admin/Labs)  
- Columns: timestamp, kwh (consumption)

## Features Implemented
- Automatic ingestion of multiple building CSV files with exception handling  
- Full OOP design (Building class for tracking)  
- Daily/weekly aggregations using groupby & resample  
- Beautiful 4-panel dashboard with trend, comparison, peak analysis  
- Automated CSV export + executive summary  

## Key Insights
- Highest consumer: Building B (hostel, ~40% total usage)  
- Peak hours: 5-9 PM evenings  
- Total consumption: ~12 million kWh over 4 years  

## Files
- `energy_dashboard-checkpoint.ipynb` - Main code  
- `data/` - 3 building CSV files  
- `output/` - Cleaned data + summary  
- `dashboard.png` - Final visualization  

**Submitted by: Kenisha Randhawa**  
**Date: November 29, 2025**
