# Microsoft Fabric Hands-On

A practical, structured learning repository covering **Microsoft Fabric
Data Engineering, Data Warehousing, Real-Time Analytics, Monitoring,
Security, and CI/CD**.

This repository is designed as a hands-on learning journey, progressing
from foundational Fabric concepts to production-oriented data
engineering and real-time analytics.

## Repository Structure

``` text
Fabric-Hands-On/
│
├── 01-Lakehouse/
├── 02-Apache-Spark/
├── 03-Delta-Tables/
├── 04-Data-Orchestration/
├── 05-Data-Ingestion/
├── 06-Medallion-Architecture/
├── 07-Warehouse-Basics/
├── 08-Warehouse-Loading/
├── 09-Warehouse-Queries/
├── 10-Secure-Warehouse/
├── 11-Monitor-Warehouse/
├── 12-Real-Time-Analytics/
├── 13-Eventstream-Ingestion/
├── 14-Eventhouse/
├── 15-Realtime-Dashboards/
├── 16-CI-CD/
├── 17-Monitoring/
└── 18-Secure-Data-Access/
```

## Modules

  -----------------------------------------------------------------------
  \#                      Topic                   What You Will Learn
  ----------------------- ----------------------- -----------------------
  01                      **Lakehouse**           Fabric Lakehouse
                                                  architecture, files,
                                                  tables, and OneLake
                                                  concepts

  02                      **Apache Spark**        Spark fundamentals,
                                                  notebooks,
                                                  transformations, and
                                                  distributed processing

  03                      **Delta Tables**        Delta tables, ACID
                                                  transactions, schema
                                                  management, and
                                                  reliable storage

  04                      **Data Orchestration**  Pipelines,
                                                  dependencies,
                                                  scheduling, and
                                                  workflow automation

  05                      **Data Ingestion**      Practical approaches
                                                  for ingesting data into
                                                  Microsoft Fabric

  06                      **Medallion             Bronze, Silver, and
                          Architecture**          Gold data processing
                                                  architecture

  07                      **Warehouse Basics**    Fabric Warehouse
                                                  fundamentals and
                                                  architecture

  08                      **Warehouse Loading**   Loading and
                                                  transforming data into
                                                  a Fabric Warehouse

  09                      **Warehouse Queries**   SQL querying and
                                                  analytical workloads

  10                      **Secure Warehouse**    Warehouse security,
                                                  permissions, and access
                                                  control

  11                      **Monitor Warehouse**   Warehouse activity,
                                                  workloads, performance,
                                                  and monitoring

  12                      **Real-Time Analytics** Microsoft Fabric
                                                  real-time analytics
                                                  capabilities

  13                      **Eventstream           Streaming data
                          Ingestion**             ingestion and
                                                  processing with
                                                  Eventstream

  14                      **Eventhouse**          Storing, querying, and
                                                  analyzing real-time
                                                  data

  15                      **Realtime Dashboards** Building dashboards for
                                                  continuously arriving
                                                  data

  16                      **CI/CD**               Continuous integration
                                                  and deployment
                                                  practices for Fabric

  17                      **Monitoring**          Monitoring Fabric
                                                  workloads, pipelines,
                                                  and operational
                                                  activities

  18                      **Secure Data Access**  Secure and controlled
                                                  access to Fabric data
  -----------------------------------------------------------------------

## What Each Folder Contains

Each module is designed as a **self-contained hands-on learning
module**.

Where applicable, each folder contains:

-   **Dataset / Data files** -- Sample data required for the exercises.
-   **Readme.txt** -- A short explanation of the topic, instructions,
    prerequisites, and exercise details.
-   **Jupyter Notebook (`.ipynb`) files** -- Practical, executable
    examples demonstrating the concepts.
-   **Supporting files** -- ZIP files, SQL scripts, configuration files,
    or other resources required for the exercises.

Typical structure:

``` text
Module/
│
├── Dataset / Data files
├── Readme.txt
├── Notebook_1.ipynb
├── Notebook_2.ipynb
└── Supporting files
```

The exact contents may vary depending on the module.

## Recommended Learning Path

### Phase 1 -- Data Engineering Foundations

**01 -- Lakehouse**\
Start with the Fabric Lakehouse and understand how data is stored and
organized.

**02 -- Apache Spark**\
Learn Spark fundamentals and perform data processing using notebooks.

**03 -- Delta Tables**\
Work with Delta tables and understand reliable data management.

**04 -- Data Orchestration**\
Build and manage pipelines, dependencies, schedules, and workflows.

**05 -- Data Ingestion**\
Learn practical methods for bringing data into Microsoft Fabric.

### Phase 2 -- Data Architecture

**06 -- Medallion Architecture**

Understand the:

``` text
Bronze → Silver → Gold
```

architecture.

-   **Bronze** -- Raw data
-   **Silver** -- Cleansed and transformed data
-   **Gold** -- Business-ready analytical data

### Phase 3 -- Data Warehouse

**07 -- Warehouse Basics**\
Understand Fabric Warehouse fundamentals.

**08 -- Warehouse Loading**\
Load and transform data into the warehouse.

**09 -- Warehouse Queries**\
Use SQL for analytical workloads.

**10 -- Secure Warehouse**\
Implement warehouse security and access controls.

**11 -- Monitor Warehouse**\
Monitor warehouse workloads and operational activity.

### Phase 4 -- Real-Time Analytics

**12 -- Real-Time Analytics**\
Understand the Fabric real-time analytics ecosystem.

**13 -- Eventstream Ingestion**\
Ingest and process streaming data using Eventstream.

**14 -- Eventhouse**\
Store, query, and analyze real-time data using Eventhouse.

**15 -- Realtime Dashboards**\
Build dashboards for real-time data monitoring and analysis.

### Phase 5 -- Production Readiness

**16 -- CI/CD**\
Understand deployment and CI/CD practices for Fabric solutions.

**17 -- Monitoring**\
Monitor Fabric workloads, pipelines, and operational activities.

**18 -- Secure Data Access**\
Implement secure and controlled access to Fabric data.

## End-to-End Fabric Journey

``` text
Data Sources
     │
     ▼
Data Ingestion
     │
     ▼
Lakehouse
     │
     ▼
Bronze
     │
     ▼
Apache Spark / Delta
     │
     ▼
Silver
     │
     ▼
Gold
     │
     ├──────────────► Fabric Warehouse
     │                       │
     │                       ▼
     │                 SQL Analytics
     │
     └──────────────► Real-Time Analytics
                             │
                             ▼
                       Eventstream
                             │
                             ▼
                         Eventhouse
                             │
                             ▼
                    Realtime Dashboards

        Security → Monitoring → CI/CD
```

## Practical Objectives

After completing the repository, you should be able to:

-   Understand the core Microsoft Fabric data engineering components.
-   Work with Fabric Lakehouses.
-   Use Apache Spark notebooks for data transformation.
-   Work with Delta tables.
-   Design Bronze, Silver, and Gold layers.
-   Build and orchestrate data pipelines.
-   Ingest batch and real-time data.
-   Work with Fabric Warehouse.
-   Write SQL queries for analytics.
-   Implement warehouse security.
-   Monitor Fabric workloads.
-   Work with Eventstream and Eventhouse.
-   Build real-time dashboards.
-   Understand CI/CD for Fabric solutions.
-   Implement secure data access.
-   Design an end-to-end Fabric data engineering solution.

## Prerequisites

Basic knowledge of the following is helpful:

-   SQL
-   Python
-   Data Engineering fundamentals
-   ETL / ELT concepts
-   Data Warehousing fundamentals
-   Basic cloud concepts

Expert-level knowledge is not required. The repository is intended for
**learning through hands-on practice**.

## How to Use This Repository

1.  Follow the modules in order.
2.  Open the `Readme.txt` inside the module before starting.
3.  Review the provided datasets and supporting files.
4.  Open the `.ipynb` notebooks in Microsoft Fabric or another
    compatible notebook environment.
5.  Execute the examples step by step.
6.  Modify the notebooks and datasets to experiment with different
    scenarios.
7.  Connect concepts from previous modules as you progress.

## Learning Philosophy

Each module is designed to answer three questions:

**What is the concept?**\
The module README provides the theoretical context.

**How does it work?**\
The notebooks demonstrate the concept through practical implementation.

**How can I practice it?**\
The included datasets and supporting files allow you to reproduce and
modify the examples.

The repository therefore focuses on **learning by doing**.

## Key Technologies Covered

-   Microsoft Fabric
-   OneLake
-   Lakehouse
-   Apache Spark
-   Delta Lake
-   Data Pipelines
-   Data Ingestion
-   Medallion Architecture
-   Fabric Data Warehouse
-   SQL / T-SQL
-   Eventstream
-   Eventhouse
-   Real-Time Analytics
-   Realtime Dashboards
-   CI/CD
-   Monitoring
-   Security
-   Secure Data Access

## Who Is This Repository For?

This repository is useful for:

-   Data Engineers
-   Aspiring Data Engineers
-   Analytics Engineers
-   BI Developers
-   Data Analysts
-   Cloud Data Professionals
-   Microsoft Fabric learners
-   Professionals preparing for Fabric projects
-   Professionals preparing for Fabric-related certifications

## Suggested End-to-End Project

After completing the individual modules, build a complete Microsoft
Fabric project containing:

1.  Batch data ingestion
2.  Lakehouse storage
3.  Bronze, Silver, and Gold processing
4.  Spark-based transformations
5.  Delta tables
6.  Data orchestration
7.  Fabric Warehouse
8.  SQL analytics
9.  Warehouse security
10. Warehouse monitoring
11. Eventstream-based real-time ingestion
12. Eventhouse analytics
13. Realtime dashboarding
14. CI/CD deployment
15. End-to-end monitoring
16. Secure data access

This can serve as a practical **Microsoft Fabric Data Engineering POC**.

## Important Note

The contents of individual folders may differ depending on the hands-on
topic.

Some modules may contain:

-   Multiple notebooks
-   Datasets
-   SQL scripts
-   ZIP files
-   Configuration files
-   Supporting documentation
-   Exercise-specific resources

Always check the **module-level `Readme.txt`** before starting an
exercise.

## Module Summary

  Module   Primary Focus
  -------- ------------------------
  01       Lakehouse
  02       Apache Spark
  03       Delta Tables
  04       Data Orchestration
  05       Data Ingestion
  06       Medallion Architecture
  07       Warehouse Basics
  08       Warehouse Loading
  09       Warehouse Queries
  10       Secure Warehouse
  11       Monitor Warehouse
  12       Real-Time Analytics
  13       Eventstream Ingestion
  14       Eventhouse
  15       Realtime Dashboards
  16       CI/CD
  17       Monitoring
  18       Secure Data Access

------------------------------------------------------------------------

## Final Outcome

By completing all 18 modules, you will gain practical exposure to a
broad Microsoft Fabric workflow:

**Ingest → Store → Transform → Model → Analyze → Stream → Visualize →
Deploy → Monitor → Secure**

The repository provides a strong hands-on foundation for building
**modern, scalable, and production-oriented data solutions using
Microsoft Fabric**.

------------------------------------------------------------------------

**Microsoft Fabric Hands-On**

*Learn the concepts. Run the notebooks. Work with the data. Build the
solution.*
