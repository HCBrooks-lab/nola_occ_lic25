# NOLA Occupational Licenses (2025)
This project analyzes New Orleans business license data to uncover trends in when businesses offically began operations. 


---


## Sample Visualization

![Business Start Trends](business_starts_trend.png)


---


## Dataset

- **Source**: [City of New Orleans Open Data Portal](https://data.nola.gov/)
- **Dataset**: *Active Occupational Licenses*
- **Last Updated**: June 12, 2025
- **File**: 'active_occ_licenses_2025.csv'


---


## Project Objective

- Perform exploratory data analysis (EDA) on business start dates
- Visualize trends in business formation over time
- Compare historical trens vs. recent activity (e.g., 2000-2025)


---


## Current Analysis Highlights 

- Parsed & converted business start dates to datetime format
- Extracted year component for trend analysis
- Created bar charts showing:
  - Total number of businesses started each year (1900-2025)
  - Recent growth from 2000 onwward
 
---


## Insights & Takeaways

- **Post-2005 Recovery:** A noticeable increase in business openings follows
  2005, potentially reflecting New Orleans' gradual recovery after Hurricane
  Katrina and local development efforts.

- **Steady Growth Trend (2010-2019):** Business formation steadily rose
  througout the 2010's, suggesting growing entrepreneurial activity or
  improved economic conditions.

- **Pandemic Impact (2020):** A slight dip in 2020 aligns with the start of
  COVID-19, likely reflecting uncertainty or shutdown-related delays in new
  business launches.

- **Strong Rebound(2021-2025):** A surge in new businesses from 2021 onward
  reflect post-pandemic resilience, more remote work/startup flexibility,
  or renewed interest in local economic participation. 


---


## Files Included

- 'README.md' | Project overview, datasat summary, goals, tools used, and
   future additions.
- 'business_starts_trend.png' | Bar chart visualizing the number of new
   businesses started each year from 2000-2025.
- `active_occ_licenses_2025.csv` | Raw dataset downloaded from data.nola.gov 
- `nola_occ_lic_analysis.ipynb` | Jupyter Notebook containing the data
   analysis and visualizations.


---


## Tools Used

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Git and Github


---


## Future Additions

- Breakdown by business type or ZIP code.
- Mapping business density with latitude/longitude. 
- Insights into post-COVID trends or economic recovery.


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
