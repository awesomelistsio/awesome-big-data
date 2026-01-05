# Awesome Big Data [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/awesomelistsio/awesome)

[![GitHub Sponsors](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/awesomelistsio) &nbsp; 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/awesomelists) &nbsp; 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) &nbsp; 
[![Stripe](https://srv-cdn.himpfen.io/badges/stripe/stripe-flat.svg)](https://tinyurl.com/e8ymxdw3) &nbsp; 
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) &nbsp; 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of frameworks, platforms, tools, architectures, and learning resources for **Big Data**, covering distributed storage, batch and stream processing, analytics engines, and large-scale data infrastructure.

## Contents

- [Foundations & Concepts](#foundations--concepts)
- [Distributed Storage & File Systems](#distributed-storage--file-systems)
- [Data Processing Engines](#data-processing-engines)
- [Streaming & Real-Time Processing](#streaming--real-time-processing)
- [Query Engines & SQL on Big Data](#query-engines--sql-on-big-data)
- [Data Warehousing & OLAP](#data-warehousing--olap)
- [NoSQL Databases](#nosql-databases)
- [Data Ingestion & Integration](#data-ingestion--integration)
- [Workflow Orchestration](#workflow-orchestration)
- [Resource Management & Cluster Computing](#resource-management--cluster-computing)
- [Monitoring, Governance & Quality](#monitoring-governance--quality)
- [Cloud Big Data Platforms](#cloud-big-data-platforms)
- [Learning Resources](#learning-resources)
- [Related Awesome Lists](#related-awesome-lists)

## Foundations & Concepts

- [Big Data Explained](https://www.ibm.com/topics/big-data) – Overview of big data characteristics, use cases, and architectures.
- [Lambda Architecture](https://www.oreilly.com/library/view/big-data/9781449358642/) – Architecture combining batch and stream processing.
- [Kappa Architecture](https://www.oreilly.com/radar/questioning-the-lambda-architecture/) – Stream-first alternative to Lambda architecture.
- [CAP Theorem](https://www.ibm.com/topics/cap-theorem) – Trade-offs in distributed systems consistency, availability, and partition tolerance.
- [Data Lake Architecture](https://aws.amazon.com/big-data/datalakes-and-analytics/what-is-a-data-lake/) – Centralized storage for raw and processed data.

## Distributed Storage & File Systems

- [HDFS](https://hadoop.apache.org/docs/current/hadoop-project-dist/hadoop-hdfs/HdfsDesign.html) – Distributed file system designed for large-scale data storage.
- [Amazon S3](https://aws.amazon.com/s3/) – Object storage widely used as a data lake backend.
- [Google Cloud Storage](https://cloud.google.com/storage) – Scalable object storage for analytics workloads.
- [Azure Data Lake Storage](https://azure.microsoft.com/products/storage/data-lake-storage/) – Optimized storage for big data analytics on Azure.
- [Ceph](https://ceph.io/) – Distributed storage system for object, block, and file data.

## Data Processing Engines

- [Apache Hadoop](https://hadoop.apache.org/) – Framework for distributed storage and batch processing.
- [Apache Spark](https://spark.apache.org/) – Unified analytics engine for batch and stream processing.
- [Apache Flink](https://flink.apache.org/) – Stream-first data processing framework with low latency.
- [Apache Beam](https://beam.apache.org/) – Unified programming model for batch and streaming data.
- [Dask](https://www.dask.org/) – Parallel computing library for scalable data processing in Python.

## Streaming & Real-Time Processing

- [Apache Kafka](https://kafka.apache.org/) – Distributed event streaming platform.
- [Apache Pulsar](https://pulsar.apache.org/) – Cloud-native pub/sub and streaming platform.
- [Apache Storm](https://storm.apache.org/) – Real-time computation system for stream processing.
- [Kafka Streams](https://kafka.apache.org/documentation/streams/) – Stream processing library built on Kafka.
- [Redpanda](https://redpanda.com/) – Kafka-compatible streaming platform with simplified operations.

## Query Engines & SQL on Big Data

- [Trino](https://trino.io/) – Distributed SQL query engine for large datasets.
- [Presto](https://prestodb.io/) – High-performance SQL engine for analytics.
- [Apache Hive](https://hive.apache.org/) – SQL-like query system for Hadoop.
- [Apache Drill](https://drill.apache.org/) – Schema-free SQL query engine.
- [Spark SQL](https://spark.apache.org/sql/) – SQL module for Apache Spark.

## Data Warehousing & OLAP

- [Snowflake](https://www.snowflake.com/) – Cloud-native data warehouse for analytics.
- [Google BigQuery](https://cloud.google.com/bigquery) – Serverless enterprise data warehouse.
- [Amazon Redshift](https://aws.amazon.com/redshift/) – Managed data warehouse on AWS.
- [ClickHouse](https://clickhouse.com/) – Column-oriented OLAP database for real-time analytics.
- [Apache Druid](https://druid.apache.org/) – High-performance OLAP database for event data.

## NoSQL Databases

- [Apache Cassandra](https://cassandra.apache.org/) – Distributed wide-column NoSQL database.
- [Apache HBase](https://hbase.apache.org/) – NoSQL database built on HDFS.
- [MongoDB](https://www.mongodb.com/) – Document-oriented NoSQL database.
- [Amazon DynamoDB](https://aws.amazon.com/dynamodb/) – Fully managed NoSQL key-value database.
- [ScyllaDB](https://www.scylladb.com/) – High-performance Cassandra-compatible database.

## Data Ingestion & Integration

- [Apache Kafka Connect](https://kafka.apache.org/documentation/#connect) – Framework for moving data between Kafka and external systems.
- [Apache NiFi](https://nifi.apache.org/) – Visual data ingestion and flow management tool.
- [Apache Sqoop](https://sqoop.apache.org/) – Bulk data transfer between Hadoop and relational databases.
- [Airbyte](https://airbyte.com/) – Open-source data integration platform.
- [Fivetran](https://www.fivetran.com/) – Managed ELT pipelines for analytics teams.

## Workflow Orchestration

- [Apache Airflow](https://airflow.apache.org/) – Platform for programmatically authoring and scheduling workflows.
- [Dagster](https://dagster.io/) – Data orchestration platform with strong observability.
- [Luigi](https://github.com/spotify/luigi) – Python module for building complex pipelines.
- [Prefect](https://www.prefect.io/) – Workflow orchestration system for data engineering.
- [Argo Workflows](https://argo-workflows.readthedocs.io/) – Kubernetes-native workflow engine.

## Resource Management & Cluster Computing

- [YARN](https://hadoop.apache.org/docs/current/hadoop-yarn/hadoop-yarn-site/YARN.html) – Resource management layer for Hadoop clusters.
- [Kubernetes](https://kubernetes.io/) – Container orchestration platform increasingly used for big data workloads.
- [Apache Mesos](https://mesos.apache.org/) – Distributed systems kernel for resource isolation and sharing.
- [Ray](https://www.ray.io/) – Distributed computing framework for scalable applications.

## Monitoring, Governance & Quality

- [Apache Atlas](https://atlas.apache.org/) – Metadata management and data governance platform.
- [Great Expectations](https://greatexpectations.io/) – Data quality and validation framework.
- [OpenLineage](https://openlineage.io/) – Open standard for data lineage collection.
- [Prometheus](https://prometheus.io/) – Monitoring and alerting toolkit for distributed systems.
- [Grafana](https://grafana.com/) – Visualization and observability platform.

## Cloud Big Data Platforms

- [Databricks](https://www.databricks.com/) – Unified analytics platform built on Apache Spark.
- [AWS EMR](https://aws.amazon.com/emr/) – Managed big data platform on AWS.
- [Google Dataproc](https://cloud.google.com/dataproc) – Managed Spark and Hadoop service.
- [Azure Synapse Analytics](https://azure.microsoft.com/products/synapse-analytics/) – Integrated analytics service for big data and warehousing.
- [Alibaba Cloud MaxCompute](https://www.alibabacloud.com/product/maxcompute) – Large-scale data warehousing and analytics platform.

## Learning Resources

### Tutorials
- [Spark Documentation](https://spark.apache.org/docs/latest/) – Official guides for Apache Spark.
- [Kafka Documentation](https://kafka.apache.org/documentation/) – Official Kafka concepts and tutorials.
- [Hadoop Training](https://hadoop.apache.org/docs/current/) – Hadoop ecosystem documentation.

### Guides
- [Designing Data-Intensive Applications](https://dataintensive.net/) – Foundational book on scalable data systems.
- [Big Data Architecture Patterns](https://learn.microsoft.com/azure/architecture/guide/architecture-styles/big-data) – Common patterns for big data solutions.
- [Streaming Systems](https://www.oreilly.com/library/view/streaming-systems/9781491983867/) – Concepts and architectures for stream processing.

### Courses
- *Big Data Fundamentals* – Distributed systems and data processing basics.
- *Spark & Streaming Analytics* – Batch and real-time data processing.
- *Cloud Big Data Engineering* – Building scalable analytics on cloud platforms.

## Related Awesome Lists

- [Awesome Data Analytics](https://github.com/awesomelistsio/awesome-data-analytics)
- [Awesome Data Engineering](https://github.com/awesomelistsio/awesome-data-engineering)
- [Awesome SQL](https://github.com/awesomelistsio/awesome-sql)
- [Awesome Cloud](https://github.com/awesomelistsio/awesome-cloud)
- [Awesome MLOps](https://github.com/awesomelistsio/awesome-mlops)

## Contribute

Contributions are welcome!

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
