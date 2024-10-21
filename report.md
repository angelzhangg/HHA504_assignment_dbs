
# Objective
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
    
![Cloud mysql](https://github.com/user-attachments/assets/3d81bf41-8eea-45ea-83f5-0ccf3f522f0c)

### 2. Explore BigQuery (GCP)
- **BigQuery:**
  - In GCP, navigate to BigQuery and create a dataset.
  - Load a small sample data file into a table within the dataset (e.g., a CSV file).
  - Run a simple query against the dataset to retrieve specific data.
  - Monitor the usage and cost associated with running the query.
    
![BigQuery database](https://github.com/user-attachments/assets/d77d242a-5857-4696-b51b-8e8226372c32)
![creating table](https://github.com/user-attachments/assets/bb6c262c-4f53-485f-a96c-3086f3b274f4)
![running query](https://github.com/user-attachments/assets/bf5bc07f-cd94-4d44-a0bb-17d70616de2e)

### 3. Monitor Database Services
- **Azure:**
  - Use the Azure portal to monitor the performance and cost of the MySQL database. Explore metrics like CPU usage, memory, and query performance.
    
![azure monitoring](https://github.com/user-attachments/assets/0d22df6a-0c6c-4985-af32-78c2408f792a)

- **GCP:**
  - Use the GCP Console to monitor the Cloud SQL instance and the BigQuery dataset. Pay attention to similar metrics and note any differences in monitoring tools between the two platforms.
    
 <img width="1316" alt="Screenshot 2024-10-21 at 1 02 17 AM" src="https://github.com/user-attachments/assets/68a7f388-f801-4dbe-ae3a-2e47d9d3a15b">

<img width="1314" alt="Screenshot 2024-10-21 at 1 03 01 AM" src="https://github.com/user-attachments/assets/dab8cb31-d994-43ca-a773-f7ad3ae12dc6">

<img width="1320" alt="Screenshot 2024-10-21 at 1 04 20 AM" src="https://github.com/user-attachments/assets/c237e7a2-7be9-46ac-9c20-cbee9106a198">

## *Reflections on the differences Azure and GCP*

- GCP uses Big Query to query their information from a csv file
- Azure is more complicated and does not have this Big Query. 
- More steps in Azure compared to GCP



