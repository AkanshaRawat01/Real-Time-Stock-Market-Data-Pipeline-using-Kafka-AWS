# 📈 Real-Time Stock Market Data Pipeline using Kafka & AWS

🏗️ Architecture

Screenshot 2026-05-05 074453.png


## 🚀 Project Overview

This project simulates real-time stock market data streaming using Apache Kafka and processes it using AWS services for scalable data analysis.

## ⚙️ Tech Stack

* Python (Kafka Producer & Consumer)
* Apache Kafka (running on EC2)
* AWS S3 (data storage)
* AWS Glue (data catalog & crawler)
* Amazon Athena (query engine)

## 🔄 Data Flow

1. Stock market dataset (CSV) is read using Python
2. Producer sends data to Kafka topic
3. Kafka broker (hosted on EC2) streams the data
4. Consumer reads and pushes data to S3 in JSON format
5. Glue crawler scans S3 and creates schema
6. Athena queries the data using SQL

## 📂 Features

* Real-time streaming pipeline
* Cloud-based scalable architecture
* Schema discovery using Glue
* Serverless querying using Athena

## ▶️ How to Run

1. Start Kafka & Zookeeper on EC2
2. Run producer script
3. Run consumer script
4. Check S3 bucket for output
5. Query data using Athena



## 🚀 Future Improvements

* Add Spark streaming
* Build dashboard (Power BI / Tableau)


