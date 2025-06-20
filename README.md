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


## Files Included

- `active_occ_licenses_2025.csv` | Raw dataset downloaded from data.nola.gov 
- `nola_occ_lic_analysis.ipynb` | Jupyter Notebook containing the data analysis and visualizations.


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

Full column descriptin and sample values are available in the [Jupyter Notebook](nola_occ_lic_analysis.ipynb).


---


*This project is part of an entry-level data analysis portfolio. For questions or collaboration, feel free to reach out!*
