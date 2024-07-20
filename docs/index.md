# AWS -hands on learning

Hands on approach for learning AWS

## Section 01 -  Introduction

| No. | Note | Description |
| --- | --- | --- |
| 1 | [Introduction to AWS](notes/01_introduction/Introduction-to-AWS.md) | Introduction to AWS |
| 2 | [Introduction to Virtualization](notes/01_introduction/Introduction-to-Virtualization.md) | Introduction to Virtualization |
| 3 | [Introduction to Cloud Computing](notes/01_introduction/Introduction-to-Cloud-Computing.md) | Introduction to Cloud Computing |
| 4 | [Lab 01 - Adding MFA to the account](labs/01-iam-mfa-lab.md) | Adding MFA to the account |
| 5 | [Lab 02 - Create an IAM user](labs/02-iam-user-lab.md) | Create an IAM user |
| 6 | [Lab 03 - Adding budget alets](labs/03-budget-lab.md) | Adding budget alerts |

## Section 02 - EC2 instances

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
| 12 | [ Lab 14 - Creating Spot instance fleet](labs/14-spot-instance-fleet.md)| Creating Spot instance fleet |
| 11 | [Lab 17 - Creating a Classic Load Balancer](labs/17-classic-load-balancer-lab.md) | Creating a Classic Load Balancer |
| 12 | [Lab 18 - Creating an Application Load Balancer](labs/18-application-load-balancer-lab.md) | Creating an Application Load Balancer |
| 13 | [Lab 19 - Creating an Application Load Balancer with HTTPS](labs/19-application-load-balancer-https-lab.md) | Creating an Application Load Balancer with HTTPS |
| 14 | [Lab 20 - Creating a Network Load Balancer](labs/20-network-load-balancer-lab.md) | Creating a Network Load Balancer |
| 15 | [Lab 21 - Creating an Auto Scaling group](labs/21-auto-scaling-group-lab.md) | Creating an Auto Scaling group |
| 16 | [Lab 22 - Configuring Auto Scaling policies](labs/22-auto-scaling-policies-lab.md) | Configuring Auto Scaling policies |
| 17 | [Lab 23 - Configuring Auto Scaling notifications](labs/23-auto-scaling-notifications-lab.md) | Configuring Auto Scaling notifications |

## Section 03 - Other Compute solutions

| No. | Note | Description |
| --- | --- | --- |
| 1 | [Lab 13 - Amazon Batch](labs/24-aws-batch-lab.md) | AWS Batch |
| 2 | [Lab 14 - AWS BeanStalk](labs/25-aws-beanstalk-lab.md) | AWS Beanstalk |


## Section 03 - S3 

| No. | Note | Description |
| --- | --- | --- |
| 1 | [Lab 13 - Create an S3 bucket and upload files](labs/13-s3-lab.md) | Create an S3 bucket |
| 2 | [Lab 14 - Versioning in S3 Buckets](labs/14-s3-versioning-lab.md) | Versioning in S3 Buckets |
| 3 | [Lab 15 - Lifecycle policies](labs/15-s3-lifecycle-lab.md) | Lifecycle policies |
| 4 | [Lab 16 - Configuring Cross-Region Replication](labs/16-s3-cross-region-replication-lab.md) | Configuring Cross-Region Replication |
| 5 | [Lab 17 - Setting up Static Website Hosting](labs/17-s3-static-website-lab.md) | Setting up Static Website Hosting |
| 6 | [Lab 18 - Implementing Object Locking](labs/18-s3-object-locking-lab.md) | Implementing Object Locking |


## Section 04 - Networking

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

## Section 05 - IAM

| No. | Note | Description |
| --- | --- | --- |
| 1 | [Lab 37 - IAM Users and Groups](labs/34-iam-users-and-groups.md) | IAM Users and Groups |
| 2 | [Lab 38 - IAM Roles and Policies](labs/35-iam-roles-and-policies.md) | IAM Roles and Policies |
| 3 | [Lab 39 - IAM Identity Federation](labs/36-iam-identity-federation.md) | IAM Identity Federation |
| 4 | [Lab 40 - IAM Access Analyzer](labs/37-iam-access-analyzer.md) | IAM Access Analyzer |
| 5 | [Lab 41 - IAM Auditing and Compliance](labs/38-iam-auditing-and-compliance.md) | IAM Auditing and Compliance |
| 6 | [Lab 42 - IAM Security Best Practices](labs/39-iam-security-best-practices.md) | IAM Security Best Practices |

## Section 06 - RDS

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


## Section 07 - Serverless

| No. | Note | Description |
| --- | --- | --- |
| 1 | [Lab 51 - AWS Lambda](labs/50-aws-lambda.md) | AWS Lambda |
| 2 | [Lab 52 - AWS Serverless](labs/51-aws-serverless.md) | AWS Serverless |


## Section 08 - Containers

| No. | Note | Description |
| --- | --- | --- |
| 1 | [Lab 53 - AWS Fargate](labs/52-aws-fargate.md) | AWS Fargate |
| 2 | [Lab 54 - AWS EKS](labs/53-ecs-load-balancer.md) | AWS ECS with Load Balancer |