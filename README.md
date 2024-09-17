**Project Overview: Building a Scalable Data Pipeline**

In this project, I developed a complete, scalable data pipeline utilizing modern data engineering tools. The system captures user data from an API, processes it in real-time, and stores it efficiently for analysis.

This project involves creation of a complete data engineering pipeline, from ingesting data to processing and storing it. Using key tools like Apache Airflow, Kafka, Cassandra, PostgreSQL, and Docker, 
we build a robust system that can efficiently handle and process real-time data.

### Key Tools Used:
- **Apache Airflow**: Manages workflows and automates tasks.
- **Kafka**: Handles real-time data streaming.
- **Cassandra**: Stores processed data in a scalable NoSQL database.
- **PostgreSQL**: Manages metadata for workflows.
- **Docker**: Simplifies deployment by containerizing services.

### How It Works:
1. **Data Generation**: We start by simulating user data with the Random User Generator API.
2. **Orchestration with Airflow**: A DAG (Directed Acyclic Graph) is created in Apache Airflow to schedule the data fetching process from the API, sending it to Kafka for streaming.
3. **Data Processing with Kafka and Spark**: Kafka streams the data into Apache Spark, where it’s processed and prepared for storage.
4. **Storage with Cassandra**: The processed data is stored in Cassandra, structured for easy querying.
5. **Real-Time Monitoring**: We use Kafka’s Control Center to visualize and monitor the data flow.

### Outcome:
The project provides hands-on experience with modern data engineering tools, how to create a scalable, end-to-end pipeline that can handle real-time data ingestion, processing, and storage efficiently. Docker is used throughout to ensure a streamlined deployment process.

This project showcases the full data engineering lifecycle, from gathering raw data to storing it in a database, making it a valuable learning experience for aspiring data engineers.
