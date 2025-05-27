NYC Traffic Accident MySQL Pipeline

This project demonstrates how to:

Connect to a MySQL database
Create a database and tables for NYC Traffic Accident data
Fetch NYC Traffic Accident data via the NYC Open Data API
Insert the cleaned and flattened data into MySQL using Python
Overview

Last week, we showed how to pull 311 complaints data from NYC Open Data into MySQL. This week, we extend the pipeline by fetching NYC Traffic Accident data.

The Python script handles:

Database initialization (creating the database and tables)
Data ingestion from the NYC Open Data API for Traffic Accidents
Batch fetching and insertion into MySQL
This project is a solid template to get started with any NYC Open Data dataset via API and MySQL.

Dependencies

Make sure to install the required Python packages:

pip install mysql-connector-python requests
Usage

Set up your MySQL credentials in the Python script.
Run the script to initialize the database and ingest data:
python fetch_accidents.py
Modify date filters in the script to fetch data for different time periods as needed.
Repository

Find the full code on GitHub:
https://github.com/djbrown227/OpenData_accidents