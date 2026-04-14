# Earthquake-Data-Engineering-Project-with-Microsoft-Fabric

## Project Overview
Developed an end-to-end data pipeline and analytics solution using Microsoft Fabric to process real-time earthquake data. Implemented a Medallion Architecture (Bronze–Silver–Gold) where raw data was ingested from an API, transformed using PySpark notebooks, and enriched for analytics.

Automated the workflow using Fabric pipelines, enabling parameterized and scheduled execution. Built a semantic model and Power BI dashboard to provide insights into earthquake trends, magnitude distribution, and geographical patterns.


## Repository Contents
`Worldwide Earthquake Events API - Bronze Layer Processing`: This notebook focuses on ingesting raw earthquake data from the USGS API. It performs minimal processing to store data in its original format, serving as the foundational layer for further refinement.

`Worldwide Earthquake Events API - Silver Layer Processing`: This notebook enhances the data from the Bronze layer by cleaning, transforming, and consolidating the earthquake data. It prepares the data for more analytical processing.

`Worldwide Earthquake Events API - Gold Layer Processing`: In this final processing stage, the notebook refines the data to create business-ready datasets. These are optimized for high-value insights and are tailored for specific analytical purposes, such as reporting and visualization in tools like Power BI.

## Data Attribute Definitions
`id`: A string identifier for each data record.

`latitude`: The latitude of the event, stored as a double.

`longitude`: The longitude of the event, also stored as a double.

`elevation`: The elevation at which the event occurred, expressed in meters, stored as a double.

`title`: A string representing the title or name of the event.

`place_description`: A string describing the location of the event.

`sig`: A bigint (large integer) representing the significance score of the event.

`mag`: A double indicating the magnitude of the earthquake.

`magType`: A string describing the type of magnitude scale used.

`time`: A timestamp marking the exact time of the event.

`updated`: A timestamp indicating the last update time for the event data.

## Prerequisites
- Microsoft Fabric Account.
- Fabric Administrator (or access to individual with Admin account).
- Familiarity with Python, Spark, and basic data engineering concepts.
- Basic Power BI skills.
