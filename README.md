# ☁️ Architecting Solutions on AWS

## 📝 Overview
This repository contains my coursework, architectural diagrams, and project notes for the **"Architecting Solutions on AWS"** course, offered by Amazon Web Services on Coursera. The course focuses on scenario-based learning, transitioning from basic cloud knowledge to practical solution architecture. 

The modules cover designing resilient, secure, and highly scalable cloud infrastructure, with a strong emphasis on serverless computing, real-time data analytics, containerization, and enterprise governance.

---

## 📚 Course Modules & Explanations

### Module 1: Designing a Serverless Web Backend on AWS
This module focuses on moving away from traditional server management to fully managed compute and database services. 
* **Key Concepts:** Decoupling application components, event-driven architecture, and building scalable APIs.
* **Core AWS Services:** AWS Lambda, Amazon API Gateway, Amazon DynamoDB, and Amazon Cognito.
* **Building a Proof of Concept:** [Exercise 1. Architecting Solutions: Building a Proof of Concept for a Serverless Solution](https://aws-tc-largeobjects.s3.us-west-2.amazonaws.com/DEV-AWS-MO-Architecting/exercise-1-serverless.html)

### Module 2: Designing a Serverless Data Analytics Solution on AWS
This module explores how to build an end-to-end data pipeline capable of handling high-volume, real-time data streaming and historical batch processing without provisioning infrastructure.
* **Key Concepts:** Data ingestion, storage (Data Lakes), serverless ETL (Extract, Transform, Load), and querying big data.
* **Core AWS Services:** Amazon Kinesis (Data Streams & Firehose), Amazon S3, Amazon Athena, and AWS Glue.
* **Building a Proof of Concept:** [Exercise 2. Architecting Solutions: Building a Proof of Concept for a Data Analytics Solution]([Insert Link Here])

### Module 3: Designing a Hybrid Solution for Container-Based Workloads on AWS
This module addresses enterprise scenarios where infrastructure must span both on-premise data centers and the AWS Cloud, utilizing container orchestration for consistency.
* **Key Concepts:** Docker containerization, microservices deployment, and secure on-premise-to-cloud networking.
* **Core AWS Services:** Amazon Elastic Container Service (ECS), AWS Fargate, Amazon Elastic Kubernetes Service (EKS), and AWS Direct Connect.
* **Building a Proof of Concept:** [Exercise 3. Architecting Solutions: Building a Proof of Concept for a Hybrid Container Solution]([Insert Link Here])

### Module 4: Designing a Solution Following Account Governance and Management Best Practices
This module covers the critical security and administrative frameworks required to manage AWS environments at an enterprise scale.
* **Key Concepts:** Multi-account strategies, centralized billing, security compliance, and auditing resource changes.
* **Core AWS Services:** AWS Organizations, AWS Identity and Access Management (IAM), AWS CloudTrail, and AWS Config.
* **Building a Proof of Concept:** [Exercise 4. Architecting Solutions: Building a Proof of Concept for Account Governance]([Insert Link Here])

---

## 🛠️ Technologies & Services Used
* **Compute:** Lambda, ECS, Fargate
* **Storage & Databases:** S3, DynamoDB
* **Analytics & Integration:** Kinesis, Athena, Glue, API Gateway
* **Security & Governance:** IAM, Organizations, CloudTrail
