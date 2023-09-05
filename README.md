# Polish Housing Market Analytics

## Overview

The project aims to provide a comprehensive analysis of the housing market in Poland, particularly in its major cities. Utilizing data science techniques, the project focuses on collecting, storing, and analyzing data related to property types, prices, and availability. The primary data source is Otodom, one of the largest real estate platforms in Poland.

---

## Table of Contents

1. [Features](#features)
2. [Technologies](#technologies)
3. [Data Collection and Storage](#data-collection-and-storage)
4. [Data Analysis](#data-analysis)
5. [Getting Started](#getting-started)
6. [Contributions](#contributions)
7. [License](#license)

---

## Features <a id="features"></a>

- **Data Collection**: Scrape real estate listings from Otodom using Bright Data.
- **Data Storage**: Utilize Snowflake as a centralized data warehouse.
- **Data Transformation**: Convert nested JSON data to flat tables.
- **Data Analysis**: Execute SQL queries for detailed insights.
- **Data Visualization**: Use Google Sheets for generating charts and graphs.

---

## Technologies <a id="technologies"></a>

- Python: Data processing and analytics.
- SQL: Querying and manipulation in Snowflake.
- Google Sheets: Additional data manipulation and visualization.
- Snowflake: Data warehousing.
- Bright Data: Data collection from Otodom.
  
---

## Data Collection and Storage <a id="data-collection-and-storage"></a>

### Steps:

1. **Data Acquisition**: Use Bright Data for scraping real estate listings from Otodom.
2. **Data Ingestion**: Store the scraped data in a Snowflake database.
3. **Data Transformation**: Flatten the JSON data and adapt the schema to be SQL-friendly.

---

## Data Analysis <a id="data-analysis"></a>

1. **Unified Data Views**: Merge multiple tables into a single data view using SQL.
2. **Query Insights**: Execute SQL queries to isolate variables such as property types, prices, and advertiser types.
3. **Data Visualization**: Employ Google Sheets for the visual representation of data findings.

---

## Getting Started <a id="getting-started"></a>

- Clone the repository.
- Set up a virtual environment and install the required packages.
- Follow the steps in the "Data Collection and Storage" section.
  



