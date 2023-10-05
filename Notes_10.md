# Auto Scaling and Monitoring

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

## Amazon EC2 Auto Scaling 
### Amazon EC2 Auto Scaling provides several ways to adjust scaling to best meet the needs of your applications. You can add or remove    EC2 instances manually, on a schedule, in response to changing demand, or in combination with AWS Auto Scaling for predictive          scaling. Dynamic scaling and predictive scaling can be used together to scale faster

* Amazon EC2 Auto Scaling helps you maintain application availability,and enables you to automatically add or remove EC2 instances according to your workloads.
* An Auto Scaling group is a collection of EC2 instances.
* A launch configuration is an instance configuration template.
* You can implement dynamic scaling with Amazon EC2 Auto Scaling, Amazon CloudWatch, and Elastic Load Balancing
