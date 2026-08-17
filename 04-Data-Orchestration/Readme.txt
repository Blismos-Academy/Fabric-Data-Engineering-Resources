
Ingest data with a pipeline in Microsoft Fabric
A data lakehouse is a common analytical data store for cloud-scale analytics solutions. One of the core tasks of a data engineer is to implement and manage the ingestion of data from multiple operational data sources into the lakehouse. In Microsoft Fabric, you can implement extract, transform, and load (ETL) or extract, load, and transform (ELT) solutions for data ingestion through the creation of pipelines.

Fabric also supports Apache Spark, enabling you to write and run code to process data at scale. By combining the pipeline and Spark capabilities in Fabric, you can implement complex data ingestion logic that copies data from external sources into the OneLake storage on which the lakehouse is based, and then uses Spark code to perform custom data transformations before loading it into tables for analysis.


In this Hand - on you'll be experiencing the following things

1. Create a workspace
2. Create a lakehouse
3. Create a pipeline
4. Create a notebook
5. Modify the pipeline

Please use this link for making copy data connection "https://raw.githubusercontent.com/MicrosoftLearning/dp-data/main/sales.csv"