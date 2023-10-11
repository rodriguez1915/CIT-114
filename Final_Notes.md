# 1 Cloud Concept Overview

## Cloud Computing:
### -Is a on-demand service that uses all the power of physical compute via internet. 

     "Stop thinking of your infrastucture or hardware"
    - This quote describes the subject as a concept of mind or a different point of view.

## Similarities and Diferences 
-Elastic Loop Banding and Amazon VPC are almost the same or similar to switches, routers, and network pipelines. 

## Advantages 
### - Expenses, varibale expesnes is a part of the cloud that can be altered, changed, and at some point avoided.

-Speed increase, a faster access to your cloud computer.

-capacity, eliminate the guess work of the amount of storage your infrastructure will need.

-econimics of scale, lower the cost (varible) by using cloud services.


# 2 Cloud Economics and Billing

## Fundementals of AWS Pricing 
###  - there are three foundamentals when it come to AWS pricing they include; 

- Compute, as the processing power for your virtual computer.
- Storage which can very on the specific needs but is usally charge per GB.
- Data Transfer, which is also charged per GB BUT only for Outboud date transfers that vary for on a specific transfer rates. Inbound data transfers are not charged as long as it is between other AWS services within the same region.

### - Pay for what you use models serves the needs of start-up comapnies with limited budgets. While other companies with more expendtiaure can also save when they pay for a reserve amount and use it later on. 
  "Since 2006, AWS has lowered pricing 75 times (as of september 2019)"
  - PAY LESS AS AWS GROWS is what this quote entitles as a growing platfrom can help lowering costs with more businesses are added and using the services. 

# 3 AWS Global Infrastructure Overview

## AWS Global Infrastructure
- Is designed adn built to have the following capbilities:
- flexible
- reliable
- scalable
- secure

# 4 Cloud econmics

A calculation on how different the price can be on cloud computing to traditional systems.- Different businesses have to be able to shwo the benefits or the cons of using one or th other 
AWS pricing: "pay as you go" even pay in bulk (such as paying rent or nuying at costco or month to month)

allocated storea spaces are taken to account when pricing for cloud 

reseve pay for cloud space could also save allot of money if the agreed price was paid in advance.

pay less if you use more

### AWS MAIN COMPOENTS FOR PRICING: COMPUTE,STORAGE,&OUTBOUND DATA TRANSFER

# 5 Cloud Global Infrastructure

## Identify how regions affect cloud infrastructure
### -Supported web services, costs, latency, security and compliance, service level agreements (SLAs)
# *1 region contains mutiple availability points*
## Selecting best region 
### When it comes to selectign the best region for AWS there are some things that can come into consideration;
* Supported AWS services
* Cost
* Latency
* Security and compliance
* Service Level Agreements

# 6 Compute

## Compute Services overview
### AWS is a ssytem of on-demand services that include the folowing services such as:
* #### VM-Virtual machines
* #### IaaS-infrastructure as a service
* #### Paas-Platfrom as a service
### these services are serverless and container based

###
## Amazon EC2
### Amazon EC2 is what helps to give virtual machines the product as as service demand. IaaS infrastucture leave plenty of room for flexibilty as they can be build to fit the needs of specific roles. Fromt the chosign the operating system and ghe size of it's required resources adn capabilities for the servers. Virtual Machines have similar concepts to as phhysical systems. 

# 7 Storage
_______________________________________________________________
### Storage is another AWS core service category. Some broad categories of storage include: instance store (ephemeral storage), Amazon EBS, Amazon EFS, Amazon S3, and Amazon S3 Glacie

## Amazon ELastic Block Store (Amazon EBS)
### Persistent storageis any datastoragedevice that retains data after power to that device is shut off. It is also sometimes called non-volatile storage. 
### Each Amazon EBS volume is automatically replicated within its Availability Zone to protect you from component failure. It is designed for high availability and durability. Amazon EBS volumes provide the consistent and low-latency performance that is needed to run your workloads.
#### Amazon EBS enables you to createindividualstoragevolumesand attachthemto an Amazon EC2 instance:
##### •Amazon EBS offers block-level storage.
##### •Volumes are automatically replicated within its Availability Zone.
##### •It can be backed up automatically to Amazon S3 through snapshots.
##### •Uses include –
##### •Boot volumes and storage for Amazon Elastic Compute Cloud (Amazon EC2) instances
##### •Data storage with a file system
##### •Database hosts

# 8 DATABASES
________________________________________________
## Amazon Relational Database Service (Amazon RDS)
### Amazon RDS is a managed service that sets up and operates a relational database in the cloud. 
### To address the challenges of running an unmanaged, standalone relational database, AWS provides a service that sets up, operates, and scales the relational database without any ongoing administration. 

* Amazon RDS provides cost-efficient and resizable capacity, while automating time-consuming administrative tasks.
* Amazon RDS enables you to focus on your application, so you can give applications the performance, high availability, security, and compatibility that they need.
* With Amazon RDS, your primary focus is your data and optimizing your application

# 9 Cloud Architecture 
# _________________________________________________
## AWS Wel-Architected Framework 
### Architecture is the art and science of designing and building large structures. Large systems require architects to manage their size and complexity. 
#### Cloud architects:•
* Engage with decision makers to identify the business goal and the capabilities that need improvement.
* Ensure alignment between technology deliverables of a solution and the business goals.
* Work with delivery teams that are implementing the solution to ensure that the technology features are appropriate.

### Having well-architected systems greatly increases the likelihood of business success
#### The AWS Well-Architected Framework is a guide that is designed to help you build the most secure, high-performing, resilient, and efficient infrastructure possible for your cloud applications and workloads. It provides a set of foundational questions and best practices that can help you evaluate and implement your cloud architectures. AWS developed the Well-Architected Framework after reviewing thousands of customer architectures on AWS
* The AWS Well-Architected Framework provides a consistent approach to evaluate cloud architectures and guidance to help implement designs.
* The AWS Well-Architected Framework documents a set of design principles and best practices that enable you to understand if a specific architecture aligns well with cloud best practices.
* The AWS Well-Architected Framework is organized into six pillars.
* Each pillar includes its own set of design principles and best practices

# 10 Auto Scaling and Monitoring

## Elastic Load Balancing

### Elastic Load Balancing is an AWS service that distributes incoming application or network traffic across multiple targets—such as Amazon Elastic Compute Cloud (Amazon EC2) instances, containers, internet protocol (IP) addresses, and Lambda functions—in a single Availability Zone or across multiple Availability Zones. Elastic Load Balancing scales your load balancer as traffic to your application changes over time. It can automatically scale to most workloads.
* Elastic Load Balancing distributes incoming application or network traffic across multiple targets in one or more Availability Zones.
* Elastic Load Balancing supports three types of load balancers:
*     Application Load Balancer
*     Network Load Balancer
*     Classic Load Balancer
* ELB offers instance health checks, security, and monitoring

## Amazon CloudWatch
### Amazon CloudWatch is a monitoring and observability service that is built for DevOps engineers, developers, site reliability engineers (SRE), and IT managers. CloudWatch monitors your AWS resources (and the applicationsthat you run on AWS) in real time. You can use CloudWatch to collect and track metrics, which are variables that you can measure for your resources and applications
### You can create an alarm to monitor any Amazon CloudWatch metric in your account and use the alarm to automatically send a notification to an Amazon Simple Notification Service (Amazon SNS) topic or perform an Amazon EC2 Auto Scaling or Amazon EC2 action. For example, you can create alarms on the CPU utilization of an EC2 instance, Elastic Load Balancing request latency, Amazon DynamoDB table throughput, Amazon Simple Queue Service (Amazon SQS) queue length, or even the charges on your AWS bill. You can also create an alarm on custom metrics that are specific to your custom applications or infrastructure
### AmazonCloudwatch also gives you the following:
* Collect and track standard and custom metrics.
* Set alarms to automatically send notifications to SNS topics, or perform Amazon EC2 Auto Scaling or Amazon EC2 actions.
* Define rules that match changes in your AWS environment and route these events to targets for processing
