# Getting Started With Data Analysis on Databricks

## Introducing Databricks SQL
### 1-1 What is Databricks?

Databricks vision
- Enable data-driven innovation to all enterprises

Data Lakehouse = Data Lake + Data Warehouse
  - Single platform to unify data, analytics, & AI workloads
  - Combines best-of-both-worlds of Data Lakes & Data Warehouses
  - Conflicting requirements that required both to exist in most enterprise environments

 Data Lakes
 - Pros
     - Support machine learning
     - Open formats
     - Large ecosystem
 - Cons
     - Poor support for BI
     - Complex data quality problems
  
Data Warehouses
- Pros
    - Great for BI
- Cons
    - Limited support fot machine learning workloads
    - Proprietary systems with only a SQL interface!

![Screenshot 2023-11-09 at 12 14 39 PM](https://github.com/MMBazel/study-databricks/assets/3360070/87b31162-a27b-4aba-a77f-fb146e7bb0c3)


Delta Lake
- Specific implementation of Data Lakes
-   "Open approach to bringing data management & governance to data lakes"
- Features
1. "Better reliability with transactions"
    - Provides ability to build curated data lakes that add reliability, performance, & governance you expect from data warehouses directly to existing data lakes
    - Reliability with ACID transactions
    - Can be sure that all oeprations in the data lake either fully succeed or fail with the ability to easily time travel backward to understand every change made to your data
2. "48X faster data processing with indexing"
    - Delta Lake is underpinned by Apapche Spark & utilizes advanced caching & indexing methods, allowing you to process & quaery data on your data lake extremely quickly at scale.
3. "Data governance at scale with fine-grained access control lists"
    - Fine-grained control lists or ACLs to give you much more control over who can access which data in your data lake. 

![Screenshot 2023-11-09 at 12 13 07 PM](https://github.com/MMBazel/study-databricks/assets/3360070/7dbc3428-2dbc-46b0-a79e-21cfc83be044)

Databricks Lakehouse Platform
- Main benefits & characterisitics
    1. Data only needs to exist once to support all your data workloads on one common platform
    2. It's open - based on open-source & open-standards to make it easy to work with existing tools & proprietary formats
    3. Izt's collaborative -- Data engineers, data analysts, & data scinetists are able to work together much more easily 


### 1-2 What is Databricks SQL? 
![Screenshot 2023-11-09 at 12 18 14 PM](https://github.com/MMBazel/study-databricks/assets/3360070/e49a5fe2-8108-4152-b8ee-449ca96e147b)

![Screenshot 2023-11-09 at 12 19 35 PM](https://github.com/MMBazel/study-databricks/assets/3360070/6371d789-ad5c-4441-8fd9-1f5e5a3b79a1)

Better price /performance
- Databricks SQl allows customers to obtain data warehouse performance & data lake economics through SQL-optimized compute clusters, powered by Photon, that directly query Delta Lake tables on data lakes
- Databricks SQL automatically load balances queries across multiple clusters to provide high concurrency & low latency without disruption 

![Screenshot 2023-11-09 at 12 22 28 PM](https://github.com/MMBazel/study-databricks/assets/3360070/f5beec1c-ed63-4b78-81e2-5d46841f6c71)
- Setting up integration to Delta Lake tables should be simple & authentication can be connected


![Screenshot 2023-11-09 at 12 39 28 PM](https://github.com/MMBazel/study-databricks/assets/3360070/502d526b-5b72-4af7-9a23-a41a5f9e3fb8)
- DB Sql makes it easier for analysts to quickly visualize and share insights with a new & easy tp use SQL query editor, rich dashboards, & automatic alerts
- DB SQl also offers fully featured, SQL-native qeury editor that allows data analysts to write queries in a familiar syntax & easily explore Delta Lake table schemas
- Regularly used SQL can be saved as snippets for quick reuse
- Query results can be cached to keep run times short
- Once queries are built, DB SQL also allows analysts to make sense of the results through a wide variety of rich visualizations
- The visualizations can be quickly organized into dashboards qith an intuitive drag-and-drop interface


#### Sql Warehouses
- SQL warehouses give a quick way to setup SQL & BI optimized compute
- Just pick the cluster size
- Offers central log so customers can record usage across virtual clusters, users, & time
- Custoemrs can also observe workloads across Databricks SQL, 3rd party BI tools, & any other SQL clients

![Screenshot 2023-11-10 at 3 22 28 PM](https://github.com/MMBazel/study-databricks/assets/3360070/f6fb870a-d18e-40b2-9b70-4bdb6e09a3e6)
