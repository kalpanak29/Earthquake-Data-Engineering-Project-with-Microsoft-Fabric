# Earthquake-Data-Engineering-Project-with-Microsoft-Fabric

## Project Overview
Developed an end-to-end data pipeline and analytics solution using Microsoft Fabric to process real-time earthquake data. Implemented a Medallion Architecture (Bronze–Silver–Gold) where raw data was ingested from an API, transformed using PySpark notebooks, and enriched for analytics.

Automated the workflow using Fabric pipelines, enabling parameterized and scheduled execution. Built a semantic model and Power BI dashboard to provide insights into earthquake trends, magnitude distribution, and geographical patterns.

Ingesting Earthquake events data from [usgs](https://earthquake.usgs.gov/). 

Technologies Used: Python, PySpark, Fabric (Data Engineering, Data Factory, Power BI)

## Getting Started
To get started with this project, downalod the notebooks in the repository and follow the guidance provided in the YouTube tutorial.

## Repository Contents
`Worldwide Earthquake Events API - Bronze Layer Processing`: This notebook focuses on ingesting raw earthquake data from the USGS API. It performs minimal processing to store data in its original format, serving as the foundational layer for further refinement.

`Worldwide Earthquake Events API - Silver Layer Processing`: This notebook enhances the data from the Bronze layer by cleaning, transforming, and consolidating the earthquake data. It prepares the data for more analytical processing.

`Worldwide Earthquake Events API - Gold Layer Processing`: In this final processing stage, the notebook refines the data to create business-ready datasets. These are optimized for high-value insights and are tailored for specific analytical purposes, such as reporting and visualization in tools like Power BI.




