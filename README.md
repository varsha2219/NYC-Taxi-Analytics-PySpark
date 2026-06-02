# NYC Taxi Analytics using PySpark & Power BI

## Project Overview

This project analyzes over 3.3 million NYC Yellow Taxi trips using PySpark and Power BI.

The objective was to identify revenue trends, customer behavior, payment preferences, and location-based demand patterns through large-scale data processing and business intelligence reporting.

---

## Technologies Used

- PySpark
- Spark SQL
- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab
- Power BI

---

## Dataset

Dataset: NYC Yellow Taxi Trip Records (January 2025)

Records Processed: 3,330,787

Source:
https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

File Used:
yellow_tripdata_2025-01.parquet

---

## Project Workflow

### 1. Data Loading

- Loaded NYC Taxi dataset into PySpark
- Explored schema and data types

### 2. Data Cleaning

- Checked duplicate records
- Removed negative fare amounts
- Removed negative total amounts
- Handled null values
- Validated passenger counts

### 3. Feature Engineering

Created new columns:

- trip_duration_minutes
- pickup_hour
- pickup_day
- pickup_month
- pickup_weekday
- tip_percentage
- revenue_per_mile

### 4. Performance Optimization

- Used cache()
- Used repartition()
- Analyzed execution plan using explain()

### 5. Business Analysis

Performed:

- Revenue Analysis
- Customer Behavior Analysis
- Payment Analysis
- Location Analysis
- Time-Based Analysis

### 6. Dashboard Development

Built an interactive Power BI dashboard containing:

- Executive Overview
- Customer Behavior & Payment Analysis
- Location Intelligence & Revenue Insights

---

## Key Findings

### Revenue Insights

- Peak revenue occurs between 4 PM and 7 PM.
- Evening hours generate the highest earnings.
- Revenue drops significantly during early morning hours.

### Customer Insights

- Single-passenger trips dominate demand.
- Average tip percentage is approximately 20%.
- Customers tip most during evening hours.

### Payment Insights

- Credit card payments account for approximately 73% of trips.
- Cash payments account for approximately 11% of trips.

### Location Insights

- Manhattan generates the highest revenue.
- Midtown Center is the busiest pickup zone.
- JFK Airport and LaGuardia Airport are major demand hubs.

---

## Dashboard Pages

### Page 1: Executive Overview

- Total Revenue
- Total Trips
- Average Fare
- Average Distance
- Average Duration
- Revenue by Hour
- Trips by Weekday

### Page 2: Customer Behavior & Payment Analysis

- Payment Distribution
- Passenger Distribution
- Revenue by Passenger Count
- Average Tip Percentage by Hour

### Page 3: Location Intelligence & Revenue Insights

- Revenue by Borough
- Borough Trip Share
- Top Pickup Zones
- Top Revenue Zones

---

---

## Business Recommendations

- Increase fleet availability during evening peak hours.
- Prioritize vehicle allocation in Manhattan.
- Expand digital payment and loyalty programs.
- Deploy additional taxis near airports and high-demand zones.
- Increase driver incentives during peak demand periods.

---

## Results

This project demonstrates:

- Big Data Processing using PySpark
- Data Cleaning & Transformation
- Feature Engineering
- Spark Performance Optimization
- Business Analytics
- Power BI Dashboard Development
- Data Storytelling

---

## Author

Varsha K T
