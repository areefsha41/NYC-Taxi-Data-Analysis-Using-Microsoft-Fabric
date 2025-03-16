# NYC-Taxi-Data-Analysis-Using-Microsoft-Fabric

This project utilizes Microsoft Fabric to perform an end-to-end analysis of New York City taxi data. The data, sourced from the Taxi & Limousine Commission (TLC), is processed using Fabric's Data Factory, Dataflows, and Power BI to generate insightful visualizations. The workflow involves structured data transformation through multiple layers for a comprehensive analytical approach.

## Data Pipeline Workflow

1. **Landing Layer**: Raw data is ingested into a Fabric Data Lakehouse.
2. **Staging Layer**: Data Factory pipelines transform the raw data into structured formats.
3. **Presentation Layer**: Further transformations using Dataflows prepare the data for Power BI visualization.

## Features

- **Data Ingestion**: Using Microsoft Fabric to store and manage large-scale NYC taxi trip data.
- **Data Transformation**: Aggregations by time, location, and trip attributes using Dataflows and SQL transformations.
- **Semantic Modeling**: Preparing the data for efficient reporting.
- **Power BI Dashboards**: Interactive visualizations to identify taxi trip trends.
- **Optimization**: Utilizing stored procedures to replace Dataflows for performance improvement.

## Prerequisites

- Access to **Microsoft Fabric**
- Familiarity with **SQL & Data Warehousing**
- Basic knowledge of **Power BI** for visualization

## How to Run the Project

1. **Set Up Fabric Environment**

   - Ensure Microsoft Fabric is enabled in your Azure account.
   - Create a Fabric Data Lakehouse for data storage.

2. **Data Ingestion**

   - Download NYC Taxi Trip Record Data from [TLC Trip Record Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page).
   - Use Data Factory to ingest the dataset into the Fabric Data Lakehouse.

3. **Data Transformation**

   - Configure Data Factory pipelines to structure raw data into the **staging layer**.
   - Use Dataflows or stored procedures to further refine the data in the **presentation layer**.

4. **Visualization with Power BI**

   - Connect Power BI to the presentation layer.
   - Create dashboards to visualize trip trends, demand fluctuations, and patterns.

## Future Enhancements

- Integrate external datasets (e.g., weather data) to analyze its impact on taxi demand.
- Implement machine learning models for predictive analytics.

## Resources

- **NYC Trip Record Data**: [TLC Website](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)



