 # Real-Time Stock Market Data Analysis with Apache Kafka and AWS
 ## Introduction
 
In this project, I developed an End-To-End Data Engineering pipeline for analyzing real-time stock market data using Apache Kafka. The project leverages various technologies including Python for stock market simulation, Amazon Web Services (AWS) for cloud-based processing, and Apache Kafka for real-time data streaming. The pipeline processes stock market data in real-time, stores it in Amazon S3, and catalogs it using AWS Glue. The processed data is then queried using Amazon Athena, enabling powerful data analysis and insights through SQL.

## Architecture
![Architecture](https://github.com/user-attachments/assets/33201e71-867d-4ec3-a2aa-43a7285aff71)

## Technology Used
- **Python**: Stock market data simulation and stream processing.
- **Amazon Web Services (AWS)**: Infrastructure for data storage and processing.
  - **Amazon EC2**: Hosting Kafka producer and consumer.
  - **Amazon S3**: Data lake storage for stock market data.
  - **AWS Glue**: Data cataloging and ETL processing.
  - **Amazon Athena**: SQL querying of real-time stock market data.

- **Apache Kafka**: Real-time streaming of stock market data.
  
## Prerequisites
To run this project, you'll need:

    - An AWS account with permissions for EC2, S3, Glue, and Athena.
    - Python 3.x installed locally.
    - Apache Kafka installed on EC2 instances.
    - Basic knowledge of Kafka, AWS services, and SQL.
    
## Dataset Used
You can use any dataset, we are mainly interested in operation side of Data Engineering (building data pipeline)
Here is the dataset used in the project - https://github.com/NouhaylaChataoui/Stock-Market-Kafka-Real-Time-Data-Analysis/blob/main/indexProcessed.csv

## Conclusion
This project demonstrates the power of combining Apache Kafka with AWS services to build a scalable and real-time data processing pipeline. By leveraging cloud infrastructure, it becomes easier to manage, process, and analyze large datasets with minimal overhead.
