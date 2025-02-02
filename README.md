# nyc-taxi-azure-data-engineering

> This project is to analyze Olympic data using various tools and technologies, including Azure Data Factory, Data Lake Gen 2, Synapse Analytics, and Azure Databricks.

# Table of Contents
- [Overview of the Design](#overview-of-the-design)
- [Dataset](#Dataset)
- [Tech Stack](#Tech-Stack)
- [Setting the workspace](#setting-the-workspace)
- [Azure Services](#Azure-Services)
- [Databricks-backed secret scope](#Databricks-backed-secret-scope)


# <a name="overview-of-the-design"></a> Overview of the Design
![Architecture_Design]()

# <a name="Dataset"></a>Dataset
For this project, we are going to use the following dataset : [Taxi Trip Records](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page) 

We are considering following CSV data within the [raw-data](https://github.com/nk3099/nyc-taxi-azure-data-engineering/tree/main/raw-data) folder:
- [taxi_zone_lookup.csv](https://github.com/nk3099/nyc-taxi-azure-data-engineering/blob/main/raw-data/taxi_zone_lookup.csv)
- [trip_type.csv](https://github.com/nk3099/nyc-taxi-azure-data-engineering/blob/main/raw-data/trip_type.csv)

# <a name="Tech-Stack"></a>Tech Stack
- PySpark
- SQL
- Azure
- Databricks

