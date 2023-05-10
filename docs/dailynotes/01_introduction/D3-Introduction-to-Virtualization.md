# Introduction to Virtualization, VPS and AWS Lightsail

## Day 3 Checklist

- [ ] Understand the concept of Virtualization
- [ ] How virtualization enables cloud computing
- [ ] What is a Virtual Private Server (VPS) ?
- [ ] How VPS were part of web hosting solutions.
- [ ] Introduction to AWS Lightsail


## Virtualization

Virtualization is a technology that enables the creation of multiple virtual versions of hardware and software resources, such as servers, operating systems, and storage devices, on a single physical machine. It allows users to run multiple operating systems and applications on a single physical machine, without having to purchase additional hardware or software resources.

## How Virtualization Works

Virtualization works by using a software layer, called a hypervisor, to manage the allocation of physical resources to virtual machines. The hypervisor acts as a mediator between the virtual machines and the physical resources, allocating resources such as CPU, memory, and storage to each virtual machine as needed. Each virtual machine operates as if it were a separate physical machine, with its own operating system, applications, and network connectivity.


## Types of virtualization

### Server Virtualization

Server virtualization is the most common type of virtualization, and involves partitioning a physical server into multiple virtual servers. Each virtual server operates as if it were a separate physical server, with its own operating system, applications, and network connectivity. Server virtualization can help organizations reduce hardware costs, improve resource utilization, and increase flexibility.

### Desktop Virtualization

Desktop virtualization involves creating virtual desktops on a server, which can be accessed by end-users from their devices. Desktop virtualization can help organizations simplify desktop management, increase security, and reduce costs, by allowing users to access virtual desktops from any device, anywhere.

### Storage Virtualization

Storage virtualization involves pooling multiple physical storage devices, such as hard drives and solid-state drives (SSDs), into a single virtual storage device. This virtual storage device can then be partitioned and allocated to different virtual machines or applications as needed. Storage virtualization can help organizations improve storage utilization, simplify storage management, and increase flexibility.

### Network Virtualization

Network virtualization involves creating multiple virtual networks on a physical network infrastructure. Each virtual network operates as if it were a separate physical network, with its own network address space, routing tables, and access control policies. Network virtualization can help organizations improve network utilization, simplify network management, and increase flexibility.

## Hypervisor types

There are two types of hypervisors:  

| Type 1 Hypervisor  | Type 2 Hypervisor  |
|-------------------|-------------------|
| Runs directly on the physical hardware  | Runs on top of an existing operating system  |
| Provides direct access to physical hardware resources  | Uses the host operating system to access hardware resources  |
| Typically used in server virtualization scenarios  | Typically used in desktop virtualization scenarios  |
| Offers higher performance and better security than Type 2 hypervisors  | Offers lower performance and security than Type 1 hypervisors  |
| Examples include VMware ESXi, Microsoft Hyper-V, and Citrix XenServer | Examples include Oracle VirtualBox, VMware Workstation, and Parallels Desktop |


## Cloud computing and virtualization

Cloud computing relies heavily on virtualization to provide users with scalable and cost-effective computing resources. By leveraging virtualization, cloud providers can provide users with flexible and dynamic computing environments that can be easily scaled up or down to meet changing business requirements.


Some of the relevant AWS services which work using the Virtualization technology includes

- Elastic Compute Cloud (EC2): EC2 is a web service that provides resizable compute capacity in the cloud. EC2 uses virtualization to provide users with a scalable and cost-effective way to run applications on a virtual server. Users can choose from a variety of virtual machine instances with different CPU, memory, storage, and networking capacities, and can launch, stop, and terminate instances as needed.

- Lambda: AWS Lambda is a serverless computing service that allows users to run code without provisioning or managing servers. Lambda uses virtualization to provide users with a scalable and cost-effective way to run code in the cloud. Users simply upload their code to Lambda, and the service takes care of provisioning and scaling the necessary compute resources to run the code.

- Elastic Block Store (EBS): EBS is a high-performance block storage service that allows users to store persistent data for use with Amazon EC2 instances. EBS uses virtualization to provide users with a scalable and highly available way to store data in the cloud. Users can choose from a variety of EBS volume types with different performance characteristics, and can attach and detach volumes from EC2 instances as needed.

- Virtual Private Cloud (VPC): VPC is a virtual network service that allows users to provision a logically isolated section of the AWS Cloud. VPC uses virtualization to provide users with a secure and flexible way to launch AWS resources into a virtual network that they define. Users can configure the network topology, create subnets, and control inbound and outbound traffic to and from their AWS resources.


## Virtual Private Server (VPS)

A Virtual Private Server (VPS) is a virtual machine that is hosted on a physical server, but operates as if it were a separate physical machine. VPS hosting is a popular hosting option for individuals and businesses that require more control and flexibility than shared hosting, but don't want the expense and complexity of dedicated hosting.

A VPS hosting provider typically uses virtualization technology to partition a physical server into multiple virtual machines, each with its own operating system, applications, and resources. Users can typically customize the configuration of their VPS, including CPU, RAM, storage, and bandwidth, and can install any software or applications they require.

Examples

- Amazon Web Services (AWS) Elastic Compute Cloud (EC2)
- DigitalOcean
- Linode
- Vultr
- Google Cloud Platform (GCP) Compute Engine


## AWS Lightsail

AWS Lightsail is a simplified, easy-to-use cloud computing solution offered by Amazon Web Services (AWS). It provides users with a pre-configured virtual private server (VPS), storage, and networking capabilities, as well as a range of other features, all at an affordable price point.

## Features

AWS Lightsail offers a range of features to help users easily deploy and manage their applications and websites, including:

- Pre-configured virtual private server (VPS) instances with a range of operating systems and applications, such as WordPress, Drupal, and Joomla.
- Integrated storage, including solid-state drives (SSD) and block storage.
- Networking capabilities, including static IP addresses, DNS management, and a firewall.
- Monitoring and alerting, including performance metrics and notifications.
- Automated backups and snapshots for easy recovery in case of data loss.

## Benefits

AWS Lightsail offers several benefits to users, including:

- Ease of use: With pre-configured instances and an easy-to-use management console, AWS Lightsail makes it easy for users to deploy and manage their applications and websites.
- Affordability: AWS Lightsail is an affordable cloud computing solution, with pricing starting at just a few dollars per month.
- Scalability: AWS Lightsail instances can be easily scaled up or down to meet changing business requirements.
- Security: AWS Lightsail provides a range of security features, including a firewall and automated backups, to help users protect their data and applications.
- Integration with other AWS services: AWS Lightsail can be easily integrated with other AWS services, such as Amazon S3 and Amazon RDS.


## Reference Links

1. "What is Virtualization?" VMware, Inc. https://www.vmware.com/topics/glossary/content/virtualization
2. "Virtualization: A beginner's guide," IBM. https://www.ibm.com/topics/virtualization
3. "Virtualization," Microsoft. https://docs.microsoft.com/en-us/virtualization/
