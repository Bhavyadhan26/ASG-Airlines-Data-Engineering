# ASG Airlines – End-to-End Data Engineering

## Project Overview

An end-to-end airline data engineering pipeline developed for the ASG Airlines
case study.

The pipeline ingests flight, booking, passenger and payment data from an Excel
workbook and processes it using Python and Pandas.

## Tech Stack

- Python 3.11
- Pandas
- NumPy
- Microsoft Power BI
- Excel
- CSV

## Pipeline

Excel
→ Ingestion
→ Profiling
→ Validation
→ Cleaning
→ Transformation
→ Aggregation
→ CSV Outputs
→ Power BI

## Key Processing

- Schema validation
- Missing-value profiling
- Data standardization
- Duplicate detection and removal
- Flight duration calculation
- Overnight flight detection
- Referential integrity validation
- Rejected-record handling
- PII masking
- KPI generation

## Power BI Report

The report contains:

1. Overview
2. Duration Analysis
3. Route Analysis
4. Airline Analysis
5. Delay & Anomaly
6. Booking & Revenue

## Documentation

Detailed architecture, data flow, data model, cleaning strategy,
transformation logic, assumptions, privacy controls and dashboard
documentation are available in the `documentation` folder.