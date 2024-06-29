1. You are deploying a web application on AWS that requires high availability. Which EC2 feature can help you automatically scale your instances based on traffic?
    - A. Amazon S3
    - B. Amazon EC2 Auto Scaling
    - C. Amazon Route 53
    - D. Amazon CloudWatch

2. You need to create a secure login to your EC2 instance. What is the recommended approach?
    - A. Use a username and password.
    - B. Configure SSH access with a weak password.
    - C. Utilize a key pair with a public key stored on the instance and a private key on your local machine.
    - D. Grant full access to your IAM user.

3. Your application on EC2 requires persistent storage for user data. Which storage option is most suitable?
    - A. Instance store
    - B. Amazon EBS volumes
    - C. Amazon S3 buckets
    - D. Amazon Glacier

4. What is the purpose of a security group in an EC2 environment?
    - A. To manage user access to IAM roles.
    - B. To define network traffic rules for your EC2 instances.
    - C. To schedule instance scaling events.
    - D. To create backups of your EBS volumes.

5. You are launching a new EC2 instance.  Where can you find pre-configured templates that include the operating system and software?
    - A. Amazon S3 buckets
    - B. Amazon Machine Images (AMIs)
    - C. Amazon Route 53 zones
    - D. AWS CloudTrail logs

6. When designing a cost-effective EC2 solution, which instance type would likely be the most expensive option?
    - A. t2.micro
    - B. c5.xlarge
    - C. m4.large
    - D. r5.metal

7. You accidentally terminated a critical EC2 instance with an EBS volume attached. How can you recover your data?
    - A. The data is lost as the instance is terminated.
    - B. Restore the instance from a recent Amazon Machine Image (AMI).
    - C. Use an EBS snapshot to create a new EBS volume and attach it to a new instance.
    - D. Redeploy your application from scratch.

8. Which of the following pricing models is best suited for workloads with unpredictable spikes in traffic?
    - A. On-Demand Instances
    - B. Reserved Instances
    - C. Spot Instances
    - D. Savings Plans

9. What AWS service can be used to centrally manage and automate tasks on your EC2 instances?
  - A. Amazon SQS
  - B. Amazon EC2 Systems Manager
  - C. Amazon CloudWatch
  - D. Amazon Inspector

10. You are building a disaster recovery plan for your EC2 instances. Which strategy is MOST effective for ensuring data availability?
    
  - A. Back up your EBS volumes to a different Availability Zone.
  - B. Implement a RAID configuration on your instance store volumes.
  - C. Rely on automatic instance restarts within the same Availability Zone.
  - D. Regularly create Amazon Machine Images (AMIs) of your instances.


### True or False

11. EC2 instances are virtual machines that provide scalable compute capacity in the cloud. (True/False)
12. You can only launch EC2 instances with a pre-installed operating system. (True/False)
13. Instance store volumes are a good choice for storing critical application data. (True/False)
14. Security groups can be used to control both inbound and outbound traffic for your EC2 instances. (True/False)
15. Amazon charges you for EC2 instances even when they are stopped. (True/False)

### Multiple Choice

16. Which of the following tools can be used to access and manage your EC2 instances through a web interface?
    - A. AWS CLI
    - B. AWS CloudFormation
    - C. Amazon EC2 console
    - D. AWS SDKs

17. You want to deploy a new application that requires a specific version of a software package. How can you ensure this software is included when launching your EC2 instance?
    - A. Include the software installation script in the user data for your instance.
    - B. Modify the chosen Amazon Machine Image (AMI) to include the software.
    - C. Upload the software package to an S3 bucket and download it during instance launch.
    - D. There is no way to guarantee specific software versions with EC2 instances.