# Zomato Data Analytics

**Project:** Zomato Data Analytics — Power BI Dashboard  
**Author:** Subhisha C

## Overview
This Power BI report analyzes Zomato restaurant data to uncover key insights across cities, cuisines, 
pricing, and customer ratings. The dashboard provides interactive visuals and supporting DAX measures to help 
stakeholders identify trends, top-performing restaurants, and opportunities for business optimization.

## Key Features
- City-wise restaurant and rating distribution
- Most popular cuisines and top restaurants
- Average cost for two by city and cuisine
- Rating vs. price correlation and outlier detection
- Interactive filters (city, cuisine, rating range)
- Cleaned and transformed dataset using Power Query
- Reusable DAX measures for aggregations and KPIs

## Files in this folder
- `Zomato_Analytics_dashboard_PBI.pbix` — Power BI report file (main dashboard)
- `data/` — (optional) cleaned CSV / sample data used for the report
- `README.md` — project overview (this file)
- `screenshots/` — (optional) screenshots of the dashboard for quick preview

## Technical Details
- Tools: Power BI Desktop, Power Query, DAX
- Sample DAX measures:
  dax
  Total Restaurants = COUNTROWS('Zomato')
  Average Rating = AVERAGE('Zomato'[Aggregate_rating])
  AvgCostForTwo = AVERAGE('Zomato'[Average_Cost_for_two])
