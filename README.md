# WideWorldImporters-DWBI-Project
Data Warehouse &amp; Business Intelligence Solution: Wide World Importers
---

Developed a comprehensive Data Warehousing and BI solution utilizing **Snowflake** to process and analyze the Wide World Importers wholesale dataset.

* **Architecture:** Engineered a data warehouse in **Snowflake** consisting of 11 Dimensions and 4 core Fact tables: Sales, Purchases, Stock Holdings, and Stock Item Transactions.
* **Dimensional Modeling:** Implemented a **Snowflake-based** schema with **Slowly Changing Dimensions (SCD Type 2)** to maintain historical integrity of customer and supplier records.
* **ETL & Process Logic:** Developed an **Accumulating Fact** update process using SSIS to calculate end-to-end "process hours," identifying operational bottlenecks in the distribution chain.
* **OLAP & Analytics:** Configured an **SSAS Cube** with custom hierarchies to enable multi-dimensional analysis and high-speed query performance.
* **Visualization:** Designed a **Power BI** dashboard featuring **Drill-through** reporting (focused on Package Types) and **Cascading Slicers** for granular US-based sales territory analysis.
