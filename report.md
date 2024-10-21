
## Objective
The objective of this assignment is to introduce you to managed database services in Azure and Google Cloud Platform (GCP). You will learn how to start, stop, and monitor database-related services, including BigQuery and MySQL.

## Instructions

### 1. Start and Configure a Managed Database
- **Azure MySQL:**
  - Navigate to the Azure portal and create an Azure Database for MySQL.
  - Configure the database with basic settings (e.g., compute and storage options).
  - Start the database service and note the connection details.
    
![error](https://github.com/user-attachments/assets/969345ae-8834-4780-99e0-1a359cd34639)
>could not set up a flexible mysql database for some reason so I used microsoft mysql instead

![microsoft mysql](https://github.com/user-attachments/assets/f47a7065-31a9-4641-95a5-a0f4e852b98a)
>could not set the region to east and could only do central

![Mysql](https://github.com/user-attachments/assets/18610e65-d628-46f2-9b55-eeece87afb99)

- **GCP MySQL:**
  - Access the Google Cloud Console and create a Cloud SQL instance with MySQL.
  - Configure the database instance similarly, noting any differences in setup between Azure and GCP.
  - Start the database service and document the connection details.

### 2. Explore BigQuery (GCP)
- **BigQuery:**
  - In GCP, navigate to BigQuery and create a dataset.
  - Load a small sample data file into a table within the dataset (e.g., a CSV file).
  - Run a simple query against the dataset to retrieve specific data.
  - Monitor the usage and cost associated with running the query.

### 3. Monitor Database Services
- **Azure:**
  - Use the Azure portal to monitor the performance and cost of the MySQL database. Explore metrics like CPU usage, memory, and query performance.
- **GCP:**
  - Use the GCP Console to monitor the Cloud SQL instance and the BigQuery dataset. Pay attention to similar metrics and note any differences in monitoring tools between the two platforms.
