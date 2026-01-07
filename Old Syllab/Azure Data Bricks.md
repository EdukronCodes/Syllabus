# Azure Databricks Comprehensive Syllabus (Data Engineering Focus)

## **Module 1: Introduction to Azure Databricks**
- Overview of Azure Databricks
- Architecture and Integration with Azure Ecosystem
- Setting Up Azure Databricks Workspace
- Databricks Runtimes and Cluster Management
  - Cluster Types (Standard, High-Concurrency)
  - Autoscaling and Cluster Termination Policies
- Navigating the Databricks Workspace
- Notebooks and Collaboration Features

---

## **Module 2: Databricks Essentials**
- Databricks File System (DBFS)
  - Understanding DBFS Architecture
  - File Management in DBFS
- Working with Databricks CLI
  - Installing and Configuring Databricks CLI
  - Managing Workspaces, Clusters, and Jobs
- Using Repos for Git Integration
- Widgets and Parameterizing Notebooks
- Workflows and Job Scheduling
  - Triggering Notebooks and Jobs
  - Notebook Chaining and Dependencies

---

## **Module 3: Data Engineering in Azure Databricks**
- ETL Pipelines in Databricks
  - Ingesting Data from Various Sources
    - Azure Blob Storage and Data Lake
    - SQL Databases (JDBC Integration)
    - External File Formats (CSV, JSON, Parquet, Avro)
  - Data Transformation with PySpark
    - Map, Filter, Reduce Operations
    - Joins, Aggregations, and Grouping
  - Writing Transformed Data to Destinations
    - Delta Lake
    - SQL Tables
- Working with Delta Lake
  - ACID Transactions
  - Schema Enforcement and Evolution
  - Time Travel and Version Control
  - Incremental Data Loads
  - Optimizing Delta Tables
- Data Partitioning and Shuffling for Optimization

---

## **Module 4: Structured Streaming**
- Overview of Structured Streaming
- Data Sources and Sinks
  - File Sources (CSV, JSON, Parquet)
  - Streaming Sources (Kafka, Event Hubs)
  - Sinks (Memory, Files, Delta Lake, SQL Tables)
- Building Real-Time Data Pipelines
  - Transformations on Streaming Data
  - Stateful Processing in Streaming Workloads
- Streaming Checkpoints and Fault Tolerance
- Hands-On: Building a Streaming ETL Pipeline

---

## **Module 5: Advanced Pipelines with Databricks**
- Implementing Batch and Streaming Pipelines
- Using Databricks Autoloader
  - Schema Inference and Evolution
  - Incremental Data Loading
- Transformation Pipelines
  - Applying Data Quality Checks
  - Enriching Data with Lookups
  - Implementing Aggregations and Joins
- Writing Pipelines with Delta Live Tables
  - Configuring Delta Live Table Pipelines
  - Setting Up Expectations and Constraints
  - Monitoring DLT Pipelines
- Optimizing Pipeline Performance
  - Skipping Unnecessary Data Reads
  - Using Partition and Bucketing Strategies
  - Cache and Broadcast Variables

---

## **Module 6: Integration with Azure Services**
- Data Pipeline Integration with Azure Data Factory
  - Orchestrating Databricks Jobs in ADF
  - Triggering Workflows using ADF Pipelines
- Event-Driven Pipelines
  - Integration with Azure Event Hubs and Event Grid
  - Real-Time Data Processing with Databricks
- Writing to and Reading from Azure Data Lake
- Working with Synapse Analytics as a Destination
- Secure Data Handling with Azure Key Vault Integration

---

## **Module 7: Security and Governance**
- Role-Based Access Control (RBAC) in Databricks
- Managing Secrets with Databricks Secrets
- Enforcing Data Permissions on Clusters, Jobs, and Tables
- Setting Up Audit Logs for Monitoring

---

## **Module 8: Monitoring and Troubleshooting**
- Cluster and Job Monitoring
  - Spark UI and Logs
  - Identifying Bottlenecks in Data Processing
- Structured Streaming Monitoring
  - Metrics and Progress Logs
  - Handling Late or Corrupt Data
- Debugging Data Pipeline Failures
  - Error Handling in ETL Pipelines
  - Checkpoint Recovery for Streaming Jobs
