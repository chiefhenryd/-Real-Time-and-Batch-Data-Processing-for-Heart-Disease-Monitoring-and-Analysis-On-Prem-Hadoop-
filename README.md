# Real Time and Batch Data Processing for Heart Disease Monitoring and Analysis in OnPrem Hadoop

**Project Overview:** This project focuses on developing a robust heart disease monitoring system, using real-time and batch data processing on an on-premise Hadoop ecosystem. The solution leverages big data tools to process, clean, and store large datasets to generate timely insights, supporting healthcare professionals in early intervention and proactive health management.

**Key Components:**

**Batch Data Processing:**

Data is sourced from PostgreSQL, ingested using Sqoop, and processed with PySpark for transformations.
Data is saved in Hive as Parquet files, enabling efficient storage and querying.

**Real-Time Data Processing:**

Kafka streams real-time data to Spark Streaming, which processes, cleans, and stores data in Hive.
This setup supports immediate data integration and real-time analysis.

**Dimensional Modeling:**

Uses a star schema in Hive, with a fact table for user interactions and dimension tables for user demographics, health metrics, and activity.
This design enables efficient, fast queries for heart disease analysis.

**Technologies Used:**

**PostgreSQL (PSQL):** Source database for patient data, used in the on-premise environment.

**Kafka:** For real-time data streaming.

**PySpark and Spark Streaming:** For batch and real-time data processing.

**Sqoop:** For transferring data from PostgreSQL to HDFS.

**HDFS:** Distributed data storage for scalable, reliable storage of large datasets.

**Hive:** Data warehousing for querying and analytics.

**Project Objectives:**

Implement a dual-mode system (real-time and batch) for heart disease data.
Enable healthcare insights through analytical queries and visualizations.
Provide timely alerts and data-driven insights to support healthcare decisions.
