# AWS
This repository is about Amazon Web Services.

### DEFINITION OF TERMS AND ACRONYMS
#### Amazon DynamoDB - 
#### Amazon EBS - 
Amazon Elastic Block Store
#### Amazon EC2 - 
Amazon Elastic Compute Cloud
#### Amazon EMR - 
Amazon Elastic MapReduce
#### Amazon EMR Studio - 
offers fully managed Jupyter notebooks for visualization with an ability to log in through AWS IAM Identity Center (successor to AWS Single Sign-On).
#### Amazon MWAA - 
Amazon Managed Workflows for Apache Airflow
#### Amazon Sagemaker - 
#### Amazon S3 - 
Amazon Simple Storage Service
#### Amazon VPC
#### Apache Flink
#### Apache Hadoop
#### Apache Spark
#### API - 
Application Programming Interface
#### AWS - 
Amazon Web Services
#### AWS Fargate - 
#### AWS CLI - 
#### AWS IAM - 
AWS Identity and Access Management
#### AWS KMS - 
AWS Key Management Service
#### AWS SDK - 
#### AZ - 
Availabilty Zone
#### EMRFS - 
EMR File System
#### HDFS - 
Hadoop Distributed Files System, operates as a distributed file system designed to run on commodity hardware. HDFS is fault-tolerant and designed to be deployed on low-cost, commodity hardware.
#### Hive ACID - 
atomicity, consistency, isolation, durability
#### IDE - 
Integrated Development Environment
#### LDAP - 
Lightweight Directory Access Protocol 
#### LLAP - 
Live Long and Process, uses persistent daemons with intelligent in-memory caching to improve Hive query performance
#### Presto CLI - 
#### Structured Streaming - 
is a scalable and fault-tolerant stream processing engine built on the Spark SQL
#### vCPU - 
virtual Central Processing Unit, represents the central processing unit used in virtual machines and cloud environments

### Amazon EMR 
is a managed cluster platform that simplifies running big data frameworks on AWS to process and analyze vast amounts of data.
It easily runs and scales Apache Spark, Hive, Presto, and other big data workloads.
It is the industry-leading cloud big data solution for petabyte-scale data processing, interactive analytics, and machine learning using open-source frameworks such as Apache Spark, Apache Hive, and Presto.

#### BENEFITS OF Amazon EMR
1. Amazon EMR Serveless
2. Amazon EMR clusters

### Lesson 3 of 15
### Amazon EMR Serverless Architecture and Use Cases

#### Typical Use Cases for Amazon EMR Serverless
	Apache Spark ETL jobs
	Large-scale SQL queries using Hive
	Interactive analysis using Jupyter notebooks with EMR studio
	Ad-hoc analysis using Presto
	Building real-time streaming data pipelines
	Running AI/ML workloads on Amazon EMR

### Lesson 4 of 15
### Amazon EMR CLuster Architecture and Use Cases

The central component of Amazon EMR is the CLUSTER. 
A CLUSTER is a collection of Amazon EC2 instances.
Each instance in the cluster is called a NODE, and every node has a role (or node type) within the cluster.
#### Three (3) types of nodes:
		primary - the primary node manages the cluster by running software components to coordinate the distribution of data and tasks among other nodes for processing. It also tracks and monitors the cluster's health.
		core - the core node runs tasks and stores data in the HDFS on your cluster. Multi-node clusters have at least one core node.
		task - the task node has software components that only runs tasks. It does not store data in HDFS. Tasks nodes are optional.
	
Data sources that Amazon EMR supports:
HDFS - Hadoop Distributed File System, The primar
	
to monitor Amazon EMR, use:
	CloudWatch, Ganglia, and CloudTrail for metrics and logs
	

### Lesson 8 of 15
### How Do I create AWS Resources for Use with Amazon EMR?
 Create VPC: vpc-0072bb529d5cd6117 
 Enable DNS hostnames
 Enable DNS resolution
 Verifying VPC creation: vpc-0072bb529d5cd6117 
 Create subnet: subnet-08aede75fbcf4d834 
 Create internet gateway: igw-0c16ed48302d6f979 
 Attach internet gateway to the VPC
 Create route table: rtb-0e850f228d7ae9cfd 
 Create route
 Associate route table
 Verifying route table creation
