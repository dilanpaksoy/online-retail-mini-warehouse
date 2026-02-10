# Online Retail Mini Warehouse

## Overview
This project builds a bronze-silver-gold layered data warehouse from the Online Retail dataset.

## Architecture
- Bronze: Raw CSV ingestion
- Silver: Cleaned dataset with business rules applied
- Gold: Star schema (fact & dimension tables)

## Data Quality Summary
- Raw rows: 525,461
- Clean rows: 417,534
- Dropped missing customer_id: 107,927
- Return rows: 9,839
- Invalid price rows: 31
- FK null checks: 0

## Star Schema
### Dimensions
- dim_customer
- dim_product
- dim_date

### Fact
- fact_sales

## Tech Stack
- Python
- Pandas
- Parquet
- Dimensional Modeling

## How to Run
1. Install requirements
2. Place dataset inside `data/`
3. Run notebook in order
