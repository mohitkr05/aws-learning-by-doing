# Sample questions : AWS Regions and AZs

**Topic: AWS Regions**

1. You are deploying a new web application with high availability requirements. Which of the following is the MOST important factor to consider when selecting an AWS Region?
    * A. Proximity to your end users
    * B. Number of available Availability Zones
    * C. Cost of EC2 instances
    * D. Availability of specific AWS services

**Explanation:** While all the options are important factors, for high availability,  having a sufficient number of Availability Zones (AZs) within a Region is crucial. This allows you to distribute your resources across AZs to minimize downtime from isolated failures.

**Topic: AWS Availability Zones**

2. An Availability Zone (AZ) failure disrupts a production database hosted on Amazon RDS. To ensure high availability, what is the recommended recovery action?
    * A. Manually failover the database to a secondary instance in another AZ.
    * B. Re-launch the database instance in the same AZ.
    * C. Restore the database from a recent backup.
    * D. No action needed, RDS automatically recovers within the AZ.

**Explanation:** Option A is the best course of action. RDS offers Multi-AZ deployments where a standby replica resides in a different AZ. During an AZ outage, you can manually initiate a failover to the healthy replica for minimal downtime.

**Topic: AWS Outposts**

3. Your company requires low-latency access to on-premises resources for a critical application.  Which AWS service would be the most suitable solution?
    * A. AWS Direct Connect
    * B. AWS Transit Gateway
    * C. AWS LocalZone
    * D. AWS Wavelength

**Explanation:** AWS Outposts, delivered through AWS LocalZone, extends AWS services and infrastructure to your on-premises environment. This provides a low-latency connection between your on-premises resources and the application running on LocalZone.

**Topic: AWS Wavelength**

4. You are developing a mobile application that requires ultra-low latency for real-time processing at the mobile edge.  Which AWS service is best suited for this scenario?
    * A. Amazon EC2
    * B. AWS Lambda@Edge
    * C. Amazon API Gateway
    * D. AWS Wavelength

**Explanation:** AWS Wavelength extends AWS services to the mobile network edge, providing single-digit millisecond latency for mobile applications. This is ideal for real-time processing at the edge of the network.


## AWS SAA Exam Simulator:

**Topic 1: AWS Regions**

1. **What is the PRIMARY benefit of using multiple AWS Regions for your application deployment?**
    * A. Cost optimization across different regions
    * B. Improved latency for geographically dispersed users
    * C. Increased number of available instance types
    * D. Enhanced security isolation between application components

2. **Which of the following statements is MOST accurate about AWS Regions?**
    * A. All regions offer identical services and features.
    * B. Regions are completely isolated from each other.
    * C. Every region has at least two Availability Zones.
    * D. Data transfer between regions is always free of charge.

**Topic 2: AWS Availability Zones (AZs)**

1. **What is the MAIN purpose of deploying resources across multiple Availability Zones within a Region?**
    * A. To leverage different pricing models for compute resources
    * B. To enforce data residency requirements for specific regulations
    * C. To achieve higher levels of fault tolerance and redundancy
    * D. To isolate development, testing, and production environments

2. **How do Availability Zones within a Region guarantee fault tolerance?**
    * A. Each AZ has a completely independent power grid and network infrastructure.
    * B. Resources are automatically replicated across all AZs within the Region.
    * C. AZs are geographically separated, minimizing the impact of localized outages.
    * D. AWS automatically migrates resources to a healthy AZ in case of failure in one AZ.

**Topic 3: AWS Outposts**

1. **Which scenario is BEST suited for deploying an application using AWS Outposts?**
    * A. Building a serverless application with minimal latency requirements
    * B. Extending your existing on-premises infrastructure to the AWS cloud
    * C. Hosting highly sensitive data that requires strict regulatory compliance
    * D. Managing a large fleet of virtual machines with pay-as-you-go pricing

2. **What is a KEY advantage of deploying AWS Outposts compared to a traditional on-premises data center?**
    * A. Reduced operational overhead and simplified management
    * B. Access to a wider range of AWS services not available on-premises
    * C. Lower upfront costs for hardware and software infrastructure
    * D. Increased security isolation from other AWS customer environments

**Topic 4: AWS Wavelength**

1. **What is the PRIMARY target audience for deploying applications on AWS Wavelength?**
    * A. Organizations with a global user base requiring low latency
    * B. Enterprises migrating large-scale databases to the AWS cloud
    * C. Businesses with strict data residency requirements in specific regions
    * D. Users who require high-performance compute resources for machine learning

2. **What is a UNIQUE benefit of deploying applications on AWS Wavelength compared to a standard AWS Region?**
    * A. Wavelength zones offer a wider selection of instance types
    * B. Applications on Wavelength zones leverage a dedicated network infrastructure
    * C. Wavelength zones provide direct access to mobile carrier networks
    * D. Wavelength zones are isolated from other AWS customer deployments


## AWS SAA Exam Simulator:

**Topic 1: AWS Regions**

1. **Which of the following statements is MOST accurate about AWS Regions?**
    * A. All regions have the same set of AWS services available.
    * B. Regions are completely isolated from each other.
    * C. Regions are geographically separated collections of data centers. **(CORRECT)**
    * D. Users can only launch resources in a single region.

**Topic 2: AWS Availability Zones**

1. **What is the PRIMARY benefit of deploying resources across multiple Availability Zones within a Region?**
    * A. To reduce the cost of running AWS services.
    * B. To improve the latency between resources.
    * C. To enhance the security posture of your application. 
    * D. To increase the fault tolerance of your application. **(CORRECT)**

**Topic 3: AWS Outposts**

1. **AWS Outposts are ideal for which of the following scenarios?**
    * A. Deploying latency-sensitive workloads close to on-premises infrastructure. **(CORRECT)**
    * B. Reducing the cost of data transfer between AWS and on-premises resources.
    * C. Offering AWS services to customers with limited internet connectivity.
    * D. Simplifying the management of hybrid cloud deployments.

**Topic 4: AWS Wavelength**

1. **What is the KEY advantage of deploying applications on AWS Wavelength?**
    * A. Reduced cost for running serverless functions.
    * B. Increased security isolation for sensitive workloads.
    * C. Ultra-low latency connectivity to mobile devices at the network edge. **(CORRECT)**
    * D. Simplified management of geographically dispersed resources.
