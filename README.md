# Module-2-end-assignment
Smart City Bike Sharing Analysis using Power BI

Project Overview

This project focuses on analysing Smart City Bike Sharing data using Microsoft Power BI. The objective is to transform raw bike-sharing data into meaningful insights through data cleaning, data modelling, DAX calculations, and interactive visualizations.

The dashboard helps understand bike availability, station capacity, station status, and distribution patterns across different cities.

Problem Statement

The bike-sharing system generates a large amount of station-level data, including bike availability, station capacity, station status, and location details. Analysing this data manually makes it difficult to understand bike distribution, monitor station performance, and identify availability patterns across different cities.

This project transforms raw bike-sharing data into meaningful insights using Power BI to support better decision-making and efficient bike-sharing system management.

Objectives

Analyse bike availability across different cities.

Monitor station capacity and availability.

Identify open and closed bike stations.

Compare bike distribution across cities.

Analyse station occupancy patterns.

Explore future bike availability trends using forecasting.

Dataset Information

The dataset contains bike-sharing station information and availability snapshots.

Key attributes include:

Column

Description

Station_ID

Unique station identifier

Station_name

Name of the bike station

Address

Station location

Latitude

Geographical latitude

Longitude

Geographical longitude

Banking

Indicates whether banking facilities are available

Bonus

Indicates bonus station status

Status

Current recorded station status

Contract Name

City or contract name

Total_capacity

Total bike station capacity

Available Bikes

Number of available bikes

Available Bike Stands

Number of empty bike stands

Last Updated

Date and time of the recorded snapshot

Tools and Technologies

Microsoft Power BI

Power Query

DAX (Data Analysis Expressions)

Microsoft Excel

Data Cleaning and Preprocessing

The following data preparation activities were performed:

Removed duplicate records where appropriate.

Checked for missing and null values.

Cleaned and formatted text columns.

Converted columns into appropriate data types.

Split geographical position into latitude and longitude.

Created a capacity validation column.

Prepared the data for analysis and visualization.

Data Modelling

A simple relational data model was created using:

Bike_raw: Main bike availability and station snapshot table.

Bike_station: Station-related information.

Dim_City: City or contract information.

Relationships were established between the main table and dimension tables to support filtering and analysis.

DAX Measures

The following DAX measures were created:

Total Stations

Total Bike Capacity

Available Bikes

Available Empty Stands

Bike Occupying Rate

Open Stations

Closed Stations

Average Available Bikes

These measures help calculate key performance indicators and support interactive dashboard analysis.

Dashboard Visualizations

The Power BI dashboard includes:

KPI Cards for key metrics.

Bar Chart for city-wise bike capacity.

Donut Chart for station status distribution.

Column Chart for bike availability by city.

Bar Chart for bike occupancy rate by city.

Combo Chart for station-level analysis.

Map Visual to display geographical station locations.

Slicers to filter data by city, station, and date.

Predictive Analysis

Predictive analysis explores future bike availability using historical station snapshots.

The analysis focuses on:

Forecasting future bike availability.

Identifying stations that may experience bike shortages.

Understanding historical bike availability trends.

Supporting station capacity planning.

Improving bike redistribution decisions.

Note: Forecasts are estimates based on historical availability patterns. The dataset does not contain individual rental transactions or customer details, so actual customer demand cannot be predicted directly.

Key Insights

The dashboard helps identify:

Differences in bike availability across cities.

Stations with higher and lower bike availability.

Distribution of open and closed stations.

Station capacity and occupancy patterns.

Potential bike availability shortages.

Geographical distribution of bike-sharing stations.

Conclusion

This project demonstrates how Power BI can be used to transform raw bike-sharing data into an interactive analytical dashboard. Through data cleaning, data modelling, DAX calculations, and visualizations, the project provides useful insights into bike availability, station performance, and capacity management.

The analysis can support better planning, resource allocation, and operational decisions for smart city bike-sharing systems.
