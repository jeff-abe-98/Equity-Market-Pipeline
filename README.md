# Equity-Market-pipeline

## Navigation

### Data Loading

Data loading is shown in a python notebook. Here any corrections to trade and quote data was accepted, and previous versions of the record discarded. Data was written back to the storage account partitioned by trade_dt

### Data Ingestion

The data ingestion process is shown as a python notebook. This notebook was exported from a Azure Databricks notebook where the data parsing was done. 

## Architecture

![](Pipeline-Architecture.drawio.png?raw=true)