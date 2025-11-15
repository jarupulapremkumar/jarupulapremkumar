# Hi, I'm Jarupula Prem Kumar 

### Senior Data Engineer | Data Platform Architect

I specialize in designing, deploying, and optimizing high-performance, multi-cloud data ecosystems built for massive scale and reliability. My focus is translating complex analytical needs (R\&D, Data Science, Product) into robust, cost-efficient, and fully automated data infrastructure.

### Key Focus & Quantified Impact

My work centers on improving performance and governance across the data lifecycle:

| Metric | Achievement | Architectural Focus |
| :---- | :---- | :---- |
| **70%** | Infrastructure Cost Reduction | Re-architected high-volume ingestion (EventHub → ADLS → Spark) |
| **3x** | Throughput Increase | Optimized batch and streaming ETL workflows |
| **\<5s** | Real-Time Latency | Engineered **MQTT/Kafka** low-latency microservices |
| **99.9%** | Production Uptime | Maintained fault-tolerant streaming via robust **Observability (Prometheus/Grafana)** |

###  Core Capabilities

- Architected the P360 telemetry platform processing 30B+ EV/ICE events per day with sub-second latency and 99.9% uptime, engineered for 10× horizontal scale.
- Re-designed EventHub ingestion by moving from direct EventHub→ClickHouse streaming to EventHub Capture→Avro→ADLS with Spark Streaming loaders, reducing ingestion cost and improving stability.
- Built Python-based Kafka→ClickHouse microservices on AKS with schema validation, DLQ routing, checkpointing, and idempotent exactly-once semantics.
- Implemented schema-aware Kafka ingestion with dynamic schema sync, automated invalid-record routing, and fault-tolerant distributed consumer processing.
- Delivered enterprise-grade CDC ingestion (Python/Polars) for 20+ SAP/master-data systems using SCD-0 modeling with autonomous schema-drift recovery and real-time freshness.
- Developed distributed Airflow/K8s aggregation pipelines producing trip summaries, charge-cycle analytics, battery-health diagnostics, and fleet KPIs from second-level telemetry.
- Built production ETL/ELT pipelines with strict data contracts, automated/manual backfills, and multi-team integration for ML, BI, and analytics workloads.
- Deployed and operated Kafka consumer microservices on AKS using ArgoCD, Helm, and KEDA autoscaling, reducing compute cost by 10%.
- Established SLO-driven observability with Prometheus/Grafana/Loki, achieving 99.95% SLA, reducing MTTR by 60%, and cutting production incidents by 90%.
- Optimized a 20+ TB ClickHouse cluster with MergeTree tuning, partitioning, replication strategies, and materialized views—improving p99 query latency by 60% (sub-2s).
- Led archival and governance migration of 20+ TB to ADLS with Unity Catalog RBAC, lineage, metadata, auditing, and retention policies—reducing storage cost by 40%.
- Built feature stores and reusable feature extraction frameworks (PySpark/Polars) with point-in-time correctness and versioning, reducing ML feature prep effort by 80%.
- Mentored 5 engineers on distributed systems, ClickHouse, Spark, Kubernetes, and observability; implemented review workflows and onboarding playbooks, cutting pipeline time-to-production from 6 to 3 weeks.

### **Technical Skills**

**Data Architecture & Design:**  
Medallion Architecture (Bronze/Silver/Gold), Data Lakehouse Patterns, Dimensional Modeling (Star/Snowflake), Event-Driven Architecture, Lambda/Kappa Architecture, Data Mesh Principles, Slowly Changing Dimensions (SCD Type-0/1/2), Data Vault Modeling

**Real-Time & Streaming:**  
Apache Kafka, Azure Event Hub, Apache Spark (PySpark, Structured Streaming, SparkSQL), Apache Flink, MQTT, Exactly-Once Semantics, Idempotent Processing, Stream Processing Patterns

**Data Warehousing & Analytics:**  
ClickHouse, Delta Lake, Databricks, BigQuery, Snowflake, DBT, Incremental Loading, Partition Pruning, Query Optimization

**Pipelines & Orchestration:**  
Apache Airflow, CDC (Change Data Capture), Incremental Processing, Backfills, Data Quality (Great Expectations), Schema Evolution, Data Lineage, Metadata Management

**Cloud Platforms:**  
Azure (ADLS Gen2, AKS, Event Hub, DevOps), AWS (S3, Glue, Lambda, EMR), GCP (BigQuery, Dataproc), MinIO, Multi-Cloud Architectures

**Containers & DevOps:**  
Kubernetes, Docker, Helm, ArgoCD, KEDA, CI/CD Pipelines, Infrastructure as Code (IaC), GitOps, Blue-Green Deployments, Canary Releases

**Programming & Development:**  
Python (PySpark, Polars, Pandas, FastAPI), Advanced SQL/T-SQL, Shell Scripting (Bash), Core Java, REST APIs

**Data Governance & Quality:**  
Unity Catalog (RBAC, Lineage Tracking, Audit Logging), Data Contracts, Schema Registry, Avro, Protobuf, Data Cataloging, Metadata Management, Data Quality Frameworks, Compliance & Auditing

**Observability & Reliability:**  
Prometheus, Grafana, Loki, SLO/SLA Monitoring, MTTR Optimization, Distributed Tracing, Incident Response, Root Cause Analysis, On-Call Engineering, Chaos Engineering

**Databases & Storage:**  
PostgreSQL, MySQL, Redis, ClickHouse, NoSQL Patterns, Columnar Storage, Time-Series Databases, Data Partitioning Strategies, Indexing Optimization

**Advanced Topics:**  
ML Feature Engineering, MLOps Pipelines, Feature Stores, Data Mesh Architecture, Vector Databases (ChromaDB), RAG Pipelines, Cost Optimization (FinOps), Capacity Planning, Performance Tuning

**Leadership & Collaboration:**  
Platform Architecture, System Design, Technical Mentoring (5+ Engineers), Code Reviews, Cross-Functional Collaboration (Product, Analytics, Data Science, BI), Async Communication, Stakeholder Management, Requirements Gathering, Documentation Standards


### Let's Connect

I'm interested in collaborative projects involving real-time pipeline design, cost optimization, and platform reliability. Feel free to connect or check out my work below\!

**Find Me:**</br>
  - <b> Linkedin :</b> https://www.linkedin.com/in/jarupula-premkumar/
  - <b> Email :</b> jarupulapremkumar@gmail.com
