# Professional Experience

## SONICWALL TECHNOLOGY SYSTEMS | INDIA  
### Staff Engineer – Reporting and Analytics, NSM  
*Network Security Manager (NSM) - Reporting and Analytics*

Architecting and implementing high-throughput data pipelines to process massive datasets from global firewall deployments. Designed petabyte-scale data lake solutions with 365-day retention, optimized for both performance and cost-efficiency to serve a diverse client base.

### Key Projects

#### Data Lake Optimization (Petabyte Scale)
Designed and implemented a scalable data lake capable of handling petabytes of data, supporting both real-time and historical analytical requirements.
- **Impact:** Engineered a multi-tenant solution that serves various clients beyond the primary data processing pipeline.
- **Technologies:** AWS (Kinesis, Firehose, Lambda, Redshift, Redshift Spectrum, Athena, DynamoDB, S3, Glue, EMR, IAM), Apache Iceberg, Hudi, Scala, Spark, Python, PySpark, Go.

#### High-Performance IPFIX Collector
Co-engineered and Developed a robust IPFIX collector as a Go-based microservice to continuously ingest and process network data via UDP.
- **Technologies:** Go, Microservices Architecture.

#### Analytical Workload & EMR Optimization
Optimized Amazon EMR clusters to enable near real-time data processing for analytics and efficient handling of massive historical backlogs for reporting.
- **Impact:** Significantly reduced processing latency and improved the scalability of realtime data processing and historical data re-processing.
- **Technologies:** AWS, EMR, Scala, Spark, Python, PySpark.

#### Encryption/ Decryption Module
Designed and implemented a secure encryption/decryption module to protect sensitive firewall files meant for cloud backup with AWS KMS. This module has further capabilities to integrate with other types of data storage and retrieval systems as well.
- **Impact:** Enhanced data security and compliance with industry standards. Files are now encrypted before being uploaded to S3, DSSE-KMS encrypted at rest in S3 and decrypted(server and client side) after being downloaded from S3.
- **Technologies:** AWS (KMS , S3, IAM), Go, Go Module for Microservices.

---

## GLOBALFOUNDRIES ENGINEERING | INDIA  
### Senior Analyst – Data Systems and Automation  
*Full-Stack Software Engineer*

Designed and implemented a comprehensive ecosystem of mobile and web applications, leveraging REST and GraphQL APIs on Amazon Web Services (AWS) and Google Cloud Platform (GCP). Focused on building scalable, event-driven applications that automate enterprise workflows.

### Key Projects

#### Strategic Idea Management Platform
Architected a serverless web platform to manage global innovation campaigns and hackathons, facilitating idea submission and peer voting.
- **Architectural Innovation:** Devised a unique "near-zero backend" architecture using AWS AppSync and GraphQL, significantly reducing infrastructure overhead.
- **Value Delivered:** Enabled rapid prototyping, reduced maintenance complexity, and allowed for a primary focus on enhancing UI/UX.
- **Technologies:** Angular, Python, GraphQL, AWS (Amplify, AppSync, S3, DynamoDB, Cognito, Lambda, API Gateway).

#### Real-time Defect Classification System
Developed a reactive, event-driven ecosystem to classify and analyze production floor images in real-time using machine learning.
- **Impact:** Integrated Google AutoML to predict defects instantly, streamlining quality control processes.
- **Architecture:** Built a Progressive Web App (PWA) with Material Design for seamless user interaction and real-time data visualization.
- **Technologies:** Angular, Python, Flask, Google Cloud (AutoML, App Engine, GCS, Cloud Functions, BigQuery, Firestore, Firebase Auth, FCM, Cloud Tasks, Hosting).

#### Enterprise Notification System
Designed a scalable, cross-platform notification engine (Web & Mobile) capable of delivering real-time messages at scale.
- **Capabilities:** Enabled multi-channel notifications (Push, In-app) via NativeScript and Angular PWAs, accessible from any enterprise server or the central portal.
- **Technologies:** Angular, NativeScript (Android/iOS), Java, Spring, Google Cloud (App Engine, Cloud Functions, Cloud Tasks, Datastore, Firebase).

#### Mobile Enterprise Approval Workflow
Developed a secure mobile application for executive-level business approvals across multiple internal systems.
- **Technologies:** NativeScript, Java, Spring, Google Cloud (App Engine, Cloud Tasks, Datastore, Firebase).

#### Digital Content Library (eBook)
Engineered an Angular-based PWA to serve as a centralized, high-performance library for documents and video content.
- **Technologies:** Angular, Java, Spring, Google Cloud (App Engine, GCS, Firestore, Firebase Auth).

#### Enterprise Event Scheduler
Developed a multi-event scheduling application, inspired by Google I/O, allowing users to manage complex schedules for internal corporate events.
- **Technologies:** Angular, Python, Flask, Google Cloud (Functions, Firestore).