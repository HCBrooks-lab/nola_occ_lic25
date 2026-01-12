## NOLA Occupational License Analysis
This project analyzes New Orleans occupational license data to show trends in business activity across the city from 2015 to 2025. Using Python and pandas, the analysis identifies seasonal patterns in business openings, highlights ZIP codes with the highest concentration of businesses, and explores how business types are distributed across the area. 

## How to Read This Project
This analysis is organized to move from data cleaning and exploration into geographic and
trend-based insights, with each visual tied to a specific business or policy question. 
- Queries are written for maintainability and clarity over cleverness.
- Each file is self-contained.
- Comments describe business purpose, not just SQL mechanics. 

---

## Key Findings
- A small number of business license types account for a disproportionate share of overall 
  business activity in New Orleans, which indicates concentration in specific industries.
- Business density shows clear geographic clustering rather than uniformed distribution
  across the city. 
- These patterns give actionable insight for city planning, economic development
  initiatives, and area-based market research. 

---

## Key Features
  # Data Cleaning & Preparation
  - Removed `business_name` entries to maintain data integrity.
  - Converted `business_start_date` to datetime format for time-based
    review.
  - Extracted `business_start_year` and `year_month` for temporal insights.

  # Trend Analysis
  - Visualized business openings from 2015-2025, showing seasonal surges.
  - Highlighted 6-month intervals for readability while keeping underlying
    trends.

  # ZIP Code Analysis
  - Identified the top 10 ZIP codes with the highest number of licensed businesses.
  - Visualized results using a horizontal bar chart to business clustering in zones with
    higher activity such as 70016, 70130, and 70119.

  # Notebook Organization
  - Markdown sections show/describe each step: data cleaning, feature extraction,
    visualization, and interpretation.
  - Sequential logic for easy reproducibility.

---

## Tools Used
  - Python (pandas, matplotlib)
  - Jupyter Notebook/VS Code
  - CSV Data Source: `active_occ_licenses_2025.csv`

---

## Visuals
# 1. Business Start Trends (2015-2025)
  <!-- Updated Business Starts trend chart coming soon -->

# 2. Business Density Map (Interactive View)
  <!-- Updated Interactive Map coming soon -->

---

## Key Enhancements & Recent Updates
- Added Q4 focused analysis identifying the most common business types starting between Oct-
  Dec.
- Used logic selecting the most recent year with sufficient Q4 records to avoid sparse or
  misleading results.
- Cleaned and validated business start dates, handling sentinel/invalid values.
- Improved business type aggregation/labeling for clearer categorical comparisons.
- Generated/saved publication-ready bar charts for portfolio and README use. 

---

## Potential Extensions
- Optional dashboard for high-level summary insights (e.g. Power BI or Streamlit)
- Deeper temporal analysis (e.g. seasonal trends after Q4) 

---

### Purpose of Roadmap
These milestones outline a clear path for continuing project development while showing examples of:
- Consistent use of data visualization and storytelling.
- Growth into geospatial and dashboarding tools for analytics communication.
- Realistic time management and project planning. 






