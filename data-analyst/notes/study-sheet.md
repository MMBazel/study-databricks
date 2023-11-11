# Exam Outline

---

## Section 1: Databricks SQL -- 22% 
### Overall
Describe Databricks SQL & its capabilities, including:
- Databricks SQL (users, benefits, queries, dashboards, compute)
    - SQL Warehouses: Formerly known as SQL warehouses
- Integrations (Partner Connect, data ingestion, other BI tools)
- Lakehouse (Medallion architecture, streaming data)

![Screenshot 2023-11-10 at 4 22 17 PM](https://github.com/MMBazel/study-databricks/assets/3360070/38806dcf-9ea9-45a6-bc9b-9c8383c9c19a)
![Screenshot 2023-11-10 at 4 23 01 PM](https://github.com/MMBazel/study-databricks/assets/3360070/3c4926e8-417b-4088-8e42-c0ac1c5091f5)
![Screenshot 2023-11-10 at 4 24 13 PM](https://github.com/MMBazel/study-databricks/assets/3360070/789503dd-dfd1-44af-8af9-bdd5ee8e573f)
![Screenshot 2023-11-10 at 4 25 02 PM](https://github.com/MMBazel/study-databricks/assets/3360070/28f2fbf4-4b0c-4d2e-aff4-7a903771563b)
![Screenshot 2023-11-10 at 4 30 39 PM](https://github.com/MMBazel/study-databricks/assets/3360070/575664c4-630f-48dc-aaad-44aa47a6d9c9)



### Specific Topics
- Describe the key audience and side audiences for Databricks SQL.
- Describe that a variety of users can view and run Databricks SQL dashboards as
stakeholders.
- Describe the benefits of using Databricks SQL for in-Lakehouse platform data processing.
- Describe how to complete a basic Databricks SQL query.
- Identify Databricks SQL queries as a place to write and run SQL code.
- Identify the information displayed in the schema browser from the Query Editor page.
- Identify Databricks SQL dashboards as a place to display the results of multiple queries at
once.
- Describe how to complete a basic Databricks SQL dashboard.
- Describe how dashboards can be configured to automatically refresh.
- Describe the purpose of Databricks SQL endpoints/warehouses.
- Identify Serverless Databricks SQL endpoint/warehouses as a quick-starting option.
- Describe the trade-off between cluster size and cost for Databricks SQL
endpoints/warehouses.
- Identify Partner Connect as a tool for implementing simple integrations with a number of
other data products.
- Describe how to connect Databricks SQL to ingestion tools like Fivetran.
- Identify the need to be set up with a partner to use it for Partner Connect.
- Identify small-file upload as a solution for importing small text files like lookup tables and
quick data integrations.
- Import from object storage using Databricks SQL.
- Identify that Databricks SQL can ingest directories of files of the files are the same type.
- Describe how to connect Databricks SQL to visualization tools like Tableau, Power BI, and
Looker.
- Identify Databricks SQL as a complementary tool for BI partner tool workflows.
- Describe the medallion architecture as a sequential data organization and pipeline system
of progressively cleaner data.
- Identify the gold layer as the most common layer for data analysts using Databricks SQL.
- Describe the cautions and benefits of working with streaming data.
- Identify that the Lakehouse allows the mixing of batch and streaming workloads.

---

## Section 2: Data Management -- 20% 
### General
- IManage data with Databricks tools & best practices, including:
    - Delta Lake (basics, benefits)
    - Storage & Management (tables, databases, views, Data Explorer)
    - Security (table ownership, PII data)


![Screenshot 2023-11-10 at 4 31 42 PM](https://github.com/MMBazel/study-databricks/assets/3360070/268df7ad-d8e7-4a1b-956e-4c7e8a62c978)
![Screenshot 2023-11-10 at 4 33 05 PM](https://github.com/MMBazel/study-databricks/assets/3360070/61bf1040-758c-4363-88e5-cb69325473b9)
![Screenshot 2023-11-10 at 4 33 31 PM](https://github.com/MMBazel/study-databricks/assets/3360070/393412af-19c3-4654-a293-2f8fdaa6cc1b)
![Screenshot 2023-11-10 at 4 34 20 PM](https://github.com/MMBazel/study-databricks/assets/3360070/7acc886c-fa98-474b-b627-6954bd380de4)
![Screenshot 2023-11-10 at 4 34 36 PM](https://github.com/MMBazel/study-databricks/assets/3360070/7532c417-a494-4149-b3cd-6191c8b8de25)


### Specifics
- Describe Delta Lake as a tool for managing data files.
- Describe that Delta Lake manages table metadata.
- Identify that Delta Lake tables maintain history for a period of time.
- Describe the benefits of Delta Lake within the Lakehouse.
- Describe persistence and scope of tables on Databricks.
- Compare and contrast the behavior of managed and unmanaged tables.
- Identify whether a table is managed or unmanaged.
- Explain how the LOCATION keyword changes the default location of database contents.
- Use Databricks to create, use, and drop databases, tables, and views.
- Describe the persistence of data in a view and a temp view
- Compare and contrast views and temp views.
- Explore, preview, and secure data using Data Explorer.
- Use Databricks to create, drop, and rename tables.
- Identify the table owner using Data Explorer.
- Change access rights to a table using Data Explorer.
- Describe the responsibilities of a table owner.
- Identify organization-specific considerations of PII data

---

## Section 3: SQL in the Lakehouse -- 29%
### General

Use SQL to complete tasks in the Lakehouse, including:
- Basic SQL (basic query structure, combining data, aggregations)
- Complex Data (nested data objects, roll-ups, windows, cubes)
- SQL in the Lakehouse (ANSI SQL, workign with silver-level data, query history, higher-order functions, user-defined functions) 

![Screenshot 2023-11-10 at 4 39 01 PM](https://github.com/MMBazel/study-databricks/assets/3360070/2653593e-5fc2-4918-a12a-584d54cab57b)
![Screenshot 2023-11-10 at 4 48 06 PM](https://github.com/MMBazel/study-databricks/assets/3360070/d4e61c81-3dca-44d4-aac4-a309d04453a1)
![Screenshot 2023-11-10 at 4 48 47 PM](https://github.com/MMBazel/study-databricks/assets/3360070/428db138-ca13-41cd-a633-84d701403e1e)
![Screenshot 2023-11-10 at 4 49 17 PM](https://github.com/MMBazel/study-databricks/assets/3360070/d4fcd2b6-82b2-4d1d-a9ef-a41ca0d9e79b)



### Specifics
- Identify a query that retrieves data from the database with specific conditions
- Identify the output of a SELECT query
- Compare and contrast MERGE INTO, INSERT TABLE, and COPY INTO.
- Simplify queries using subqueries.
- Compare and contrast different types of JOINs.
- Aggregate data to achieve a desired output.
- Manage nested data formats and sources within tables.
- Use cube and roll-up to aggregate a data table.
- Compare and contrast roll-up and cube.
- Use windowing to aggregate time data.
- Identify a benefit of having ANSI SQL as the standard in the Lakehouse.
- Identify, access, and clean silver-level data.
- Utilize query history and caching to reduce development time and query latency.
- Optimize performance using higher-order Spark SQL functions.
- Create and apply UDFs in common scaling scenarios.


---

### Section 4: Data Visualization and Dashboarding
- Create basic, schema-specific visualizations using Databricks SQL.
- Identify which types of visualizations can be developed in Databricks SQL (table, details,
counter, pivot).
- Explain how visualization formatting changes the reception of a visualization
- Describe how to add visual appeal through formatting
- Identify that customizable tables can be used as visualizations within Databricks SQL.
- Describe how different visualizations tell different stories.
- Create customized data visualizations to aid in data storytelling.
- Create a dashboard using multiple existing visualizations from Databricks SQL Queries.
- Describe how to change the colors of all of the visualizations in a dashboard.
- Describe how query parameters change the output of underlying queries within a
dashboard
- Identify the behavior of a dashboard parameter
- Identify the use of the "Query Based Dropdown List" as a way to create a query parameter
from the distinct output of a different query.
- Identify the method for sharing a dashboard with up-to-date results.
- Describe the pros and cons of sharing dashboards in different ways
- Identify that users without permission to all queries, databases, and endpoints can easily
refresh a dashboard using the owner's credentials.
- Describe how to configure a refresh schedule
- Identify what happens if a refresh rate is less than the Warehouse's "Auto Stop"
- Describe how to configure and troubleshoot a basic alert
- Describe how notifications are sent when alerts are set up based on the configuration

---

### Section 5: Analytics applications
- Compare and contrast discrete and continuous statistics.
- Describe descriptive statistics.
- Describe key moments of statistical distributions.
- Compare and contrast key statistical measures.
- Describe data enhancement as a common analytics application.
- Enhance data in a common analytics application.
- Identify a scenario in which data enhancement would be beneficial.
- Describe the blending of data between two source applications.
- Identify a scenario in which data blending would be beneficial.
- Perform last-mile ETL as project-specific data enhancement.
