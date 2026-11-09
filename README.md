# Smart City Bike Sharing Analysis using Power BI

## 1. Project Overview

This project focuses on analysing Smart City Bike Sharing data using Microsoft Power BI. The objective is to transform raw data into meaningful insights through data cleaning, data modelling, DAX calculations, and interactive visualizations.

The dashboard provides insights into bike availability, station capacity, station status, and bike distribution across different cities.

## 2. Problem Statement

The bike-sharing system generates a large amount of station-level data, including bike availability, station capacity, station status, and location details. Analysing this data manually makes it difficult to understand bike distribution, monitor station performance, and identify availability patterns across different cities.

This project uses Power BI to transform raw bike-sharing data into meaningful insights and support efficient bike-sharing system management.

## 3. Project Objectives

- Analyse bike availability across different cities.
- Monitor station capacity and availability.
- Identify open and closed stations.
- Compare bike distribution across cities.
- Analyse station occupancy patterns.
- Explore future bike availability trends.

## 4. Dataset Information

The dataset contains bike-sharing station details and historical availability snapshots.

**Key Attributes:**

- Station_ID: Unique station identifier.
- Station_name: Name of the bike station.
- Address: Station location.
- Latitude: Geographical latitude.
- Longitude: Geographical longitude.
- Banking: Indicates banking facility availability.
- Bonus: Indicates bonus station status.
- Status: Station operating status.
- Contract Name: City or contract name.
- Total_capacity: Total station capacity.
- Available Bikes: Number of available bikes.
- Available Bike Stands: Number of empty bike stands.
- Last Updated: Date and time of the recorded snapshot.

## 5. Tools and Technologies

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Microsoft Excel

## 6. Data Cleaning and Preprocessing

The following data preparation steps were performed:

- Checked for missing and null values.
- Checked duplicate records.
- Cleaned and formatted text columns.
- Changed columns to appropriate data types.
- Split geographical position into latitude and longitude.
- Created a capacity validation column.
- Prepared the dataset for analysis and visualization.

## 7. Data Modelling and DAX

Created a relational data model using:

- Bike_raw: Main bike availability and station snapshot table.
- Bike_station: Station-related information.
- Dim_City: City or contract information.

Created DAX measures to calculate key performance indicators:

- Total Stations
- Total Bike Capacity
- Available Bikes
- Available Empty Stands
- Bike Occupying Rate
- Open Stations
- Closed Stations
- Average Available Bikes

## 8. Dashboard Visualizations

The interactive Power BI dashboard includes:

- KPI Cards: Display key performance indicators.
- Bar Chart: Compare bike capacity across cities.
- Donut Chart: Show station status distribution.
- Column Chart: Analyse bike availability by city.
- Bar Chart: Compare bike occupancy rates.
- Combo Chart: Analyse station-level performance.
- Map Visual: Display geographical station locations.
- Slicers: Filter data by city, station, and date.

## 9. Predictive Analysis

Predictive analysis explores future bike availability using historical station snapshots.

The analysis focuses on:

- Forecasting future bike availability.
- Identifying stations that may experience bike shortages.
- Analysing historical availability trends.
- Supporting station capacity planning.
- Improving bike redistribution decisions.

Note: Predictions are estimates based on historical availability patterns. Actual customer demand cannot be directly predicted because the dataset does not contain individual rental transactions.

## 10. Key Insights

The dashboard helps identify:

- Bike availability differences across cities.
- Stations with higher and lower bike availability.
- Open and closed station distribution.
- Station capacity and occupancy patterns.
- Potential bike availability shortages.
- Geographical distribution of bike-sharing stations.

## 11. Conclusion

This project demonstrates the use of Microsoft Power BI for analysing Smart City Bike Sharing data. Through data cleaning, data modelling, DAX calculations, and interactive visualizations, the dashboard provides meaningful insights into bike availability and station performance.

The analysis supports better resource allocation, station capacity planning, and operational decision-making.
Project Tool: Microsoft Power BI

Project Type: Data Cleaning, Data Modelling, Data Visualization and Predictive Analysis
