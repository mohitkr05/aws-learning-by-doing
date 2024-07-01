# Introduction to AWS

## What is AWS?

Amazon Web Services (AWS)[^1] is a cloud computing platform provided by Amazon, offering a wide range of services to individuals, organizations, and governments. It is a comprehensive, secure, and scalable platform that enables customers to build, deploy, and manage applications and services with ease and flexibility.

## AWS Services

AWS provides over 200 fully featured services that span computing, storage, databases, analytics, machine learning, Internet of Things (IoT), security, and more. Some of the popular services offered by AWS include:

- Amazon Elastic Compute Cloud (EC2)
- Amazon Simple Storage Service (S3)
- Amazon Relational Database Service (RDS)
- Amazon DynamoDB
- Amazon Lambda
- Amazon CloudFront
- Amazon Virtual Private Cloud (VPC)
- Amazon Elastic Block Store (EBS)

## Benefits of AWS

AWS offers several benefits to its customers, including:

- Scalability: AWS enables customers to scale their resources up or down based on their requirements, allowing them to meet their changing business needs and control costs effectively.
- Security: AWS provides a secure and compliant platform with features such as encryption, identity and access management, and monitoring to ensure data protection and compliance with industry standards.
- Cost-effectiveness: AWS offers a pay-as-you-go pricing model, enabling customers to pay only for what they use and avoid upfront costs and long-term commitments.
- Reliability: AWS provides high availability, durability, and fault tolerance, ensuring that applications and services are always up and running.
- Flexibility: AWS enables customers to choose the tools, programming languages, operating systems, and databases they prefer, giving them the freedom to build and run their applications and services as they like.

## Getting Started with AWS

To get started with AWS, customers can create an AWS account and access the AWS Management Console, which provides a web-based interface to access and manage AWS services. AWS also offers various SDKs and APIs for developers to build applications and services that interact with AWS services programmatically.

In addition, AWS provides a wealth of resources to help customers learn about AWS and develop their skills, including documentation, training courses, certification programs, forums, and support services.

## Creating your Account with AWS

1. Go to the AWS website at https://aws.amazon.com/.
2. Click on the "Create an AWS Account" button located in the top right corner of the page.
3. Enter your email address, a password, and your AWS account name, then click on "Continue".
4. Enter your personal information, including your name, company name (if applicable), address, and phone number.
5. Select your payment method, which can be a credit card, debit card, or bank account. Note that some AWS services offer a free tier with limited usage.
6. Enter your billing address and click on "Verify and Add".
7. Review the AWS Customer Agreement and click on "Create Account and Continue".
8. AWS will then send a verification code to your email address. Enter the verification code in the provided field and click on "Verify".
9. You will then be prompted to choose a support plan, which can be Basic, Developer, Business, or Enterprise. Select the plan that best suits your needs and click on "Continue".
10. AWS will then redirect you to the AWS Management Console, where you can access and manage your AWS services.

## Account security

1. Log in to your AWS account and navigate to the AWS Management Console.
2. Click on the `Services` dropdown menu and select `IAM` under the `Security, Identity, & Compliance` section.
3. In the IAM dashboard, you can create and manage IAM users, groups, and roles to control access to your AWS resources.

### Secure Access to your Root user account

- To secure your account, you have to configure multi-factor authentication (MFA) for IAM users and the root account.

### Create a seperate user for console access

1. Click on the "Add user" button to create a new IAM user for console access.
2. Enter a name for the new IAM user and select "Programmatic access" and "AWS Management Console access" as the access type.
3. Create a password for the new IAM user or let AWS generate one for you, and then click on "Next: Permissions".
4. Assign the necessary permissions to the new IAM user, either by adding them to an existing IAM group or by creating a new IAM policy.
5. Review the permissions and click on "Next: Tags" to add optional metadata tags to the new IAM user.
6. Review the tags and click on "Next: Review" to review the IAM user's settings.
7. Review the settings and click on "Create user" to create the new IAM user.
8. Note down the IAM user's console login URL, which should be in the format of https://ACCOUNT-ID.signin.aws.amazon.com/console/.



## Reference Links

[^1]: [AWS Homepage](https://aws.amazon.com/)



