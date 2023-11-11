# Administration in Databricks SQL
## Sec 2-1: Controlling Access to Databricks SQL

![Screenshot 2023-11-10 at 3 30 50 PM](https://github.com/MMBazel/study-databricks/assets/3360070/d4202acb-421e-4712-aafd-265feee8caa6)

![Screenshot 2023-11-10 at 3 31 32 PM](https://github.com/MMBazel/study-databricks/assets/3360070/bc074e12-4e51-4938-b7db-54e2fac16b14)

---

## Sec 2-2: Create A Simple Databricks SQL Warehouse

![Screenshot 2023-11-10 at 3 32 08 PM](https://github.com/MMBazel/study-databricks/assets/3360070/e816fe54-7b05-4a13-87c6-a39958fc3692)

![Screenshot 2023-11-10 at 3 32 38 PM](https://github.com/MMBazel/study-databricks/assets/3360070/fd190435-3347-4c22-ad2e-1ed49752a93d)

- Must have admin privileges to create SQL warehouses


![Screenshot 2023-11-10 at 3 33 13 PM](https://github.com/MMBazel/study-databricks/assets/3360070/3b221e15-aa69-4ff8-9dfe-a0480e3d3990)

![Screenshot 2023-11-10 at 3 33 36 PM](https://github.com/MMBazel/study-databricks/assets/3360070/476a3f9f-e24a-4407-8ca6-7de8771e10f2)

![Screenshot 2023-11-10 at 3 35 11 PM](https://github.com/MMBazel/study-databricks/assets/3360070/68aa355a-008d-4e76-bf70-b13ef2594010)

![Screenshot 2023-11-10 at 3 39 10 PM](https://github.com/MMBazel/study-databricks/assets/3360070/03799bee-36fb-428b-a502-54d49aba9b77)

![Screenshot 2023-11-10 at 3 41 07 PM](https://github.com/MMBazel/study-databricks/assets/3360070/42bd7fdc-5e57-42c7-a1d5-413e71b5a339)

![Screenshot 2023-11-10 at 3 41 40 PM](https://github.com/MMBazel/study-databricks/assets/3360070/2ab5fdf0-4d35-4274-8da7-110b9bee0b59)


- Cluster size is how you can reduce query latency
- Bigger cluster, greater cost (DBUs)
- Auto-stop: If the Warehouse isn't being used
- Scaling: Manage scaling to hanfle more concurrent users
- We can also monitor the connection details.  

---

## Sec 2-3 Advanced SQL Warehouse Options in AWS

![Screenshot 2023-11-10 at 3 42 58 PM](https://github.com/MMBazel/study-databricks/assets/3360070/0b677385-62d8-4a43-a766-e27835e36b1b)

Let's check out the advanced options:
- Tags: Can add them to instances (can be tracked in udnerlying cloud provider) 
- Serverless: Hosted & managed by Databricks; start & stop when you need it; take very little time to startup
    - vs SQl warehouses: Clusters need to be provisioned & startup time may take a couple minutes
- Unity Catalog: Secure catalog system built by DB
- Channel: If you want to enable new releases


---

## Sec 2-4: Advanced SQL Warehouse Options in Azure

![Screenshot 2023-11-10 at 3 55 34 PM](https://github.com/MMBazel/study-databricks/assets/3360070/8efeba30-5b16-4830-8282-e74d305bbea4)
![Screenshot 2023-11-10 at 4 01 04 PM](https://github.com/MMBazel/study-databricks/assets/3360070/898f2aa2-251e-4b28-acc5-bde9dc2848dd)

- Spot Instance:
    -    Cost Optimized -- This saves money: We'll use the spot isntances thata re cost optimized at 100% of the bid price for all workers & they'll auto fall back to on-demand instances if the spot isntance is reclaimed;
        -    if the spot instance is reclaimed, any queries that are running at the time that spot instance is reclaimed will need to be resubmitted;
    -   Reliability Optimized -- More Reliable: if we want to ensure that we have reliability for any queries that are running, we would want to choose R.O. 


---


## Sec 2-5: Advanced SQL Warehouse Options in GCP


---


## Sec 2-6: Create Entities & Configure Permissions in Databricks SQL

---


## Sec 2-7: Create a Slack Alert Destination in Databricks SQL

