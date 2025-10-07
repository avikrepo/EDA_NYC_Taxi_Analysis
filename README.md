# 🗽 EDA on NYC Taxi Trip Data

### Author: Avik Ghosh  
**Role:** Data Analyst | Automation Engineer  
**Notebook:** `EDA_NYC_Taxi_Analysis_Avik_Ghosh.ipynb`

---

## 📘 Project Overview

This project performs an **Exploratory Data Analysis (EDA)** on the **New York City Taxi Trip dataset** to uncover insights into passenger behavior, fare structures, trip patterns, and revenue trends.  

The goal is to understand operational inefficiencies, identify revenue opportunities, and support data-driven decision-making for optimizing taxi services in NYC.

---

## 🎯 Objectives

- Clean and preprocess raw trip data.  
- Identify and handle missing, zero, or negative values.  
- Analyze fare components such as tips, surcharges, and tolls.  
- Study trip distance, duration, and passenger count distributions.  
- Explore temporal patterns (hourly, daily, monthly trends).  
- Investigate geographical trends using pickup/drop-off zones.  
- Visualize correlations and relationships between numerical variables.  
- Derive actionable insights to improve operations and pricing strategies.

---

## 🧩 Dataset Description

**Dataset Source:** NYC TLC (Taxi & Limousine Commission) trip record data.  
**Data Fields (sample):**
- `VendorID`
- `passenger_count`
- `trip_distance`
- `RatecodeID`
- `PULocationID`, `DOLocationID`
- `payment_type`
- `fare_amount`, `extra`, `mta_tax`, `tip_amount`, `tolls_amount`
- `improvement_surcharge`, `total_amount`, `congestion_surcharge`, `airport_fee`
- `pickup_datetime`, `dropoff_datetime`

**Data Volume:** Sample of ~300,000 rows extracted for analysis.

---

## 🧮 Tools & Libraries Used

| Purpose | Libraries |
|----------|------------|
| Data Manipulation | pandas, numpy |
| Visualization | matplotlib, seaborn, plotly |
| Data Cleaning | pandas, datetime |
| Environment | Jupyter Notebook (Python 3.x) |

---

## ⚙️ Steps Performed

1. **Data Import & Overview**
   - Loaded NYC Taxi dataset.
   - Checked dataset dimensions, column types, and null values.

2. **Data Cleaning**
   - Removed duplicate entries.
   - Handled missing, zero, and negative values in key columns.
   - Converted datetime fields and derived new temporal columns (hour, weekday, month).

3. **Feature Engineering**
   - Added new features such as trip_duration, pickup_hour, and tip_percentage.

4. **Exploratory Analysis**
   - Analyzed passenger count and trip distance distributions.
   - Visualized fare and tip amount patterns.
   - Explored surcharges and their frequency by location and time.
   - Compared revenue across day vs night trips.

5. **Statistical Insights**
   - Correlation matrix and pairwise relationships between numerical features.
   - Detection of potential outliers and data quality checks.

6. **Visualization**
   - Used bar charts, histograms, heatmaps, and scatter plots for clear representation.

---

## 📊 Key Insights

- Majority of trips have 1–2 passengers and short distances (<5 miles).  
- Nighttime trips show higher revenue per mile due to surcharge and tip behavior.  
- Zero or near-zero distances often correspond to same-zone pickups.  
- Tip percentage positively correlates with trip distance and fare amount.  
- Surcharges vary significantly across pickup zones and times of day.

---

## 🚀 How to Run This Notebook

1. **Clone the Repository**
   ```bash
   git clone https://github.com/<your-username>/EDA_NYC_Taxi_Analysis.git
   cd EDA_NYC_Taxi_Analysis
   ```

2. **Install Required Packages**
   ```bash
   pip install -r requirements.txt
   ```

3. **Open the Notebook**
   ```bash
   jupyter notebook EDA_NYC_Taxi_Analysis_Avik_Ghosh.ipynb
   ```

4. **Run All Cells**
   - Follow the markdown explanations and execute each code cell sequentially.

---

## 📈 Future Scope

- Incorporate geospatial visualization using Folium or GeoPandas.  
- Apply statistical hypothesis testing on fare and tip variations.  
- Extend analysis to predictive modeling (e.g., fare estimation, demand forecasting).  
- Automate report generation using Python scripts.

---

## 👤 Author

**Avik Ghosh** 


