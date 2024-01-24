# Project Overview
The project aims to build a robust data pipeline using Apache Airflow for orchestrating tasks. The pipeline involves parallel processing, utilizes S3 buckets for storage, and relies on an RDS PostgreSQL database for data persistence.

# DAG Structure

 Apache Airflow Instance: Hosted on an EC2 instance, serving as the central orchestrator for the data pipeline.
 
 S3 Buckets: Used for storing and retrieving data files, facilitating seamless interaction with various tasks.
 
 RDS PostgreSQL Database: Provides a reliable and scalable solution for persisting joined data.
 
 IAM Roles & Policies: Implemented robust access control mechanisms to safeguard sensitive resources.

 ![image](https://github.com/Boxydaa/weather-map-airflow/assets/152782315/334b806b-a68c-4d3c-9974-c681a95e9074)
In conclusion, this data pipeline orchestrated by Apache Airflow on an EC2 instance demonstrates a robust and scalable solution for handling weather data. The parallel processing capabilities of Airflow, combined with the storage flexibility of S3 buckets and the data persistence offered by RDS PostgreSQL, create a comprehensive and reliable workflow.

# Key highlights of the project include:

# Infrastructure: 
The project leverages an EC2 instance for hosting Apache Airflow, providing a centralized platform for task orchestration. This infrastructure allows for efficient coordination and execution of tasks within the data pipeline.

# Parallel Processing: 
The use of Airflow's TaskGroups facilitates parallel processing, enabling concurrent execution of tasks within the group_a section. This enhances the overall efficiency and speed of the data pipeline.

# Data Storage: 
S3 buckets serve as a versatile storage solution for both input and output data. This enables seamless data transfer between tasks and ensures accessibility and durability of data throughout the pipeline.

# Data Persistence: 
The RDS PostgreSQL database plays a crucial role in persisting joined data. Its reliability and scalability make it an ideal choice for storing structured data, providing a foundation for analytics and reporting.

# Configurability: 
The DAG configuration includes settings for the EC2 instance, S3 buckets, RDS PostgreSQL connection, and Weather API. Proper configuration management is essential for the smooth execution of the pipeline.



