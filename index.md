---
layout: home
title: NYC Traffic Accident Data Analysis
---

# 🚦 NYC Traffic Accident Data with MySQL & Python

Last week, I showed you how to fetch and store NYC 311 complaint data. This week, we’re diving into another critical dataset: **NYC Traffic Accident Data**.

This project demonstrates how to:

- Connect to a MySQL database  
- Create a new database and tables  
- Fetch NYC Traffic Accident data via the [NYC Open Data API](https://data.cityofnewyork.us/)  
- Clean and insert the accident data into MySQL using Python  
- Prepare the data for further analysis or visualization  

## 🐍 Python Script Overview

The Python scripts include:

1. **Database Setup**  
   - Connects to MySQL  
   - Creates a database (`nyc_traffic_accidents`)  
   - Creates tables (`accidents`, `vehicles`, `persons`) to properly structure the data  

2. **Data Ingestion**  
   - Uses NYC’s Traffic Accident API (`h9gi-nx95`)  
   - Fetches accident records for a specified date range  
   - Cleans and flattens nested data fields  
   - Inserts data into MySQL tables  

> You can modify the date range in the script to fetch accident data for any time period you need.  
> This approach is adaptable for other NYC Open Data datasets with similar API structures.

## 🧩 Dependencies

Install the required Python packages:

```bash
pip install mysql-connector-python requests pandas
