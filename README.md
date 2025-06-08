# ETL Project : Youtube-data-analysis

## Introduction
This `README` document provides an overview of an `ETL` (Extract, Transform, Load) project developed to extract data from a `YouTube` channel using the YouTube API and `Python`, perform data transformations with the `Pandas` library, export the transformed data to a CSV file, load the data into `Snowflake` data warehouse, and create a reporting dashboard using `Power BI`.

## Project Overview
This project demonstrates how to extract, transform, and visualize data from a YouTube channel using YouTube Data API, Python, MySQL, and Power BI. It automates the end-to-end data pipeline, ensuring that the Power BI dashboard stays up-to-date dynamically with the latest channel statistics.

## Tools Used
- `Python`: Used for scripting and data manipulation.
- `Pandas`: Employed for data transformation and manipulation.
- `YouTube API`: Utilized for data extraction from the YouTube channel.
- `Power BI`: Employed for creating interactive dashboards and reports.
- `MySQL` : for structured data storage

## Dynamic Dashboard with Power BI
Power BI is connected directly to the MySQL database. The dashboard reads live data via:
Power BI MySQL connector
Configured on-premises data gateway for secure connectivity

## Scheduled Automation

The Python script can be scheduled via Windows Task Scheduler to run periodically (e.g., hourly or daily).
Power BI Service can be configured for scheduled refresh to pull the latest data from MySQL and update the visuals automatically.

## Project Steps

### Step 1: Web Scraping
In this step, the YouTube API and Python were used to extract data from a specific YouTube channel. This data typically includes video metadata such as titles, views, likes, Title,Published date ...

### Step 2: CSV File Creation
After extracting the data, it was transformed and cleaned using the Pandas library in Python. Once the data was in a structured and organized format, it was exported to a CSV file. This CSV file serves as an intermediary data storage format.

### Step 3: Load Data to Snowflake Data Warehouse
The CSV file generated in Step 2 was loaded into Snowflake, a cloud-based data warehouse. Snowflake provides a scalable and secure environment for storing and managing large datasets, making it suitable for analytics.

### Step 4: Reporting with Power BI
In the final step, the data stored in Snowflake was connected to Power BI. A reporting dashboard was created in Power BI, allowing users to visualize and interact with the YouTube channel data. This dashboard can be customized to display various metrics and insights from the data.



Here is the workflow (data analysis) of  this project

![Texte alternatif de l'image](images/data_pipeline(1).png)

**The dashboard :** 

![Texte alternatif de l'image](images/pie1.png)




## Contacts
For any questions or inquiries related to this project, please feel free to contact me :)

- linkedin : <a href="https://www.linkedin.com/in/sudhir-singh-241983286/" target="_blank">Sudhir Singh</a><br>
- Email: `sudhirsingh9763@gmail.com`
