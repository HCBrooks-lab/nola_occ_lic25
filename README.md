# New Orleans Business License Analysis

## Project Overview

This project analyzes active business license data for the City of New Orleans to understand **business growth trends, seasonality, and geographic concentration**. The goal is to turn raw public records into clear, decision‑ready insights using Python, pandas, and data visuals.

The analysis focuses on:

* How business openings change over time.
* Seasonal patterns (especially Q4 activity).
* The most common types of businesses.
* Where businesses are concentrated across the city.

---

## Dataset

* **Source:** City of New Orleans – Active Occupational Licenses
* **Records:** ~10,900 businesses
* **Time Range:** 2000–2026
* **Granularity:** Individual business license records

Basic cleaning was performed before analysis (column normalization, date parsing, ZIP cleanup, and removal of records missing required identifiers).

---

## Key Analyses & Visuals

### 1. Business Starts Over Time - Yearly (2000–2026)

This chart shows how many new businesses started each year. It highlights long‑term growth patterns and year‑to‑year fluctuations rather than focusing on individual business details.

![Businesses Starts Yearly](businesses_started_yearly.png)

---

### 2. Q4 Business Starts by Year - Q4 of Each Year

This chart focuses only on **Q4 (October–December)** business starts. Looking at Q4 separately helps reveal seasonal behavior tied to tourism, holidays, and year‑end planning.

![Q4 Business Starts by Year](q4_business_starts_by_year.png)

---

### 3. Top 10 Business Types in Q4 (2000–2026)

This bar chart shows the **most common business types that start during Q4** across all years. It highlights which industries are most active at year‑end.

![Top 10 Q4 Business Types](q4_top_10_business_types.png)

---

### 4. Year‑over‑Year Business Growth Trend

This line chart visualizes overall year‑over‑year changes in new business starts. It helps distinguish short‑term dips from longer‑term recovery and growth trends.

![Year‑over‑Year Growth Trend](yoy_business_growth_trend.png)

---

### 5. Geographic Business Density (Heatmap)

The heatmap shows where businesses are most concentrated across New Orleans. Warmer colors indicate areas with higher business density, while cooler colors show lighter activity.

![Business Density Heatmap](business_density_heatmap.png)

---

## Tools & Skills Used

* **Python** (pandas, matplotlib, seaborn)
* **Data Cleaning & Validation**
* **Time‑Series Analysis**
* **Geospatial Visualization (Folium heatmaps)**
* **Data Storytelling & Documentation**

---

## Key Takeaways

* Business activity shows clear **seasonal patterns**, with Q4 playing a significant role.
* A small number of business types account for a large share of licenses.
* Business density is **highly concentrated in specific ZIP codes**, reflecting commercial
  hubs.
* Long‑term trends provide more insight than single‑year changes.

---

## Notes

This project emphasizes **clarity over complexity**. Each chart answers a specific question, and overlapping visuals were intentionally avoided to keep the analysis focused and readable.
