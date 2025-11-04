## NOLA Occupational License Analysis
This project analyzes New Orleans occupational license data to show trends in business activity across the city from 2015 to 2025. Using Python and pandas, the analysis identifies seasonal patterns in business openings, highlights ZIP codes with the highest concentration of businesses, and explores how business types are distributed across the area. 

---

## Key Features
  # Data Cleaning & Preparation
  - Removed `business_name` entries to maintain data integrity.
  - Converted `business_start_date` to datetime format for time-based review.
  - Extracted `business_start_year` and `year_month` for temporal insights.

  # Trend Analysis
  - Visualized business openings from 2015-2025, showing seasonal surges.
  - Highlighted 6-month intervals for readability while keeping underlying trends.

  # ZIP Code Analysis
  - Identified the top 10 ZIP codes with the highest number of licensed businesses.
  - Visualized results using a horizontal bar chart to business clustering in zones with
    higher activity such as 70016, 70130, and 70119.

  # Notebook Organization
  - Markdown sections show/describe each step: data cleaning, feature extraction,
    visualization, and interpretation.
  - Sequential logic for easy reproducibility.

## Tools Used
  - Python (pandas, matplotlib)
  - Jupyter Notebook/VS Code
  - CSV Data Source: `active_occ_licenses_2025.csv`

---

## Visuals
# 1. Business Start Trends (2015-2025)
  This line chart visualizes how new business openings in the city have fluctuated over 
  the last decade. It shows possible seasonal surges tied to city events, tourism 
  patterns, or administrative cycles. 

  ![Business Start Trends](business_starts_trend.png)

# 2. Business Density Map (Interactive View)
  To show geographic context, an interactive density map was created using `folium`, 
  which shows spatial distribution of licensed businesses around New Orleans. Each
  point represents a business, with clusters showing areas of high concentration, often 
  near commercial or tourist areas. 
  
  ![View the Interactive Business Density Map](business_map.png)

---

## Future Additions & Target Timeline
# 1. Business Type by ZIP Code Heatmap - By 11-10-25. 
# 2. Expanded Interactive Map (Folium) - By 11-15-25.
# 3. Year/Year Growth - By 11-20-25. 
# 4. Optional Dashboard - By 11-30-25. 

### Purpose of Roadmap
These milestones outline a clear path for continuing project development while demonstrating:
- Consistent use of data visualization and storytelling.
- Growth into geospatial and dashboarding tools for analytics communication.
- Realistic time management and project planning. 






