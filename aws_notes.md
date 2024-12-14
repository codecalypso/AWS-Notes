My AWS Cloud Practioner exam notes

Amazon Relational Database Service (RDS)
* Lower administrative burden.
* Resizable compute capacity.
* Read replicas facilitates offloading of database read activity 
* attaching security groups to an Amazon RDS instance Controls what IP address ranges can connect to your database instance
* server-based
* should be used for read/write of constantly changing data
* Cross-Region read replicas helps to create globally redundant databases


- Network Access Control Lists (NACLs)
- Security Groups. 
* help protect your EC2 instances from DDoS attacks
* Control network traffic in AWS
AWS EBS
* Deleting unnecessary snapshots may reduce costs
*  Changing the type of the volume may reduce costs

Amazon Direct Connect.
* allows companies to connect an Amazon VPC to an on-premises data center

Elastic Load Balancing
* Distributes incoming application traffic across one or more Amazon EC2 instances.
* Capable of handling constant changes in network traffic patterns.
* 


Amazon Elasticache 
* best for storing common database query results, which helps to alleviate database access load
* 
AWS VPN
* allows companies to connect an Amazon VPC to an on-premises data center

AWS Tagging
* makes it easier for you to categorize, manage and filter your resources
* Use tags to associate each instance with a particular department.

AWS Service Health Dashboard.
* provides the current status of all AWS Services in all AWS Regions

AWS Lambda
* scale automatically without your intervention
* executes code only when triggered by events
*  AWS Lambda runs code without provisioning or managing servers.
*  AWS Lambda provides resizable compute capacity in the cloud.
*  There is no charge when your AWS Lambda code is not running.
* Number of requests to your functions determine how you are charged 
* Compute time consumed determine how you are charged 
* Serverless 

Amazon EMR
* Enables you to analyze and process extremely large amounts of data in a timely manner.
* Enables you to easily run and scale Apache Spark, Hadoop,and other Big Data frameworks.
* Server-based

Amazon S3
* scale automatically without your intervention
* Versioning, encryption & permissions can be used to protect data at rest 
* Amazon S3.offers volume discounts based on usage
* automatically replicate data across Availability Zones
* enabling S3 Versioning protects data from accidental deletion
* . Virtually unlimited storage.
* can be used as a low-cost option for hosting static websites

Pillars of the AWS Well-Architected Framework
* Performance efficiency.
* Security.

Amazon Route 53
* can be used to register a new domain name?
* can be used to deploy SSL server certificates
* can perform health checks on Amazon EC2 instances
* DNS configuration and management.
* Manages global application traffic through a variety of routing types.
* used to route end users to the nearest AWS Region to reduce latency
* can be used across hybrid AWS Cloud architectures
* Global

Amazon Redshift
* allows you to build a data warehouse in the cloud

AWS over traditional on-premises solutions
* Using AWS allows companies to replace large capital expenditure with low variable costs.
* Using AWS, they can reduce time-to-market by focusing on business activities rather than on building and managing data centers.

AWS Trusted Advisor
* provides cost-optimization recommendations
* provide real-time auditing for compliance and vulnerabilities
* identifies security groups that allow unrestricted access to a user’s AWS resources
* Fault Tolerance & Performance.
* inspects AWS environments to find opportunities that can save money for users and also improve system performance?
* provides real-time guidance on AWS security best practices



AWS CloudTrail
* track resource changes using the API call history
* enables risk auditing by continuously monitoring and logging account activity, including user actions in the AWS Management Console and AWS SDKs
* 



AWS OpsWorks
* uses Puppet to automate how EC2 instances are configured


AWS CodeDeploy
* If an organization uses a hybrid cloud architecture to run their business. Enables them to deploy their applications to any AWS or on-premises server

AWS Budgets service
* track the reserved instances usage and set up alert notifications when their utilization drops below the threshold that they define.

AWS Management Console
* allows you to create new RDS instances


AWS CloudFormation
* allows you to create new RDS instances
* It automates the provisioning and updating of your infrastructure in a safe and controlled manner.
* It allows you to model your entire infrastructure in just a text file.
* can be uses to launch a new Amazon Relational Database Service (Amazon RDS) cluster
* provides the ability to manage infrastructure as code
* manage and automate application deployments on AWS


AWS Storage Gateway service
* It allows integration of on-premises IT environments with Cloud Storage.
* provides a hybrid storage service that enables on-premises applications to seamlessly use cloud storage

AWS Organizations
* Control access to AWS services.
* Consolidate billing across multiple AWS accounts
* allows a company with multiple AWS accounts to combine its usage to obtain volume discounts
* customer take advantage of volume discounts with minimal impact to the AWS resources?

AWS Cost Explorer
* can help a company visualize their AWS spending in the last few months
* Highly accurate cost forecasts for up to 12 months ahead

AWS TCO Calculator total cost of ownership
* perform a cost-benefit analysis of moving to the AWS Cloud
* use to compare the cost of on-premises environment resources to AWS
* Elastic computing will reduce the customer’s total cost of ownership 
* a company can reduce it TCO using AWS By minimizing large capital expenditures.
* 



AWS Cost & Usage Report
* provides them the most granular data about their AWS costs and usage

AWS-managed service
* Allows customers to deliver new solutions faster
* Lowers operational complexity

AWS Professional Services.
* assists customers in achieving their desired business outcomes

AWS Service Catalog
* It simplifies organizing and governing commonly deployed IT services.

Amazon Inspector.
* can help you perform security analysis and regulatory compliance auditing

DynamoDB
* Automatically scales to meet required throughput capacity
* Offers extremely low (single-digit millisecond) latency.
* automatically replicate data across Availability Zones
* Serverless 

AWS Config
* can help you perform security analysis and regulatory compliance auditing
* provide real-time auditing for compliance and vulnerabilities
* allows users to identify the changes made to a resource over time

AWS region
* An AWS Region is a geographical location with a collection of Availability Zones

AWS Application Discovery Service.
* helps with planning application migration to the AWS Cloud
* 
AWS Transit Gateway.
* simplify the connection management among the VPCs

Amazon VPC
* AWS Customers have complete control over their Amazon VPC virtual networking environment.
* Security Groups and subnets can be configured through the VPC dashboard
* 


Amazon EC2
* Eliminates the need to invest in hardware upfront.
* Can launch as many or as few virtual servers as needed.
* Improves Fault-Tolerance
* Can be scaled manually in a shorter period of time.
* Offers scalable computing.
* Per-second instance billing
* You should regularly patch the operating system and applications on your EC2 instances.
* The ability to pay upfront to get lower hourly costs.
* AWS allows customers to launch and terminate EC2 instances based on demand.
* allows you to install and run custom relational database software
* AWS customers are responsible for patching any database software running on Amazon EC2.
* can be used to manually launch instances based on resource requirements
* can be used to run a customer-managed relational database
* An object store.
* A durable storage system

Amazon EC2 Spot Instances
* For non-production applications.
* For fault-tolerant flexible applications.
* should be used company has a number of infrequent, interruptible jobs that are currently using On-Demand Instances
* can provide discounts of up to 90%
* pricing model adjusts based on supply and demand of EC2 instances


Reserved EC2 instance
* Reserved instances require at least a one-year pricing commitment.
* Reserved instances provide a significant discount compared to on-demand instances.
* three-year, All Upfront, Standard RI pricing provides the highest average savings compared to On-Demand pricing

On-Demand EC2 instances
* They remove the need to buy “safety net” capacity to handle periodic traffic spikes.
* You can increase or decrease your compute capacity depending on the demands of your application.

AWS Certification Manager (ACM)
* can be used to deploy SSL server certificates
* enables you to quickly purchase and deploy SSL/TLS certificates

Elastic Load Balancing (ELB)
* improve the reliability of your application by ensuring that only healthy targets receive traffic. 

AWS CAF
* framework created by AWS Professional Services that helps organizations design a road map to successful cloud adoption
* 
AWS Snowball 
* a petabyte-scale data transport service that uses secure devices to transfer large amounts of data into and out of the AWS Cloud.

AWS Artifact
* allows customers to download AWS SOC & PCI reports
* gives you access to all AWS auditor-issued reports and certifications
* compliance and certification reports be downloaded

AWS KMS.
* used to manage the keys used to encrypt customer data

Amazon CloudFront
* Increases application availability by caching at the edge.
* Delivers content to end users with low latency
* Number of Requests affects cost
* Traffic Distribution affects cost
* integrates with AWS Shield and AWS Web Application Firewall (AWS WAF) to protect against network and application layer DDoS attacks
* Global 

AWS offer to help protect your data in the Cloud
* Access control
* Data encryption
* AWS notify customers about security and privacy events pertaining to AWS services Using Security Bulletins.
* IAM Roles can best be used to grant temporary access to your AWS resources
* Require Multi-Factor Authentication (MFA) for all IAM User access to better secure account from unauthorized access.
* When granting permissions to applications running on Amazon EC2 instances Use temporary security credentials (IAM roles) instead of long-term access keys.
IAM
* An IAM user is uniquely associated with only one person, however a role is intended to be assumable by anyone who needs it.
* An IAM user has permanent credentials associated with it, however a role has temporary credentials associated with it.
* IAM user requires an access key ID and a secret access key to get long-lived programmatic access to AWS resources
* IAM root user requires an access key ID and a secret access key to get long-lived programmatic access to AWS resources
* Apply an IAM policy to an IAM group to apply common access controls to a large set of users
* 

AWS CloudHSM
* enables you to easily generate and use your own encryption keys in the AWS Cloud
* 


Amazon CloudWatch
* can be used to monitor CPU usage
* A metrics repository with customizable notification thresholds and channels.
* Real-time monitoring.
* Adjustable retention.

AWS pricing
* With the AWS pay-as-you-go pricing model, you don't have to pay any upfront fee
* You only pay for the individual services that you need with no long-term contracts.

AWS Billing and Cost Management.
* used to pay AWS bills, and monitor usage and budget costs


AWS Management Console
* can an AWS customer use to launch a new Amazon Relational Database Service (Amazon RDS) cluster

Amazon Macie.
* automatically recognizes and classifies sensitive data or intellectual property on AWS
* 
Amazon EFS.
* used for read/write of constantly changing data
* provides a simple and scalable shared file storage solution for use with Linux-based AWS and on-premises servers
* 

AWS Business Support plan
* 24/7 assistance by way of live chat or a telephone call.
* An unlimited number of cases and contacts.
* Provides Access to the full set of Trusted Advisor checks.
* Provides AWS Support API


customer's responsibility under the AWS shared responsibility model
* Patching Amazon EC2 instances
* Encrypting data on the client-side
* Configuring Network Access Control Lists (ACL)
* Ensuring that application data is encrypted at rest
* Ensuring that users have received security training in the use of AWS services
* Managing the VPC network access control lists.
* Encrypting data in transit and at rest.
* Configuring the operating system, network, and firewall
* Firewall management
* Patching of operating systems

Penetration testing on AWS
* Request and wait for approval from AWS support, and then conduct testing
responsibility of AWS
* Securing the Amazon EC2 hypervisor
* Physical and environmental controls
* Edge location management
* Updating the firmware on the underlying EC2 hosts.
* Managing the network infrastructure
* Physically destroying storage media at end of life
* Physical security of global infrastructure

Shared control between a customer and AWS
* Patch management
* configuration management


asset management on AWS easier than asset management in a physical data center AWS performs infrastructure discovery scans on the customer's behalf

There are six design principles for operational excellence in the cloud:
* Perform operations as code
* Annotate documentation
* Make frequent, small, reversible changes
* Refine operations procedures frequently
* Anticipate failure
* Learn from all operational failures
