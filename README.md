# Earthquake-Data-Engineering-Project-with-Microsoft-Fabric
This project delivers a Lakehouse on Microsoft Fabric which relies on an API as data source and a Report prepared from the gold data.

Data is ingested from [usgs]([url](https://earthquake.usgs.gov/))

## Repository Content
1. Earthquake API - Bronze Layer: Ingests data in its raw format from the data source leveraging pre-defined parameters.
2. Earthquake API - Silver Layer: Performs cleansing and transformations on the data loaded from the bronze layer.
3. Earthquake API - Gold layer: Refines the data loaded from the silver layer and makes them ready for business consumption.

## Artifacts
- Workspace
- Custom Environment: For certain libraries/modules
- Notebooks
- Reports
- Semantic Models
- Lakehouse
- SQL Endpoint

## Data Attributes
id: A string identifier for each data record.

latitude: The latitude of the event, stored as a double.

longitude: The longitude of the event, also stored as a double.

elevation: The elevation at which the event occurred, expressed in meters, stored as a double.

title: A string representing the title or name of the event.

place_description: A string describing the location of the event.

sig: A bigint (large integer) representing the significance score of the event.

mag: A double indicating the magnitude of the earthquake.

magType: A string describing the type of magnitude scale used.

time: A timestamp marking the exact time of the event.

updated: A timestamp indicating the last update time for the event data.
