# Uber Data Analytics | Modern Data Engineering GCP Project

## Introduction

The goal of this project is to perform data analytics on Uber data using various tools and technologies, including Google Cloud Platform (GCP) services like Google Storage, Compute Instance, BigQuery, and Looker Studio. Additionally, a modern data pipeline tool, [Mage Data Pipeline Tool](https://www.mage.ai/), will be utilized.

## Architecture
![Project Architecture](https://github.com/user-attachments/assets/ff46c073-d972-4184-9b8f-5f13aa39fafc)

## Technology Used

- Programming Language: Python
- Google Cloud Platform:
  1. Google Storage
  2. Compute Instance
  3. BigQuery
  4. Looker Studio
- Modern Data Pipeline Tool: [Mage Data Pipeline Tool](https://www.mage.ai/)

## Dataset Used

The project uses the TLC Trip Record Data, which contains Yellow and green taxi trip records. It includes fields capturing pick-up and drop-off dates/times, locations, distances, fares, rate types, payment types, and passenger counts.

- [Dataset Link](https://github.com/aniketandhale08/Uber-Data-Analytics-Data-Engineering-with-GCP/tree/main/data)
- More information about the dataset:
  - [Website](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
  - [Data Dictionary](https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf)

## Data Model
![Uber Data Model](https://github.com/user-attachments/assets/6b5e8f5c-d120-4ff3-bf9c-d52c1a7a57cf)

## Features
- Data preprocessing and transformation using Python and Pandas.
- Creation of a robust data pipeline using Mage.
- Deployment on Google Cloud Platform for scalability.
- Comprehensive analytics using BigQuery.
- Interactive dashboards built in Looker Studio for data visualization.
  
## Project Workflow

### Step 1: Data Preprocessing and Model Building
1. Review the data dictionary.
2. Open Jupyter Notebook to read CSV data.
3. Create a data model with fact and dimension tables (using lucid.app).
4. Use the `info` function to check data types.
5. Convert date columns to a standard format.
6. Write data transformation code.
7. Merge data into the fact table.

### Step 2: Google Cloud Setup
1. Create a Google Cloud storage bucket.
2. Create a VM instance with the required configuration, including SSH access.
3. Run setup commands from `command.txt`.

### Step 3: GCP Integration
1. Check if the project is running on your external IP address.
2. Write code for data loading, transformation, and exporting.
3. Create a GCP service account, download the JSON key, and configure the `io_config.yaml` file for GCP connectivity.

### Step 4: BigQuery Integration
1. Open BigQuery, create a multi-region dataset, and resolve any errors.
2. Load all cleaned tables into BigQuery.

### Step 5: Visualization and Reporting

![looker dashboard](https://github.com/user-attachments/assets/1c3c21aa-7b1f-44f5-86a7-27c45ae76344)

[View looker dashboard](https://lookerstudio.google.com/u/0/reporting/03c1a20b-57e4-441a-b52d-f7b6a2de73d3/page/iYIFE)

1. Apply SQL queries to join tables and create the `table_analysis`.
2. Use Looker to generate reports, connecting to BigQuery and adding the `table_analysis` table.
3. Create visualizations and reports using various charts and controls.

## Conclusion
This project was a significant learning experience that enhanced my skills in data engineering and analytics. I gained hands-on experience with GCP services, data modeling, and visualization techniques. Moving forward, I plan to explore more advanced analytics techniques and improve the dashboard's interactivity.

## Connect with Me
Feel free to reach out if you have any questions or want to discuss data analytics:
- [LinkedIn](https://www.linkedin.com/in/aniketandhale08/)
  
