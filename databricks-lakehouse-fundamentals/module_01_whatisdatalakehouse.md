# Module 1: What is a Data Lakehouse?
## Describe the origin and purpose of the data lakehouse.

### 1980's: Businesses need more than relational databases
![Screenshot 2023-11-21 at 4 00 28 PM](https://github.com/MMBazel/study-databricks/assets/3360070/b0b7ef8b-613e-4152-98e7-b3e47ac27f71)
![Screenshot 2023-11-21 at 4 02 53 PM](https://github.com/MMBazel/study-databricks/assets/3360070/80312382-342c-41b3-bcbf-e1c47f5b0400)

- Data warehouses are great for supporting business analytics and oeprational reporting that relies on clean & structured daya, with predefined schemas.
- But they weren't designed with either unstructured or semi-structured data in mind and become expensive when trying to store & analyze any data that didn't fit the schema
- Data collection drastically increased in volume, velocity, & variety
- Data warehouses took too much time to process data & provide results & there was limited capability to handle data variety & velocity

### 2000s: Big data explosion
- Structured, semi-structured, & unstructured data could live simultaneously, collected in the volumes & speeds necessary
- Data created from many different sources such as web logs or sensor data, could be streamed into the data lake quickly & cheaply in low-cost cloud object stores
- However while data lakes solved the storage dilemma, it introduced additional concerns & lacked neceddary features of data warehouses
- Cons:
    - 1) Data lakes aren't supportive of transactional data & can't enforce data quality, so the reliability of the data stored in the data lake is questionable, mostly due to the various formats
    - 2) With such a large volume of data, the performance of analysis is slower, & the timeliness of decision-impacting results has never manifested
      3) Governance over the data in a data lake challenges with security & privacy enforcement due to the unstructrued nature of the contents of a data lake
      4) 

![Screenshot 2023-11-21 at 4 08 30 PM](https://github.com/MMBazel/study-databricks/assets/3360070/68a75956-cabc-4dd9-a5fb-8cd1a580137e)
![Screenshot 2023-11-21 at 4 16 20 PM](https://github.com/MMBazel/study-databricks/assets/3360070/4c9b2ab7-c3bd-41c3-812f-37213f6a5f12)

### Needed two disparate, incompatible data platforms
![Screenshot 2023-11-21 at 4 17 31 PM](https://github.com/MMBazel/study-databricks/assets/3360070/ba52f9e4-bd60-44d1-88ad-52e126a5e15d)

- Because data lakes didn't fully replace data warehouses for reliable BI insights, businesses implemented complex technology stack environments
- These included: data lakes, data warehouses, & additional specialized systems for streaming, time series, graph, & image databases (to name a few)
- Such an environment introduced complexity & delay as data teams were stuck in silos, completing disjointed work
- Data had to be copied between the systems & in some cases opied back, impacting oversight & data usage governance, not to mention the cost of storing the same information twice with disjointed systems
- Successful AI implementation was difficult& actionable outcome rewuired data from multiple places

- Business needed a single, high-performing system to support the ever icnreasing use cases for data exploration, predictive modeling, & predictive analytics
- Data teams needed systems to support data applications, including SQL analytics, real-time analysis, data science, & machine learning

![Screenshot 2023-11-21 at 4 23 11 PM](https://github.com/MMBazel/study-databricks/assets/3360070/e8350b36-fd6e-4e15-8cab-00dc2c7f34c6)

- To meet these needs, developed the data lakehouse architecture
- Developed as an open architecture, combining the benefits of a data lake with the analytical power & controls of a data warehouse
- Built on a data lake, a data lakehouse can store all data of any type together, becoming a single reliable source of truth, providing direct access for AI & BI together

- Key features of a data lakehouse
    - Transaction support: 

## Explain the challenges of managing and using big data.
