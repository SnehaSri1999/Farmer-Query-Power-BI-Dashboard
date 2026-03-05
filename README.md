# Farmer Query Analysis Dashboard (Kisan Call Centre)

## Overview
This project analyzes farmer queries recorded by the Kisan Call Centre (KCC) to identify patterns in agricultural concerns across regions, crops, and time periods. An interactive Power BI dashboard was built to explore query trends and provide insights into the most common issues raised by farmers.

The objective is to demonstrate practical data analysis and visualization skills using real-world government data.

---

## Dataset
**Source:** Government of India Open Data Portal (data.gov.in) – Kisan Call Centre Dataset  

**Dataset size:** ~100,000 records

### Key fields include:

- **StateName** – State where the query originated  
- **DistrictName** – District of the farmer  
- **BlockName** – Administrative block  
- **Sector** – Agriculture or related sector  
- **Category** – Agricultural category (e.g., cereals, oilseeds)  
- **Crop** – Crop referenced in the query  
- **QueryType** – Type of concern (weather, government schemes, nutrient management, etc.)  
- **QueryText** – Description of the farmer's issue  
- **CreatedOn** – Timestamp of query registration  
- **Year / Month** – Extracted temporal fields for trend analysis  

---

## Data Preparation

Data preparation was performed using **Power BI tools**:

- Cleaned inconsistent categorical values  
- Removed null or incomplete records  
- Extracted **Year and Month** fields from timestamp data  
- Standardized crop and category values  
- Prepared dataset for dashboard visualizations  

---

## Dashboard Features

An interactive dashboard was developed in **Power BI** to explore farmer query patterns.

### Key components include:

- **KPI card** showing total queries raised  
- **Geographic map** visualizing query distribution by state  
- **Query type distribution chart** showing common farmer concerns  
- **Crop-wise query analysis**  
- **Time-series visualization** of query trends across years  

### Interactive Filters

- Sector  
- Crop  
- Block Name  
- Date range  

These features allow users to dynamically explore query patterns across multiple agricultural dimensions.

---

## Key Insights

Exploratory analysis revealed several patterns:

- Certain crops such as **wheat and mustard generate higher query volumes**.  
- **Government scheme and weather-related queries** are among the most frequent concerns.  
- Query distribution varies significantly across different regions.  
- Some districts consistently report higher volumes of farmer queries.  

---

## Tools Used

### Data Visualization
- Power BI

### Data Transformation
- Power Query

---
