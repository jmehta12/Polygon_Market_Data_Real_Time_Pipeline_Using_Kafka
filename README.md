# Polygon Market Data Real-Time Data Analysis Using Kafka
This is an End-To-End Data Engineering Project on Real-Time Stock Market Data, using AWS and Kafka. 

Technologies used

Apache Kafka: This is an event streaming platform used to collect, process, store, and integrate data at scale. Its Python API was utilized to stream data received from the web API

AWS EC2 : This is a cloud-based computing service that allows users to quickly launch virtual servers and manage cookies, security, and networking from an easy-to-use dashboard. It was used to host Kafka server for this project. 

AWS S3: This is a highly scalable object storage service that stores data as objects within buckets. It is commonly used to store and distribute large media files, data backups and static website files. For this project it is used to store data streamed from kafka. 

AWS Glue :Glue Crawler is a fully managed service that automatically crawls your data sources, identifies data and infer schemas to create an AWS Glue Data Catalog. This Catalog is a fully managed metadata repository that makes it easy to discover and manage data that has been crawled.It allows us to query the data directly from S3 without loading it first. 

AWS Athena: Athena is an interactive query service that makes it easy to analyze data in Amazon S3 using SQL commands. For this project it is used to analyze data in Glue Data Catalog or in other S3 buckets. 
