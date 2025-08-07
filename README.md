# NOLA Occupational Business Licenses (2025)
This project analyzes New Orleans business license data to uncover trends in when businesses officially began operations. 

---

## Dataset

- **Source**: [City of New Orleans Open Data Portal](https://data.nola.gov/)
- **Dataset**: *Active Occupational Licenses*
- **File**: 'active_occ_licenses_2025.csv'

---

## Current Highlights 

- Parsed & converted business start dates.
- Extracted year & month for trend and seasonal analysis. 
- Visualized:
  - Trends by year.
  - Business openings after Hurricane Katrina (2006-Present).
- Interactive business density map using Folium & MarkerCluster. 


## Sample Visualizations

![Business Start Trends](business_starts_trend.png)

- To provide geographic context, and interactive map was added using 'folium'
  showing the density of businesses across New Orleans. Each dot on the map
  represents a business, and clusters highlight areas of activity. This
  visualization helps identify commercial zones and areas with potential saturation
  or opportunity.

![View the Interactive Business Density Map](business_map.png)

---

## Project Objective

- Perform exploratory data analysis (EDA) on business start dates
- Visualize trends in business formation over time

---

## Insights & Takeaways

- **Post-2005 Recovery:** Noticeable rise after Hurricane Katrina
- **Steady Growth (2010-2019):** Strong entrepreneurial activity
- **Pandemic Impact (2020):** Small dip in openings 
- **Strong Rebound(2021-2025):** Significant growth
- **Interactive Map:** Built using folium and MarkerCluster, visualizing business
  concentration across the city. Data points include business names as popup markers.
  Map centers on average coordinates in New Orleans.
  **[Open Interactive Map](https://spontaneous-salamander-630181.netlify.app/)**
- **Geographic Anomalies:** Some licenses reflect Texas/West Africa addresses (HQ in
  New Orleans or remote offices). 

---

## Future Additions/Progress Tracker

- Breakdown by business type or ZIP code (completed).
- Outlier & anomoly detection. 
- Insights into post-COVID trends or economic recovery.

---

## Tools Used

- Python, Pandas, Matplotlib, Folium, MarkerCluster
- Jupyter Notebook/VS Code
- Git & GitHub
- Leaflet | OpenStreetMap

---

## Files Included

- nola_occ_lic_analysis.ipynb: Analysis & visualizations
- active_occ_licenses_2025.csv: Dataset
- business_starts_trend.png: Yearly trends chart
- business_map.png: Business density map

---

## Understanding the Dataset Columns

The dataset includes 20 fields related to licensed businesses in New Orleans, such as:
- Business name & address
- License type & ID
- Start date & owner
- Location coordinates (latitude, longitude, GIS point)

Full column description and sample values are available in the [nola_occ_lic_analysis.ipynb](./nola_occ_lic_analysis.ipynb)). 

---

*This project is part of an entry-level data analysis portfolio. For questions or collaboration, feel free to reach out!*
