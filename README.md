# Video-Game-Sales-Reviews-Data-Integration-Pipeline

This project implements an end-to-end ETL pipeline that integrates video game sales data
with Amazon user reviews and product metadata to support analytical querying.

## Data Sources
- VGChartz video game sales dataset
- Amazon product metadata
- Amazon customer reviews

## Approach
- Cleaned and normalized inconsistent schemas and identifiers
- Linked reviews to games using metadata keys
- Implemented validation checks to ensure data integrity across datasets

## Example Queries
- Which games rated under 3 stars generated the highest revenue?
- How do user review volume and sentiment relate to sales performance?

## Tools
Python (pandas), PostgreSQL, SQL, Google Collab
