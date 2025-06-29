# 🚲 Shared Bike Service Data Analysis — MiBici & CitiBike

This repository contains a data analysis project focusing on two major bike-sharing systems:
- **MiBici** in Guadalajara, Mexico  
- **CitiBike** in New York City, USA

The project explores user behavior, operational challenges, and data-driven strategies to improve service efficiency and profitability.

---

## 📁 Repository Structure

| File / Folder                 | Description                                                                 |
|------------------------------|-----------------------------------------------------------------------------|
| `Project Presentation.pdf`   | Final presentation summarizing key insights and visualizations             |
| `Project Documentation.pdf`  | Full project documentation with analysis, methods, and conclusions         |
| `Bike Sharing Service Data Analysis.ipynb`| Jupyter Notebook containing all data analysis, and visualization |
| `mibici_rides.parquet`       | MiBici user trip data (2015–2019)                                           |
| `citibike_rides.parquet`     | CitiBike trip data (June–December 2013)                                     |
| `mibici_stations.parquet`       | Mibici Station information   |

---

## 📊 Datasets Overview

### MiBici — Guadalajara, Mexico
- **Time Period**: January 2015 to December 2019  
- **Provider**: [MiBici Open Data Portal](https://www.mibici.net/es/datos-abiertos/)
- **Fields**:
  - `Viaje_Id`: Trip ID  
  - `Usuario_Id`: User ID  
  - `Genero`, `Año_de_nacimiento`: Gender and birth year  
  - `Inicio_del_viaje`, `Fin_del_viaje`: Trip start and end time  
  - `Origen_Id`, `Destino_Id`: Origin and destination station IDs  

### CitiBike — New York, USA
- **Time Period**: June 2013 to December 2013  
- **Provider**: [CitiBike System Data](https://citibikenyc.com/system-data)
- **Fields**:
  - Start and end time  
  - Station name and location  
  - Bike ID  
  - User age and gender  
  - User type (subscriber / casual)

---

## ❓ Business Questions Addressed

This project answers the following real-world business questions:

1. **Descriptive Statistics**  
   Summary statistics of available fields in both datasets.

2. **Marketing Strategy for Long-Distance Bikes**  
   Identify user segments more likely to benefit from bikes designed for longer trips.

3. **Predictive Maintenance**  
   Develop methods to proactively detect and flag faulty or worn-out bikes before user complaints.

4. **Company Growth & Demand Spread**  
   - Analyze whether the growth in trips is evenly distributed across the city.  
   - Identify contributing factors to demand spikes.

5. **User Segmentation for Pricing Strategy**  
   Classify users into "Loyal" vs. "Occasional" and study behavioral differences.

6. **Churn Detection**  
   Identify users whose ride frequency has declined and suggest personalized incentive packages.

7. **Revenue Optimization Simulation**
   - (a) Simulate increased revenue from better bike redistribution and calculate related costs.
   - (b) Evaluate the ROI of expanding the bike fleet or station count, using location-based analysis and sensitivity tests.

---

## 📌 Key Highlights

- Extensive use of **exploratory data analysis** and **visual storytelling**.
- Computed weekly/monthly KPIs, ride durations, and churn metrics.
- Applied **DuckDB** for efficient querying of large datasets.
- Simulated revenue impact of rebalancing strategies using business assumptions and cost models.
- Performed **sensitivity analysis** on profitability and investment decisions.

---

## 🚀 Getting Started

To run this project locally:

Clone the repository:
   ```bash
   git clone https://github.com/your-username/bike-sharing-analysis.git
   cd bike-sharing-analysis

This project was developed as part of the Data Analysis Bootcamp at **Rahnema College**. 
Special thanks to the instructors and mentors for their guidance.