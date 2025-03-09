# EDA_Optimising_NYC_Taxis_Utkarsh_Gaigole

# **README: NYC Taxi Data Analysis Notebook**

## **Project Overview**
This Jupyter Notebook (`EDA_Assg_NYC_Taxi_Completed.ipynb`) contains an **exploratory data analysis (EDA)** of New York City taxi trip data. The objective is to identify patterns in taxi demand, optimize fleet allocation, and propose data-driven strategies for improving operational efficiency and revenue generation.

## **Dataset Description**
The dataset contains yellow taxi trip records for NYC in 2023. Key features include:
- **Trip Details:** Pickup & drop-off locations, timestamps, trip distance.
- **Fare Information:** Total fare, tip amounts, surcharges, tolls.
- **Passenger Information:** Number of passengers per trip.
- **Operational Metrics:** Trip duration, speed, congestion charge.

## **Notebook Structure**
### **1. Data Preparation & Loading**
- Imports necessary Python libraries (`pandas`, `matplotlib`, `seaborn`, `numpy`).
- Loads the dataset and merges relevant files.
- Samples the data for efficient processing.

### **2. Data Cleaning**
- Handles missing values (e.g., imputation for `passenger_count`).
- Removes outliers in `trip_distance`, `fare_amount`, and `tip_amount`.
- Converts timestamps to `datetime` format and extracts key features like `pickup_hour` and `day_of_week`.

### **3. Exploratory Data Analysis (EDA)**
- **Trip Distribution:** Identifies busiest hours, days, and months for taxi demand.
- **Revenue Analysis:** Examines fare trends, tip patterns, and surcharge impacts.
- **Geospatial Insights:** Analyzes pickup/drop-off densities in key NYC zones.
- **Speed & Route Analysis:** Identifies slowest routes and peak traffic periods.

### **4. Key Findings & Insights**
- **Peak demand periods:** Evening rush (5 PM - 7 PM) and late nights (10 PM - 3 AM on weekends).
- **High-demand zones:** Midtown, JFK Airport, and Times Square.
- **Revenue patterns:** Nighttime trips generate higher revenue due to surcharges.
- **Trip inefficiencies:** Pickup/drop-off imbalances in certain locations.

### **5. Recommendations**
- **Dynamic Fleet Allocation:** Increase taxis in business hubs during morning/evening rush hours.
- **Demand-Based Pricing:** Introduce surge pricing during peak hours and discounts in low-demand zones.
- **Route Optimization:** Avoid congestion-heavy roads and use real-time traffic data for rerouting.
- **Incentives for Drivers:** Encourage more pickups in underutilized zones with bonus structures.

## **How to Run the Notebook**
### **Requirements**
- Python 3.7+
- Jupyter Notebook
- Required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `geopandas`

### **Steps to Execute**
1. Install necessary dependencies using:
   ```sh
   pip install pandas numpy matplotlib seaborn geopandas
   ```
2. Open Jupyter Notebook and load `EDA_Assg_NYC_Taxi_Completed.ipynb`.
3. Run each cell sequentially to generate insights and visualizations.

## **Output & Visualizations**
- Bar charts, line plots, and heatmaps displaying demand patterns.
- Geospatial maps highlighting high-demand pickup/drop-off locations.
- Correlation matrices analyzing relationships between fare, trip duration, and distance.

## **Next Steps**
- Extend the analysis to include **ride-hailing vs. taxi trends**.
- Implement **predictive modeling** for demand forecasting.
- Use **machine learning** to optimize pricing strategies based on real-time factors.

For further questions or modifications, please refer to the **report document** accompanying this analysis.
