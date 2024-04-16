# Introduction
The purpose of this project is to build a real-time data engineering pipeline. It covers from data ingestion to processing and finally to storage,
using tech stack including Apache Airflow, Python, Apache Kafka, Apache Zookeeper, Apache Spark, and Cassandra. 
Everything is contained using Docker for ease of deployment and scalability.

# Components of the project
- Data Source: Using randomuser.me API to generate random user data for pipeline
- Apache Airflow: Orchestrating the pipeline and storing fetched data in a PostgreSQL database.
- Control Center and Schema Registry: Helps monitoring and schema management of Kafka stream.
- Apache Spark: For data processing with its master and worker nodes.
- Cassandra: Storing the processed data.
- Docker: Containerizing entire data engineering setup.

# Technologies:
- Apache Airflow
- Apache Kafka
- Apache Zookeeper
- Apache Spark
- Python
- Cassandra
- PostgreSQL
- Docker
