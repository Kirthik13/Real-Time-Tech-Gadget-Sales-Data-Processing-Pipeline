# ⚡Real-Time Tech Gadget Sales Data Processing-Pipeline

This project demonstrates a real-time data pipeline for processing sales events of tech gadgets using streaming AWS services and enabling analytics through S3 and Athena.

## 🚀 Tech Stack
- Python
- Amazon DynamoDB
- DynamoDB Streams
- Amazon Kinesis Data Streams
- Amazon EventBridge Pipes
- Amazon Kinesis Firehose
- Amazon S3
- AWS Lambda
- Amazon Athena

## 📌 Features
- Captures real-time sales updates from DynamoDB via streams
- Lambda function transforms the data for downstream processing
- EventBridge Pipe routes data to Firehose for delivery to S3
- Athena enables querying the processed sales data

## 🏗️ Architecture
1. Sales data written to DynamoDB
2. DynamoDB Stream triggers Lambda for transformation
3. Transformed events routed through EventBridge Pipe → Kinesis Firehose
4. Data is stored in S3 and queried via Athena


