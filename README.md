# Awesome-Lakehouse-Platform

## Top Lakehouse Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Open Table Formats, Unified Analytics, Data Lake + Warehouse Architecture, ACID Tables & Multi-Engine Query*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Lakehouse** architectures. Lakehouses combine the low-cost, flexible storage of data lakes with the reliability, ACID transactions, and performance features of data warehouses—typically using open table formats on object storage.



**Examples** include Databricks, Snowflake, Dremio, Starburst, Onehouse, Cloudera Data Platform, Microsoft Fabric, AWS Lake Formation, Tabular, Ahana, Snowflake Open Lakehouse, Dremio Cloud, Starburst Galaxy, Firebolt, and Upsolver (the category leaders).



**Open-source emphasis**: The lakehouse is built on open standards. **Apache Iceberg**, **Delta Lake**, **Apache Hudi**, **Apache Spark**, **Trino**, **Apache Flink**, and related projects form the core of most open and hybrid lakehouses. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Databricks](https://www.databricks.com/)**  

  Leading lakehouse platform unifying data engineering, analytics, and AI/ML on Delta Lake (and Iceberg), with managed Spark and collaborative workspaces.



- **[Snowflake](https://www.snowflake.com/)**  

  Cloud data platform that has expanded into lakehouse patterns with support for open table formats, external tables, and multi-cloud analytics.



- **[Dremio](https://www.dremio.com/)**  

  Lakehouse query engine focused on self-service SQL analytics, acceleration, and open table formats (especially Iceberg) on data lakes.



- **[Starburst](https://www.starburst.io/)**  

  Trino-based analytics platform for federated and lakehouse SQL, querying data in place across lakes, warehouses, and other sources.



- **[Onehouse](https://www.onehouse.ai/)**  

  Managed lakehouse platform centered on Apache Hudi for incremental data and streaming-oriented lakehouse workloads.



- **[Cloudera Data Platform](https://www.cloudera.com/)**  

  Enterprise data platform with lakehouse capabilities, hybrid/multi-cloud deployment, and open-source lineage (Spark, Iceberg, etc.).



- **[Microsoft Fabric](https://www.microsoft.com/microsoft-fabric)**  

  Unified analytics platform with OneLake storage and lakehouse experiences integrated across the Microsoft data stack.



- **[AWS Lake Formation](https://aws.amazon.com/lake-formation/)**  

  AWS service for building, securing, and managing data lakes, often used with Athena, Redshift Spectrum, and open table formats.



- **[Tabular](https://www.tabular.io/)**  

  Managed Iceberg-focused lakehouse catalog and table service (now part of the broader Iceberg ecosystem narrative).



- **[Ahana](https://ahana.io/)**  

  Managed Presto/Trino offerings historically focused on open analytics on data lakes.



- **[Dremio Cloud / Starburst Galaxy](https://www.dremio.com/)**  

  Fully managed cloud offerings of Dremio and Starburst for lakehouse and federated SQL without self-managed infrastructure.



- **[Firebolt](https://www.firebolt.io/)**  

  Cloud data warehouse with strong performance focus, often used alongside or in place of traditional lakehouse patterns for analytics.



- **[Upsolver](https://www.upsolver.com/)**  

  Data pipeline and lakehouse-oriented platform for continuous ingestion and transformation into analytics-ready tables.



## Open-Source GitHub Projects

- **[Apache Iceberg](https://github.com/apache/iceberg)**  

  Open table format for huge analytic tables with ACID transactions, schema evolution, time travel, and multi-engine compatibility (Spark, Trino, Flink, etc.).



- **[Delta Lake](https://github.com/delta-io/delta)**  

  Open-source storage layer that brings ACID transactions, scalable metadata, and time travel to data lakes (widely used with Spark and Databricks).



- **[Apache Hudi](https://github.com/apache/hudi)**  

  Open table format optimized for incremental data, upserts, and streaming ingestion into the lakehouse.



- **[Apache Spark](https://github.com/apache/spark)**  

  Unified analytics engine for large-scale data processing—the workhorse compute layer of most lakehouses.



- **[Trino](https://github.com/trinodb/trino)**  

  Distributed SQL query engine (foundation of Starburst) for interactive analytics across lakes and federated sources.



- **[Apache Flink](https://github.com/apache/flink)**  

  Stream-processing framework frequently used for real-time ingestion and processing into Iceberg/Hudi/Delta tables.



- **[Apache Polaris / Iceberg REST catalogs](https://github.com/)**  

  Open catalog implementations that enable multi-engine access to Iceberg tables with centralized governance.



- **[lakeFS](https://github.com/treeverse/lakeFS)**  

  Open-source data version control for data lakes, bringing Git-like branching and commits to lakehouse storage.



- **[Open Lakehouse reference architectures](https://github.com/)**  

  Community and vendor-neutral stacks combining Iceberg/Delta/Hudi with Spark, Trino, Flink, dbt, and Airflow.



- **[MinIO and open object-storage tools](https://github.com/minio/minio)**  

  High-performance open-source object storage often used as the S3-compatible foundation for self-hosted lakehouses.



### Additional Strong Open-Source Options

- Building on **Iceberg + Spark + Trino** for a vendor-neutral, multi-engine lakehouse.

- Choosing **Delta Lake** when Spark-centric or Databricks-aligned workloads dominate.

- Using **Hudi** for CDC-heavy and incremental upsert pipelines.

- Adding **lakeFS** for data versioning and reproducible lakehouse workflows.

- Accepting that fully managed security, Unity Catalog–style governance, optimized runtimes (Photon, etc.), and enterprise support still favor commercial platforms (Databricks, Snowflake, Dremio, Starburst, Microsoft Fabric, etc.).

- Focusing open-source efforts on open table formats, engine choice, and avoiding lock-in to a single vendor’s storage layer.



**Frameworks for building custom systems**: Land data in object storage (S3/MinIO) as Parquet → manage tables with Iceberg/Delta/Hudi → process with Spark/Flink → query with Trino or Spark SQL → orchestrate with Airflow/dbt → govern via open catalogs. Suitable for data platform teams that want full control. Many enterprises still adopt commercial lakehouse platforms for operational simplicity and integrated AI/ML features.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Lakehouse platforms handle critical business data. Open-source deployments require careful capacity planning, security, backup, and governance. Table format and catalog choices have long-term architectural impact. This list is not architecture or compliance advice.



---

**Made for data engineers, platform teams, and analytics leaders building modern data stacks.**

Let's keep the lakehouse open, reliable, and multi-engine by design.
