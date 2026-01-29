

# Project: U.S. Emissions Analysis Dashboard
This project is a comprehensive data engineering and visualization pipeline built on the Databricks Lakehouse Platform. Inspired by a Databricks industry demo, I utilized EPA (Environmental Protection Agency) 2023 data to analyze and visualize carbon emissions across the United States.

## Technical Workflow
Data Ingestion: Streamlined ingestion of EPA raw data into the Databricks environment.

Medallion Architecture: Implemented a multi-stage pipeline (Bronze/Silver/Gold) to clean and transform raw records into high-quality analytical tables.

Advanced Analytics: Calculated complex metrics such as Emissions per Person by joining emission datasets with population demographics.

Visualization: Developed an interactive Databricks SQL Dashboard featuring:

Geospatial Mapping: Emissions density by location.

Statistical Analysis: Correlation between population density and per-capita emissions.

Concentration Metrics: Identifying the top 10 states responsible for over 50% of total U.S. emissions.

Granular Reporting: County-level breakdown of total metric tons of CO 2.

## Key Insights
The dashboard reveals critical trends in environmental data, such as the disproportionate impact of specific industrial hubs and the inverse relationship between high-population urban centers and individual emission rates.


![#f03c15](https://github.com/ryjamj/Databricks-Projects-RJ/blob/main/Demo_Emissions/Emissions%20Dashboard.png)
