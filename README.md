# Supply Chain Shipment Visibility Platform

## Business Problem

A retail supply-chain organization needs visibility into shipments moving from
suppliers to warehouses and finally to customers.

Operations teams need timely answers to questions such as:

- Are shipments delayed?
- Which carriers have poor on-time delivery performance?
- Which routes or warehouses cause recurring delays?
- What is the financial impact of late deliveries?
- Where are inventory and shipments stuck?

## Project Goal

Build an end-to-end data platform that ingests shipment, warehouse, carrier,
and order data; applies data-quality checks; builds trusted analytical models;
and provides delivery-performance insights.

## Key Business Metrics

- On-time delivery rate
- Late shipment rate
- Average delivery delay
- Carrier performance
- Warehouse throughput
- Shipment cost and delay impact

## Architecture Overview

The platform will follow a layered architecture:

1. Source systems  
2. Ingestion layer  
3. Raw storage layer  
4. Data-quality and transformation layer  
5. Curated analytical layer  
6. Dashboard and reporting layer  

## Tech Stack

- Python
- PostgreSQL
- Docker
- Apache Airflow
- dbt
- MinIO
- Metabase
- GitHub Actions

## Project Status

Initial repository created. Business problem, source-system analysis, and
data-model design will be added next.
