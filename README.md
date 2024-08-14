# Automated News Data Pipeline with Sentiment Analysis

## Project Overview
This project implements an end-to-end news data pipeline using Microsoft Fabric. It automates the process of ingesting news data, performing sentiment analysis, and creating interactive reports.

## Key Steps
1. **Data Ingestion**: 
   - Set up a Synapse workspace and lakehouse.
   - Created a pipeline in Azure Data Factory to pull data from Bing News API and store it in a JSON file.

2. **Data Transformation**:
   - Used PySpark in Synapse to clean and transform the raw JSON data into a structured format.
   - Applied incremental loading to keep the data updated.

3. **Sentiment Analysis**:
   - Implemented sentiment analysis using Synapse Data Science.
   - Stored results in a Delta table.

4. **Reporting**:
   - Created interactive dashboards in Microsoft Fabric to visualize sentiment metrics and insights.

## Technologies Used
- Microsoft Fabric
- PySpark
- Bing News API
- Delta Lake

## Impact
This pipeline automates data processing, provides real-time sentiment insights, and enables dynamic reporting for informed decision-making.
