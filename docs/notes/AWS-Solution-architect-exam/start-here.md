# AWS Solution Architect Associate Exam Bootcamp


- [Official URL](https://aws.amazon.com/certification/certified-solutions-architect-associate/)



## Who should take this exam?

AWS Certified Solutions Architect - Associate is a great starting point on the AWS Certification path for individuals who may have any of the following:

- Experience in AWS technology
- Strong on-premises IT experience and understanding of mapping on-premises to cloud
- Experience working in other cloud services


## What does it take to earn this certification?

To earn this certification, you’ll need to take and pass the AWS Certified Solutions Architect - Associate exam (SAA-C03). The exam features a combination of two question formats: multiple choice and multiple response. Additional information, such as the exam content outline and passing score, is in the exam guide. The exam also validates a candidate’s ability to complete the following tasks:
 - Design solutions that incorporate AWS services to meet current business requirements and future projected needs
 - Design architectures that are secure, resilient, high-performing, and cost-optimized
 - Review existing solutions and determine improvements to existing solutions

## Exam content

There are two types of questions on the exam:

- Multiple choice: Has one correct response and three incorrect responses (distractors)
- Multiple response: Has two or more correct responses out of five or more response options
- Unanswered questions are scored as incorrect; there is no penalty for guessing. The exam includes 50 questions that affect your score.
- The exam includes 15 unscored questions that do not affect your score. AWS collects information about performance on these unscored questions to evaluate these questions for future use as scored questions. These unscored questions are not identified on the exam.

### Domains

The exam has the following content domains and weightings:

Domain | Name |  Weighting | Total questions* | 
------ | ----- | --- |  ----- |  
1 | Design Secure Architectures | 30%  | 20 | 
2 | Design Resilient Architectures | 26% |  17 | 
3 | Design High-Performing Architectures | 24% | 15 |
4 | Design Cost-Optimized Architectures | 20% | 13 |
x | Total | 100% |  65 | 

* Approximate number, some questions would be overlapped.

### Sample questions 


### Detailed guideline

# Detalied exam guide

## Domain 1: Design Secure Architectures (30% of scored content)

### Task Statement 1.1: Design secure access to AWS resources

#### Knowledge of

   - Access controls and management across multiple accounts
   - AWS federated access and identity services (e.g., AWS IAM, AWS IAM Identity Center)
   - AWS global infrastructure (e.g., Availability Zones, AWS Regions)
   - AWS security best practices (e.g., the principle of least privilege)
   - The AWS shared responsibility model

#### Skills in
  - Applying AWS security best practices to IAM users and root users (e.g., MFA)
  - Designing a flexible authorization model (IAM users, groups, roles, and policies)
  - Designing a role-based access control strategy (e.g., AWS STS, role switching, cross-account access)
  - Designing a security strategy for multiple AWS accounts (e.g., AWS Control Tower, SCPs)
  - Determining the appropriate use of resource policies for AWS services
  - Determining when to federate a directory service with IAM roles

### Task Statement 1.2: Design secure workloads and applications

#### Knowledge of
  - Application configuration and credentials security
  - AWS service endpoints
  - Control ports, protocols, and network traffic on AWS
  - Secure application access
  - Security services with appropriate use cases (e.g., Amazon Cognito, Amazon GuardDuty, Amazon Macie)
  - Threat vectors external to AWS (e.g., DDoS, SQL injection)


#### Skills in
  - Designing VPC architectures with security components (e.g., security groups, route tables, network ACLs, NAT gateways)
  - Determining network segmentation strategies (e.g., public and private subnets)
  - Integrating AWS services to secure applications (e.g., AWS Shield, AWS WAF, IAM Identity Center, AWS Secrets Manager)
  - Securing external network connections to and from the AWS Cloud (e.g., VPN, AWS Direct Connect)

### Task Statement 1.3: Determine appropriate data security controls

#### Knowledge of
  - Data access and governance
  - Data recovery
  - Data retention and classification
  - Encryption and key management
#### Skills in
  - Aligning AWS technologies to meet compliance requirements
  - Encrypting data at rest (e.g., AWS KMS)
  - Encrypting data in transit (e.g., AWS Certificate Manager using TLS)
  - Implementing access policies for encryption keys
  - Implementing data backups and replications
  - Implementing policies for data access, lifecycle, and protection
  - Rotating encryption keys and renewing certificates

## Domain 2: Design Resilient Architectures

### Task Statement 2.1: Design scalable and loosely coupled architectures

#### Knowledge of
  - API creation and management (e.g., Amazon API Gateway, REST API)
  - AWS managed services with appropriate use cases (e.g., AWS Transfer Family, Amazon SQS, Secrets Manager)
  - Caching strategies
  - Design principles for microservices (e.g., stateless vs. stateful workloads)
  - Event-driven architectures
  - Horizontal and vertical scaling
  - Edge accelerators (e.g., CDN)
  - Migrating applications into containers
  - Load balancing concepts (e.g., Application Load Balancer)
  - Multi-tier architectures
  - Queuing and messaging concepts (e.g., publish/subscribe)
  - Serverless technologies and patterns (e.g., AWS Fargate, AWS Lambda)
  - Storage types with associated characteristics (e.g., object, file, block)
  - Container orchestration (e.g., Amazon ECS, Amazon EKS)
  - When to use read replicas
  - Workflow orchestration (e.g., AWS Step Functions)
#### Skills in
  - Designing event-driven, microservice, and/or multi-tier architectures based on requirements
  - Determining scaling strategies for components in an architecture design
  - Determining AWS services required to achieve loose coupling based on requirements
  - Determining when to use containers
  - Determining when to use serverless technologies and patterns
  - Recommending appropriate compute, storage, networking, and database technologies based on requirements
  - Using purpose-built AWS services for workloads

### Task Statement 2.2: Design highly available and/or fault-tolerant architectures 
#### Knowledge of
  - AWS global infrastructure (e.g., Availability Zones, AWS Regions, Amazon Route 53)
  - AWS managed services with appropriate use cases (e.g., Amazon Comprehend, Amazon Polly)
  - Basic networking concepts (e.g., route tables)
  - Disaster recovery (DR) strategies (e.g., backup and restore, pilot light, warm standby, active-active failover, RPO, RTO)
  - Distributed design patterns
  - Failover strategies
  - Immutable infrastructure
  - Load balancing concepts (e.g., Application Load Balancer)
  - Proxy concepts (e.g., Amazon RDS Proxy)
  - Service quotas and throttling (e.g., configuring service quotas for a workload in a standby environment)
  - Storage options and characteristics (e.g., durability, replication)
  - Workload visibility (e.g., AWS X-Ray)
#### Skills in
  - Determining automation strategies to ensure infrastructure integrity
  - Determining AWS services required for highly available and/or fault-tolerant architecture across AWS Regions or Availability Zones
  - Identifying metrics based on business requirements for a highly available solution
  - Implementing designs to mitigate single points of failure
  - Implementing strategies to ensure data durability and availability (e.g., backups)
  - Selecting an appropriate DR strategy to meet business requirements
  - Using AWS services to improve reliability of legacy applications and applications not built for the cloud
  - Using purpose-built AWS services for workloads

## Domain 3: Design High-Performing Architectures

### Task Statement 3.1: Determine high-performing and/or scalable storage solutions 
#### Knowledge of
  - Hybrid storage solutions to meet business requirements
  - Storage services with appropriate use cases (e.g., Amazon S3, Amazon EFS, Amazon EBS)
  - Storage types with associated characteristics (e.g., object, file, block)
#### Skills in
  - Determining storage services and configurations to meet performance demands
  - Determining storage services that can scale to accommodate future needs

### Task Statement 3.2: Design high-performing and elastic compute solutions 
#### Knowledge of
  - AWS compute services with appropriate use cases (e.g., AWS Batch, Amazon EMR, Fargate)
  - Distributed computing concepts supported by AWS global infrastructure and edge services
  - Queuing and messaging concepts (e.g., publish/subscribe)
  - Scalability capabilities with appropriate use cases (e.g., Amazon EC2 Auto Scaling, AWS Auto Scaling)
  - Serverless technologies and patterns (e.g., Lambda, Fargate)
  - Container orchestration (e.g., Amazon ECS, Amazon EKS)
#### Skills in
  - Decoupling workloads for independent scaling of components
  - Identifying metrics and conditions to perform scaling actions
  - Selecting appropriate compute options and features (e.g., EC2 instance types) to meet business requirements
  - Selecting appropriate resource type and size (e.g., Lambda memory) to meet business requirements

### Task Statement 3.3: Determine high-performing database solutions 
#### Knowledge of
  - AWS global infrastructure (e.g., Availability Zones, AWS Regions)
  - Caching strategies and services (e.g., Amazon ElastiCache)
  - Data access patterns (e.g., read-intensive vs. write-intensive)
  - Database capacity planning (e.g., capacity units, instance types, Provisioned IOPS)
  - Database connections and proxies
  - Database engines with appropriate use cases (e.g., heterogeneous vs. homogeneous migrations)
  - Database replication (e.g., read replicas)
  - Database types and services (e.g., serverless, relational vs. non-relational, in-memory)
#### Skills in
  - Configuring read replicas to meet business requirements
  - Designing database architectures
  - Determining appropriate database engine (e.g., MySQL vs. PostgreSQL)
  - Determining appropriate database type (e.g., Amazon Aurora, Amazon DynamoDB)
  - Integrating caching to meet business requirements

### Task Statement 3.4: Determine high-performing and/or scalable network architectures 
#### Knowledge of
  - Edge networking services with appropriate use cases (e.g., Amazon CloudFront, AWS Global Accelerator)
  - Network architecture design (e.g., subnet tiers, routing, IP addressing)
  - Load balancing concepts (e.g., Application Load Balancer)
  - Network connection options (e.g., AWS VPN, Direct Connect, AWS PrivateLink)
#### Skills in
  - Creating network topology for various architectures (e.g., global, hybrid, multi-tier)
  - Determining network configurations that can scale to accommodate future needs
  - Determining appropriate placement of resources to meet business requirements
  - Selecting appropriate load balancing strategy

### Task Statement 3.5: Determine high-performing data ingestion and transformation solutions
#### Knowledge of
  - Data analytics and visualization services with appropriate use cases (e.g., Amazon Athena, AWS Lake Formation, Amazon QuickSight)
  - Data ingestion patterns (e.g., frequency)
  - Data transfer services with appropriate use cases (e.g., AWS DataSync, AWS Storage Gateway)
  - Data transformation services with appropriate use cases (e.g., AWS Glue)
  - Secure access to ingestion access points
  - Sizes and speeds needed to meet business requirements
  - Streaming data services with appropriate use cases (e.g., Amazon

 Kinesis)
#### Skills in
  - Building and securing data lakes
  - Designing data streaming architectures
  - Designing data transfer solutions
  - Implementing visualization strategies
  - Selecting appropriate compute options for data processing (e.g., Amazon EMR)
  - Selecting appropriate configurations for ingestion
  - Transforming data between formats (e.g., .csv to .parquet)

## Domain 4: Design Cost-Optimized Architectures

### Task Statement 4.1: Design cost-optimized storage solutions 
#### Knowledge of
  - Access options (e.g., S3 bucket with Requester Pays object storage)
  - AWS cost management service features (e.g., cost allocation tags, multi-account billing)
  - AWS cost management tools with appropriate use cases (e.g., AWS Cost Explorer, AWS Budgets, AWS Cost and Usage Report)
  - AWS storage services with appropriate use cases (e.g., Amazon FSx, Amazon EFS, Amazon S3, Amazon EBS)
  - Backup strategies
  - Block storage options (e.g., HDD volume types, SSD volume types)
  - Data lifecycles
  - Hybrid storage options (e.g., DataSync, Transfer Family, Storage Gateway)
  - Storage access patterns
  - Storage tiering (e.g., cold tiering for object storage)
  - Storage types with associated characteristics (e.g., object, file, block)
#### Skills in
  - Designing appropriate storage strategies (e.g., batch uploads to S3 vs. individual uploads)
  - Determining the correct storage size for a workload
  - Determining the lowest cost method of transferring data for a workload to AWS storage
  - Determining when storage auto-scaling is required
  - Managing S3 object lifecycles
  - Selecting appropriate backup and/or archival solution
  - Selecting appropriate service for data migration to storage services
  - Selecting appropriate storage tier
  - Selecting correct data lifecycle for storage
  - Selecting the most cost-effective storage service for a workload

### Task Statement 4.2: Design cost-optimized compute solutions 
#### Knowledge of
  - AWS cost management service features (e.g., cost allocation tags, multi-account billing)
  - AWS cost management tools with appropriate use cases (e.g., Cost Explorer, AWS Budgets, AWS Cost and Usage Report)
  - AWS global infrastructure (e.g., Availability Zones, AWS Regions)
  - AWS purchasing options (e.g., Spot Instances, Reserved Instances, Savings Plans)
  - Distributed compute strategies (e.g., edge processing)
  - Hybrid compute options (e.g., AWS Outposts, AWS Snowball Edge)
  - Instance types, families, and sizes (e.g., memory optimized, compute optimized, virtualization)
  - Optimization of compute utilization (e.g., containers, serverless computing, microservices)
  - Scaling strategies (e.g., auto-scaling, hibernation)
#### Skills in
  - Determining appropriate load balancing strategy (e.g., Application Load Balancer vs. Network Load Balancer vs. Gateway Load Balancer)
  - Determining appropriate scaling methods and strategies for elastic workloads (e.g., horizontal vs. vertical, EC2 hibernation)
  - Determining cost-effective AWS compute services with appropriate use cases (e.g., Lambda, Amazon EC2, Fargate)
  - Determining required availability for different classes of workloads (e.g., production vs. non-production workloads)
  - Selecting appropriate instance family for a workload
  - Selecting appropriate instance size for a workload

### Task Statement 4.3: Design cost-optimized database solutions 
#### Knowledge of
  - AWS cost management service features (e.g., cost allocation tags, multi-account billing)
  - AWS cost management tools with appropriate use cases (e.g., Cost Explorer, AWS Budgets, AWS Cost and Usage Report)
  - Caching strategies
  - Data retention policies
  - Database capacity planning (e.g., capacity units)
  - Database connections and proxies
  - Database engines with appropriate use cases (e.g., heterogeneous vs. homogeneous migrations)
  - Database replication (e.g., read replicas)
  - Database types and services (e.g., relational vs. non-relational, Aurora, DynamoDB)
#### Skills in
  - Designing appropriate backup and retention policies (e.g., snapshot frequency)
  - Determining appropriate database engine (e.g., MySQL vs. PostgreSQL)
  - Determining cost-effective AWS database services with appropriate use cases (e.g., DynamoDB vs. Amazon RDS, serverless)
  - Determining cost-effective AWS database types (e.g., time series format, columnar format)
  - Migrating database schemas and data to different locations and/or different database engines

### Task Statement 4.4: Design cost-optimized network architectures 
#### Knowledge of
  - AWS cost management service features (e.g., cost allocation tags, multi-account billing)
  - AWS cost management tools with appropriate use cases (e.g., Cost Explorer, AWS Budgets, AWS Cost and Usage Report)
  - Load balancing concepts (e.g., Application Load Balancer)
  - NAT gateways (e.g., NAT instance costs vs. NAT gateway costs)
  - Network connectivity (e.g., private lines, dedicated lines, VPNs)
  - Network routing, topology, and peering (e.g., AWS Transit Gateway, VPC peering)
  - Network services with appropriate use cases (e.g., DNS)
#### Skills in
  - Configuring appropriate NAT gateway types for a network (e.g., a single shared NAT gateway vs. NAT gateways for each Availability Zone)
  - Configuring appropriate network connections (e.g., Direct Connect vs. VPN vs. internet)
  - Configuring appropriate network routes to minimize network transfer costs (e.g., Region to Region, Availability Zone to Availability Zone, private to public, Global Accelerator, VPC endpoints)
  - Determining strategic needs for content delivery networks (CDNs) and edge caching
  - Reviewing existing workloads for network optimizations
  - Selecting appropriate throttling strategy
  - Selecting appropriate bandwidth allocation for a network device (e.g., a single VPN vs. multiple VPNs, Direct Connect speed)


### References


- [Exam Prep Official Practice Question Set: AWS Certified Solutions Architect - Associate (SAA-C03 - English)](https://explore.skillbuilder.aws/learn/course/external/view/elearning/13266/aws-certified-solutions-architect-associate-official-practice-question-set-saa-c03-english?saa=sec&sec=prep)
- [AWS Well architected labs](https://www.wellarchitectedlabs.com/)
- [AWS Ramp up](https://d1.awsstatic.com/training-and-certification/ramp-up_guides/Ramp-Up_Guide_Architect.pdf)
- [AWS Well-Architected Labs](https://aws.amazon.com/well-architected/)
- [Tutorails Dojo](https://tutorialsdojo.com/aws-certified-solutions-architect-associate-saa-c03/)
- [AWS Webinars](https://pages.awscloud.com/traincert-twitch-power-hour-architecting.html)
- [Topics mindmap](mindmap.md)
- [Topic Details](topic-details.md)