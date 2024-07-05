# AWS -hands on learning

Hands on approach for learning AWS

## Chapters

The chapters are sorted in various sections

### Section 01 -  Introduction

| No. | Note | Description |
| --- | --- | --- |
| 1 | [Introduction to AWS](notes/01_introduction/Introduction-to-AWS.md) | Introduction to AWS |
| 2 | [Introduction to Virtualization](notes/01_introduction/Introduction-to-Virtualization.md) | Introduction to Virtualization |
| 3 | [Introduction to Cloud Computing](notes/01_introduction/Introduction-to-Cloud-Computing.md) | Introduction to Cloud Computing |
| 4 | [Lab 01 - Adding MFA to the account](labs/01-iam-mfa-lab.md) | Adding MFA to the account |
| 5 | [Lab 02 - Create an IAM user](labs/02-iam-user-lab.md) | Create an IAM user |
| 6 | [Lab 03 - Adding budget alets](labs/03-budget-lab.md) | Adding budget alerts |



### Section 02 - EC2 instances

| No. | Note | Description |
| --- | --- | --- |
| 1 | [Notes - EC2 Instances](notes/02_EC2/01-Introduction-to-EC2.md) | Introduction to EC2 |
| 2 | [Lab 04 - Create an EC2 instance](labs/04-ec2-lab.md) | Launch an EC2 instance using console |
| 3 | [Lab 05 - What happens to public IP when you restart an instance](labs/05-public-ip-lab.md) | What happens to public IP when you restart an instance |
| 4 | [Lab 06 - Launching an instance with userscript](labs/06-userscript-lab.md) | Launching an instance with userscript |
| 5 | [Lab 07 - Attaching an Elastic IP](labs/07-elastic-ip-lab.md) | Attaching an Elastic IP |
| 6 | [Lab 08 - Attaching an EBS volume](labs/08-ebs-lab.md) | Attaching an EBS volume |
| 7 | [Lab 09 - Restoring an EBS volume](labs/09-restore-lab.md) | Restoring an EBS volume |
| 8 | [Lab 10 - Understanding bursting nature](labs/10-bursting-lab.md) | Understanding bursting nature |
| 9 | [Lab 11 - Creating a static website](labs/11-static-website-lab.md) | Creating a static website |
| 10 | [Lab 12 - Understanding placement groups](labs/12-placement-groups.md) | Cleaning up all resources |
| 11 | [ Lab 13 - Creating a launch template](labs/13-launch-template.md)| Creating a launch template |
| 12 | [ Lab 14 - Creating Spot instance fleet](labs/14-spot-instance-fleet)| Creating Spot instance fleet |
| 11 | [Lab 17 - Creating a Classic Load Balancer](labs/17-classic-load-balancer-lab.md) | Creating a Classic Load Balancer |
| 12 | [Lab 18 - Creating an Application Load Balancer](labs/18-application-load-balancer-lab.md) | Creating an Application Load Balancer |
| 13 | [Lab 19 - Creating an Application Load Balancer with HTTPS](labs/19-application-load-balancer-https-lab.md) | Creating an Application Load Balancer with HTTPS |
| 14 | [Lab 20 - Creating a Network Load Balancer](labs/20-network-load-balancer-lab.md) | Creating a Network Load Balancer |
| 15 | [Lab 21 - Creating an Auto Scaling group](labs/21-auto-scaling-group-lab.md) | Creating an Auto Scaling group |
| 16 | [Lab 22 - Configuring Auto Scaling policies](labs/22-auto-scaling-policies-lab.md) | Configuring Auto Scaling policies |
| 17 | [Lab 23 - Configuring Auto Scaling notifications](labs/23-auto-scaling-notifications-lab.md) | Configuring Auto Scaling notifications |


### Section 03 - Other Compute solutions

| No. | Note | Description |
| --- | --- | --- |
| 1 | [Lab 13 - Amazon Batch](labs/24-aws-batch-lab.md) | AWS Batch |
### Section 03 - S3 

| No. | Note | Description |
| --- | --- | --- |
| 1 | [Lab 13 - Create an S3 bucket and upload files](labs/13-s3-lab.md) | Create an S3 bucket |
| 2 | [Lab 14 - Versioning in S3 Buckets](labs/14-s3-versioning-lab.md) | Versioning in S3 Buckets |
| 3 | [Lab 15 - Lifecycle policies](labs/15-s3-lifecycle-lab.md) | Lifecycle policies |
| 4 | [Lab 16 - Configuring Cross-Region Replication](labs/16-s3-cross-region-replication-lab.md) | Configuring Cross-Region Replication |
| 5 | [Lab 17 - Setting up Static Website Hosting](labs/17-s3-static-website-lab.md) | Setting up Static Website Hosting |
| 6 | [Lab 18 - Implementing Object Locking](labs/18-s3-object-locking-lab.md) | Implementing Object Locking |

### Section 04 - Networking

| No. | Note | Description |
| --- | --- | --- |
| 1 | [Lab 19 - Create a VPC](labs/16-create-a-vpc.md) | Create a VPC |
| 2 | [Lab 20 - Create a Subnet](labs/17-create-a-subnet.md) | Create a Subnet |
| 3 | [Lab 21 - Associate a subnet with a route table](labs/18-associate-a-subnet-with-a-route-table.md) | Associate a subnet with a route table |
| 4 | [Lab 22 - Create a Route Table](labs/19-create-a-route-table.md) | Create a Route Table |
| 5 | [Lab 23 - Associate a route table with a VPC](labs/20-associate-a-route-table-with-a-vpc.md) | Associate a route table with a VPC |
| 6 | [Lab 24 - Create a NACL](labs/21-create-a-nacl.md) | Create a NACL |
| 7 | [Lab 25 - Associate a NACL with a subnet](labs/22-associate-a-nacl-with-a-subnet.md) | Associate a NACL with a subnet |
| 8 | [Lab 26 - Create a Security Group](labs/23-create-a-security-group.md) | Create a Security Group |
| 9 | [Lab 27 - Associate a Security Group with an EC2 instance](labs/24-associate-a-security-group-with-an-ec2-instance.md) | Associate a Security Group with an EC2 instance |
| 10 | [Lab 28 - Elastic Network Interfaces](labs/25-elastic-network-interfaces.md) | Elastic Network Interfaces |
| 11 | [Lab 29 - VPC Peering](labs/26-vpc-peering.md) | VPC Peering |
| 12 | [Lab 30 - Direct Connect](labs/27-direct-connect.md) | Direct Connect |
| 13 | [Lab 31 - VPC Flow Logs](labs/28-vpc-flow-logs.md) | VPC Flow Logs |
| 14 | [Lab 32 - VPC Endpoints](labs/29-vpc-endpoints.md) | VPC Endpoints |
| 15 | [Lab 33 - Transit Gateway](labs/30-transit-gateway.md) | Transit Gateway |
| 16 | [Lab 34 - Site-to-Site VPN](labs/31-site-to-site-vpn.md) | Site-to-Site VPN |
| 17 | [Lab 35 - Client VPN](labs/32-client-vpn.md) | Client VPN |
| 18 | [Lab 36 - Network Access Control Lists](labs/33-network-access-control-lists.md) | Network Access Control Lists |

### Section 04 - IAM

| No. | Note | Description |
| --- | --- | --- |
| 1 | [Lab 37 - IAM Users and Groups](labs/34-iam-users-and-groups.md) | IAM Users and Groups |
| 2 | [Lab 38 - IAM Roles and Policies](labs/35-iam-roles-and-policies.md) | IAM Roles and Policies |
| 3 | [Lab 39 - IAM Identity Federation](labs/36-iam-identity-federation.md) | IAM Identity Federation |
| 4 | [Lab 40 - IAM Access Analyzer](labs/37-iam-access-analyzer.md) | IAM Access Analyzer |
| 5 | [Lab 41 - IAM Auditing and Compliance](labs/38-iam-auditing-and-compliance.md) | IAM Auditing and Compliance |
| 6 | [Lab 42 - IAM Security Best Practices](labs/39-iam-security-best-practices.md) | IAM Security Best Practices |


### Section 05 - RDS

| No. | Note | Description |
| --- | --- | --- |
| 1 | [Lab 43 - RDS Security Best Practices](labs/40-rds-security-best-practices.md) | RDS Security Best Practices |
| 2 | [Lab 44 - Amazon RDS Read Replicas](labs/41-rds-read-replicas.md) | Amazon RDS Read Replicas |
| 3 | [Lab 45 - Amazon Aurora](labs/42-amazon-aurora.md) | Amazon Aurora |
| 4 | [Lab 46 - Amazon Multi-AZ Deployments](labs/43-amazon-multi-az-deployments.md) | Amazon Multi-AZ Deployments |
| 5 | [Lab 47 - Amazon RDS Backups](labs/44-amazon-rds-backups.md) | Amazon RDS Backups |
| 6 | [Lab 48 - Amazon RDS Performance Optimization](labs/45-amazon-rds-performance-optimization.md) | Amazon RDS Performance Optimization |
| 7 | [Lab 49 - Amazon RDS Monitoring and Logging](labs/46-amazon-rds-monitoring-and-logging.md) | Amazon RDS Monitoring and Logging |
| 8 | [Lab 50 - Amazon RDS Encryption](labs/47-amazon-rds-encryption.md) | Amazon RDS Encryption |

### Section 06 - Serverless

| No. | Note | Description |
| --- | --- | --- |
| 1 | [Lab 51 - AWS Lambda](labs/50-aws-lambda.md) | AWS Lambda |
| 2 | [Lab 52 - AWS Lambda with S3 Event Trigger](labs/50-aws-lambda-with-s3-event-trigger.md) | AWS Lambda with S3 Event Trigger |
| 3 | [Lab 53 - AWS Lambda with API Gateway](labs/50-aws-lambda-with-api-gateway.md) | AWS Lambda with API Gateway |
| 4 | [Lab 54 - AWS Lambda with CloudWatch Events](labs/50-aws-lambda-with-cloudwatch-events.md) | AWS Lambda with CloudWatch Events |
| 5 | [Lab 55 - Amazon DynamoDB](labs/51-amazon-dynamodb.md) | Amazon DynamoDB |
| 6 | [Lab 56 - DynamoDB - Basic CRUD Operations](labs/51-dynamodb-basic-crud-operations.md) | DynamoDB - Basic CRUD Operations |
| 7 | [Lab 57 - DynamoDB - Query and Scan Operations](labs/51-dynamodb-query-and-scan-operations.md) | DynamoDB - Query and Scan Operations |
| 8 | [Lab 58 - DynamoDB - Indexes and GSI](labs/51-dynamodb-indexes-and-gsi.md) | DynamoDB - Indexes and GSI |
| 9 | [Lab 59 - Amazon SQS](labs/52-amazon-sqs.md) | Amazon SQS |
| 10 | [Lab 60 - SQS - Standard Queue](labs/52-sqs-standard-queue.md) | SQS - Standard Queue |
| 11 | [Lab 61 - SQS - FIFO Queue](labs/52-sqs-fifo-queue.md) | SQS - FIFO Queue |
| 12 | [Lab 62 - SQS - Message Visibility Timeout](labs/52-sqs-message-visibility-timeout.md) | SQS - Message Visibility Timeout |
| 13 | [Lab 63 - Amazon SNS](labs/53-amazon-sns.md) | Amazon SNS |
| 14 | [Lab 64 - SNS - Publish/Subscribe Model](labs/53-sns-publish-subscribe-model.md) | SNS - Publish/Subscribe Model |
| 15 | [Lab 65 - SNS - Topic and Subscription](labs/53-sns-topic-and-subscription.md) | SNS - Topic and Subscription |
| 16 | [Lab 66 - SNS - SMS and Email Subscriptions](labs/53-sns-sms-and-email-subscriptions.md) | SNS - SMS and Email Subscriptions |
| 17 | [Lab 67 - AWS Batch](labs/54-aws-batch.md) | AWS Batch |
| 18 | [Lab 68 - Batch - Job Definition and Job Queue](labs/54-batch-job-definition-and-job-queue.md) | Batch - Job Definition and Job Queue |
| 19 | [Lab 69 - Batch - Job Submission and Monitoring](labs/54-batch-job-submission-and-monitoring.md) | Batch - Job Submission and Monitoring |
| 20 | [Lab 70 - Batch - Compute Environment and Job Dependency](labs/54-batch-compute-environment-and-job-dependency.md) | Batch - Compute Environment and Job Dependency |
| 21 | [Lab 56 - AWS Glue](labs/55-aws-glue.md) | AWS Glue |
| 22 | [Lab 56A - Glue - Data Catalog and Jobs](labs/55-glue-data-catalog-and-jobs.md) | Glue - Data Catalog and Jobs |
| 23 | [Lab 56B - Glue - ETL Job and Crawler](labs/55-glue-etl-job-and-crawler.md) | Glue - ETL Job and Crawler |
| 24 | [Lab 56C - Glue - Data Quality and Job Bookmarks](labs/55-glue-data-quality-and-job-bookmarks.md) | Glue - Data Quality and Job Bookmarks |
| 25 | [Lab 57 - AWS Step Functions](labs/56-aws-step-functions.md) | AWS Step Functions |
| 26 | [Lab 57A - Step Functions - Simple Workflow](labs/56-step-functions-simple-workflow.md) | Step Functions - Simple Workflow |
| 27 | [Lab 57B - Step Functions - Parallel Execution](labs/56-step-functions-parallel-execution.md) | Step Functions - Parallel Execution |
| 28 | [Lab 57C - Step Functions - Error Handling and Retry](labs/56-step-functions-error-handling-and-retry.md) | Step Functions - Error Handling and Retry |

## Certifications

- [AWS Solution Architect Associate exam AWS SAA-03](notes/AWS-Solution-architect-exam/start-here.md)
