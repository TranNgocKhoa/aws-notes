# aws-notes
**Amazon Redshift** is a fully managed data warehouse service that allows you to run complex analytic queries against petabytes of structured data using standard SQL and your existing Business Intelligence (BI) tools.

**Amazon Aurora** is a MySQL and PostgreSQL-compatible relational database.

**Amazon Route 53, Amazon CloudFront, Elastic Load Balancing, and AWS WAF** to control and absorb traffic, and deflect unwanted requests. These services integrate with **AWS Shield**, a managed DDoS protection service that provides always-on detection and automatic inline mitigations to safeguard web applications running on AWS.

**Amazon Cognito** allows you to add user sign-up, sign-in, and access control to your web and mobile apps quickly and easily.

**AWS KMS** provides a highly available key storage, management, and auditing solution for you to encrypt data within your own applications and control the encryption of stored data across AWS services. 
 AWS Config is used to monitor and audit changes in AWS resources and allow you to automate the evaluation of recorded configurations of a specific resource against desired configurations.

**AWS Config** is a service that enables you to monitor, assess, and audit all changes made to your AWS **resources**.

**AWS CloudTrail** is a service that enables governance, compliance, operational auditing, and risk auditing of your AWS account. With CloudTrail, you can log, continuously monitor, and retain **account activity related to actions** across your AWS infrastructure. CloudTrail provides event history of your AWS account activity, including actions taken through the AWS Management Console, AWS SDKs, command line tools, and other AWS services. This event history simplifies security analysis, resource change tracking, and troubleshooting.
AWS CloudTrail records user API activity on your account and allows you to access information about this activity. You get full details about API actions, such as identity of the caller, the time of the API call, the request parameters, and the response elements returned by the AWS service.

**Amazon SES** refers to the Amazon Simple Email service.

**Amazon EMR** is used to run and scale Apache Spark, Hadoop, Presto, and other Big Data Frameworks.E 

**AWS CloudFormation** allows you to use programming languages or a simple text file to model and provision, in an automated and secure manner, all the resources needed for your applications across all regions and accounts. You create a template that describes all the AWS resources that you want (like Amazon EC2 instances or Amazon RDS DB instances), and AWS CloudFormation takes care of provisioning and configuring those resources for you. You don't need to individually create and configure AWS resources and figure out what's dependent on what; AWS CloudFormation handles all that for you.

**Spot instances** provide a discount (up to 90%) off the On-Demand price. The Spot price is determined by long-term trends in supply and demand for EC2 spare capacity. If the Spot price exceeds the maximum price you specify for a given instance or if capacity is no longer available, your instance will automatically be interrupted.

**Spot Instances** are a cost-effective choice if you can be flexible about when your applications run and if you don't mind if your applications get interrupted. For example, Spot Instances are well-suited for data analysis, batch jobs, background processing, and optional tasks.

**Dedicated Hosts** provide additional control over your instances and visibility into Host level resources and tooling that allows you to manage software that consumes licenses on a per-core or per-socket basis, such as Windows Server and SQL Server. This is why most BYOL scenarios are supported through the use of Dedicated Hosts, while only certain scenarios are supported by Dedicated Instances.

**Dedicated Instances** are Amazon EC2 instances that run in a virtual private cloud (VPC) on hardware that's dedicated to a single customer. Dedicated Instances that belong to different AWS accounts are physically isolated at the hardware level. In addition, Dedicated Instances that belong to AWS accounts that are linked to a single payer account are also physically isolated at the hardware level. However, Dedicated Instances may share hardware with other instances from the same AWS account that are not Dedicated Instances.

**AWS CodeDeploy** is a deployment service that automates application deployments to Amazon EC2 instances, on-premises instances, serverless Lambda functions, or Amazon ECS services.

**AWS Transit Gateway** is a network transit hub that simplifies how customers interconnect all of their VPCs, across thousands of AWS accounts and into their on-premises networks. Customers can easily and quickly connect into a single centrally-managed gateway, and rapidly growing the size of their network. Transit Gateway acts as a hub that controls how traffic is routed among all the connected networks which act like spokes. This hub and spoke model significantly simplifies management and reduces operational costs because each network only has to connect to the Transit Gateway and not to every other network. Any new VPC is simply connected to the Transit Gateway and is then automatically available to every other network that is connected to the Transit Gateway. This ease of connectivity makes it easy to scale networks as business grow.

**To enable HTTPS connections to your website or application in AWS**, you need an SSL/TLS server certificate. You can use a server certificate provided by **AWS Certificate Manager (ACM)** or one that you obtained from an external provider. You can use ACM or IAM to store and deploy server certificates. Use IAM as a certificate manager only when you must support HTTPS connections in a region that is not supported by ACM. **IAM supports deploying server certificates in all regions, but you must obtain your certificate from an external provider for use with AWS**. Amazon Route 53 is used to register domain names or use your own domain name to route your end users to Internet applications. Route 53 is not responsible for creating SSL certifications.


===
**Shared Controls** are controls which apply to both the infrastructure layer and customer layers, but in completely separate contexts or perspectives. In a shared control, AWS provides the requirements for the infrastructure and the customer must provide their own control implementation within their use of AWS services.

Examples include:

**Patch Management**  – AWS is responsible for patching the underlying hosts and fixing flaws within the infrastructure, but customers are responsible for patching their guest OS and applications.

**Configuration Management** – AWS maintains the configuration of its infrastructure devices, but a customer is responsible for configuring their own guest operating systems, databases, and applications.

** Awareness & Training - AWS trains AWS employees, but a customer must train their own employees.

===

**AWS Snowball** is a petabyte-scale data transport solution that uses secure appliances to transfer large amounts of data into and out of the AWS cloud. Using Snowball addresses common challenges with large-scale data transfers, including high network costs, long transfer times, and security concerns. AWS Customers use Snowball to migrate analytics data, genomics data, video libraries, image repositories, and backups. Transferring data with Snowball is simple, fast, secure, and can cost as little as one-fifth the cost of using high-speed internet.

Additionally, With AWS Snowball, you can access the compute power of the AWS Cloud locally and cost-effectively in places where connecting to the internet might not be an option. AWS Snowball is a perfect choice if you need to run computing in rugged, austere, mobile, or disconnected (or intermittently connected) environments.

With AWS Snowball, you have the choice of two devices, **Snowball Edge** **Compute Optimized** with more computing capabilities, suited for higher performance workloads, or **Snowball Edge** **Storage Optimized** with more storage, which is suited for large-scale data migrations and capacity-oriented workloads.

Snowball Edge Storage Optimized is the optimal choice if you need to securely and quickly transfer dozens of terabytes to petabytes of data to AWS. It is also a good fit for running general purpose analysis such as IoT data aggregation and transformation.

Snowball Edge Compute Optimized is the optimal choice if you need powerful compute and high-speed storage for data processing. Examples include high-resolution video processing, advanced IoT data analytics, and real-time optimization of machine learning models.

**AWS Snowmobile** is an Exabyte-scale data transfer service used to move extremely large amounts of data to AWS. You can transfer up to 100 Petabytes (PB) per Snowmobile, a 45-foot long ruggedized shipping container, pulled by a semi-trailer truck. Snowmobile makes it easy to move massive volumes of data to the cloud, including video libraries, image repositories, or even a complete data center migration. At exabyte scale, transferring data with Snowmobile is more secure, fast and cost effective.

**Amazon Athena** is an interactive query service that is mainly used to analyze data in Amazon S3 using standard SQL.

**The AWS Cost & Usage Report** is your one-stop shop for accessing the most detailed information available about your AWS costs and usage.The AWS Cost & Usage Report lists AWS usage for each service category used by an account and its IAM users in hourly or daily line items, as well as any tags that you have activated for cost allocation purposes.

**AWS Pricing Calculator** is a web service that you can use to estimate the cost for your AWS monthly bill based on your expected usage.

**AWS Systems Manager** provides a unified user interface so you can view operational data from multiple AWS services and allows you to automate operational tasks across your AWS resources.

**AWS Budgets** gives you the ability to set custom budgets that alert you when your costs or usage exceed (or are forecasted to exceed) your budgeted amount.

AWS Cost Explorer provides an easy-to-use interface that lets you visualize, understand, and manage your AWS costs and usage over time.

**AWS OpsWorks** is a configuration management service that provides managed instances of Chef and Puppet. Chef and Puppet are automation platforms that allow you to use code to automate the configurations of your servers.

**EMR** is used to process vast amounts of data easily and securely. Use cases include: big data,log analysis, web indexing, data transformations (ETL), machine learning, financial analysis, scientific simulation, and bioinformatics.

**Amazon CloudWatch** is a service that monitors AWS cloud resources and the applications you run on AWS. You can use Amazon CloudWatch to collect and track metrics, collect and monitor log files, set alarms, and automatically react to changes in your AWS resources. Amazon CloudWatch can monitor AWS resources such as Amazon EC2 instances, Amazon DynamoDB tables, and Amazon RDS DB instances, as well as custom metrics generated by your applications and services, and any log files your applications generate. You can use CloudWatch to detect anomalous behavior in your environments, take automated actions, troubleshoot issues, and discover insights to keep your applications running smoothly.

**AWS CloudTrail** is a service that enables governance, compliance, operational auditing, and risk auditing of your AWS account. With CloudTrail, you can log, continuously monitor, and retain account activity related to actions across your AWS infrastructure. CloudTrail provides event history of your AWS account activity, including actions taken through the AWS Management Console, AWS SDKs, command line tools, and other AWS services. This event history simplifies security analysis, resource change tracking, and troubleshooting.

**AWS Artifact** is a self-service audit artifact retrieval portal that provides customers with on-demand access to AWS’ compliance documentation and AWS agreements. You can use AWS Artifact Agreements to review, accept, and track the status of AWS agreements such as the Business Associate Addendum (BAA).

Additional information:

You can also use AWS Artifact Reports to download AWS security and compliance documents, such as AWS ISO certifications, Payment Card Industry (PCI), and System and Organization Control (SOC) reports.

Amazon Simple Email Service (Amazon SES) is a cloud-based email sending service designed to help digital marketers and application developers send marketing, notification, and transactional emails.

AWS X-Ray helps developers analyze and debug distributed applications in production or under development, such as those built using microservice architecture. With X-Ray, you can understand how your application and its underlying services are performing so you can identify and troubleshoot the root cause of performance issues and errors. X-Ray provides an end-to-end view of requests as they travel through your application, and shows a map of your application’s underlying components. You can use X-Ray to analyze both applications in development and in production, from simple three-tier applications to complex microservices applications consisting of thousands of services.

CloudTrail is a service that allows you to track all users’ actions that are taken in your AWS account.

The 5 Pillars of the AWS Well-Architected Framework:

1- Operational Excellence: The operational excellence pillar includes the ability to run and monitor systems to deliver business value and to continually improve supporting processes and procedures. Key topics include **automating changes**, responding to events, and defining standards to manage daily operations. 
 AWS CloudFormation can help you define your entire workload (applications, infrastructure) as code and update it with code. You can implement your operations procedures as code and automate their execution by triggering them in response to events. This will help you build a more consistent operating model and continually improve over time.

2- Security: The security pillar includes the ability to protect information, systems, and assets while delivering business value through risk assessments and mitigation strategies.

3- Reliability: The reliability pillar includes the ability of a system to recover from infrastructure or service disruptions, dynamically acquire computing resources to meet demand, and mitigate disruptions such as  misconfigurations or transient network issues.

4- Performance Efficiency: The performance efficiency pillar includes the ability to use computing resources efficiently to meet system requirements. Key topics include selecting the right resource types and sizes based on workload requirements, monitoring performance, and making informed decisions to maintain efficiency as business needs evolve.

5- Cost Optimization: The cost optimization pillar includes the ability to avoid or eliminate unneeded cost or sub-optimal resources.

Capital expenditures (CapEx) are a company's major, long-term expenses, while operating expenses (OpEx) are a company's day-to-day expenses. Examples of CapEx include physical assets such as buildings, equipment, and machinery. Examples of OpEx include employee salaries, rent, utilities, and property taxes.

AWS enables businesses to leverage high-end technologies and infrastructure needs with **low CapEx and low OpEx**. The AWS pay-as-you-go model reduces investments in large capital expenditures. In addition, you can reduce the operating expense (OpEx) costs involved with the management and maintenance of data. This frees up budget, allowing you to quickly act on innovative initiatives that can’t be easily pursued when managing physical data centers.

Pricing is per instance-hour consumed for each instance, from the time an instance is launched until it is terminated or stopped. Each partial instance-hour consumed will be billed per-second (minimum of 1 minute) for Linux, Windows, or Ubuntu Instances and as a full hour for all other instance types.

Amazon EC2 Auto Scaling monitors your applications and automatically adjusts capacity (up or down) to maintain steady, predictable performance at the lowest possible cost. When demand drops, Amazon EC2 Auto Scaling will automatically remove any excess capacity so you avoid overspending. When demand increases, Amazon EC2 Auto Scaling will automatically add capacity to maintain performance.

For Amazon S3 and Amazon EFS, you can create a lifecycle policy to automatically move infrequently accessed data to less expensive storage tiers. In order to reduce your Amazon S3 costs, you should create a lifecycle policy to automatically move old (or infrequently accessed) files to less expensive storage tiers such as Amazon Glacier, or to automatically delete them after a specified duration. Similarly, you can create an Amazon EFS lifecycle policy to automatically move less frequently accessed data to less expensive storage tiers such as Amazon EFS Standard-Infrequent Access (EFS Standard-IA) and Amazon EFS One Zone-Infrequent Access (EFS One Zone-IA). Amazon EFS Infrequent Access storage classes provide price/performance that is cost-optimized for files not accessed every day, with storage prices **up to 92% lower** compared to Amazon EFS Standard (EFS Standard) and Amazon EFS One Zone (EFS One Zone) storage classes respectively.

The traffic comes to the instances through HTTP. Network Load Balancer is best suited for load balancing of TCP and TLS traffic.

Elastic Load Balancing automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, IP addresses, and Lambda functions. Elastic Load Balancing offers four types of load balancers: 1- Application Load Balancer. 2- Network Load Balancer. 3- Gateway Load Balancer. 4- Classic Load Balancer. Application Load Balancer is best suited for load balancing of HTTP and HTTPS traffic. In our case, the application receives HTTP traffic. Hence, the Application Load Balancer is the correct answer here.

**AWS CloudHSM** is a cloud-based hardware security module (HSM) that enables you to easily generate and use your own encryption keys on the AWS Cloud.

Security groups allow you to control inbound and outbound traffic to your Amazon EC2 instances by specifically allowing communication only on the ports and protocols required for your applications. Access to any other port or protocol is automatically denied.

Network ACLs provide an additional layer of defense for your VPC by allowing you to create allow and deny rules that are processed in numeric order, much like a traditional firewall. This is useful for allowing or denying traffic at a subnet level, as opposed to security groups that filter traffic at an EC2 instance level. For example, if you have identified Internet IP addresses or ranges that are unwanted or potentially abusive, you can block them from reaching your application with a Network ACL deny rule.

Data protection refers to protecting data while in-transit (as it travels to and from Amazon S3) and at rest (while it is stored on disks in AWS data centers). The AWS customer is responsible for protecting their data **either at rest or in transit** for all services (including S3).

AWS WAF (Web Application Firewall) helps protect your web applications from common web exploits that could affect application availability, compromise security, or consume excessive resources. You can use AWS WAF to create custom rules that block common attack patterns, such as SQL injection or cross-site scripting, and rules that are designed for your specific application.

APN Consulting Partners are professional services firms that help customers design, architect, build, migrate, and manage their workloads and applications on AWS. Consulting Partners include System Integrators, Strategic Consultancies, Agencies, Managed Service Providers, and Value-Added Resellers. AWS supports the APN Consulting Partners by providing a wide range of resources and training to support their customers.

**Savings Plans** are a flexible pricing model that offers low prices on EC2, Lambda, and Fargate usage, in exchange for a commitment to a consistent amount of usage (measured in $/hour) for a 1 or 3 year term. When you sign up for Savings Plans, you will be charged the discounted Savings Plans price for your usage up to your commitment. For example, if you commit to $10 of compute usage an hour, you will get the Savings Plans prices on that usage up to $10 and any usage beyond the commitment will be charged On Demand rates.

**Amazon S3 Glacier** is a secure, durable, and extremely low-cost cloud storage service for data archiving and long-term backup. It is designed to deliver 99.999999999% durability, and provides comprehensive security and compliance capabilities that can help meet even the most stringent regulatory requirements.
Amazon S3 Glacier is more cost-effective than S3 One Zone-IA, but it does not provide immediate retrieval of data. With S3 Glacier, **the minimum retrieval period is 1-5 minutes.**

**Amazon S3 Glacier Deep Archive** is Amazon S3’s lowest-cost storage class that supports long-term retention and digital preservation for data that may be accessed once or twice in a year.

**S3 One Zone-IA** is for data that is **accessed less frequently**, but requires rapid access when needed. Unlike other S3 Storage Classes which store data in a minimum of three Availability Zones (AZs), S3 One Zone-IA stores data in a single AZ and costs 20% less than S3 Standard-IA.

 **S3 One Zone-IA** is a good choice for storing secondary backup copies of on-premises data or easily re-creatable data. You can also use it as cost-effective storage for data that is replicated from another AWS Region using S3 Cross-Region Replication.

 Although S3 One Zone-IA offers less availability than all other S3 storage classes but that is not an issue for the given scenario since it is just a secondary backup copy. S3 One Zone-IA is ideal for customers who want a lower-cost option for infrequently accessed data but do not require the availability and resilience of S3 Standard or S3 Standard-IA.

**Amazon S3 provides a number of security features for the protection of data at rest, which you can use or not depending on your threat profile:**

1- **Permissions**: Use bucket-level or object-level permissions alongside IAM policies to protect resources from unauthorized access and to prevent information disclosure, data integrity compromise or deletion.

2- **Versioning**: Amazon S3 supports object versions. Versioning is disabled by default. Enable versioning to store a new version for every modified or deleted object from which you can restore compromised objects if necessary.

3- **Replication**: Although Amazon S3 stores your data across multiple geographically diverse Availability Zones by default, compliance requirements might dictate that you store data at even greater distances. Cross-region replication (CRR) allows you to replicate data between distant AWS Regions to help satisfy these requirements. CRR enables automatic, asynchronous copying of objects across buckets in different AWS Regions.

4- **Encryption** – **server side**: Amazon S3 supports server-side encryption of user data. Server-side encryption is transparent to the end user. AWS generates a unique encryption key for each object, and then encrypts the object using AES-256.

5- **Encryption** – **client side**: With client-side encryption you create and manage your own encryption keys. Keys you create are not exported to AWS in clear text. Your applications encrypt data before submitting it to Amazon S3, and decrypt data after receiving it from Amazon S3. Data is stored in an encrypted form, with keys and algorithms only known to you.