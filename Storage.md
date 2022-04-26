# Storage
**AWS Storage Gateway** is a hybrid cloud storage service that gives you on-premises access to virtually unlimited cloud storage. All data transferred between the gateway and **AWS storage is encrypted using SSL** (for all three types of gateways - File, Volume and Tape Gateways).


**Elastic File Storage (EFS)** - Amazon Elastic File System (Amazon EFS) provides a simple, scalable, fully managed elastic NFS file system for use with AWS Cloud services and on-premises resources. 
Amazon EFS supports two forms of encryption for file systems, encryption of data in transit and encryption at rest. This is an optional feature and has to be enabled by user if needed.

**Elastic Block Storage (EBS)** - Amazon Elastic Block Store (EBS) is an easy to use, high-performance block storage service designed for use with Amazon Elastic Compute Cloud (EC2) instances for both throughput and transaction-intensive workloads at any scale. Encryption (at rest and during transit) is an optional feature for EBS and has to be enabled by the user.

**Amazon S3** - Amazon Simple Storage Service is storage for the Internet. To upload data into S3 you need to create an S3 bucket in one of the AWS Regions. Amazon S3 default encryption provides a way to set the default encryption behavior for an S3 bucket. 

Encryption for an S3 bucket is an additional feature and the user needs to enable it.				

**Amazon S3 Standard-Infrequent Access (S3 Standard-IA)**
		**S3 Standard-IA** is for data that is accessed less frequently, but requires rapid access when needed. S3 Standard-IA offers the high durability, high throughput, and low latency of S3 Standard, with a low per GB storage price and per GB retrieval fee. This combination of low cost and high performance make S3 Standard-IA ideal for long-term storage, backups, and as a data store for disaster recovery files.
		**Amazon S3 Standard** - The S3 Standard offers high durability, availability, and performance object storage for frequently accessed data. S3 standard would turn out to be costlier than S3 Standard-IA for the given use-case, so this option is not correct.
		**Amazon S3 Intelligent-Tiering (S3 Intelligent-Tiering)** - The S3 Intelligent-Tiering storage class is designed to optimize costs by automatically moving data to the most cost-effective access tier, without performance impact or operational overhead. It works by storing objects in two access tiers: one tier that is optimized for frequent access and another lower-cost tier that is optimized for infrequent access. S3 Intelligent-Tiering would turn out to be costlier than S3 Standard-IA for the given use-case, so this option is not correct.
		**Amazon S3 Glacier (S3 Glacier)** - Amazon S3 Glacier is a secure, durable, and extremely low-cost Amazon S3 cloud storage class for data archiving and long-term backup. It is designed to deliver 99.999999999% durability, and provide comprehensive security and compliance capabilities that can help meet even the most stringent regulatory requirements. S3 Glacier does not support rapid data retrieval, so this option is ruled out.
		
**Amazon S3 Glacier (S3 Glacier)**, is a storage service optimized for infrequently used data, or "cold data. Data at rest stored in **S3 Glacier is automatically server-side encrypted** using 256-bit Advanced Encryption Standard (AES-256) with keys maintained by AWS.

**Storage Gateway** - AWS Storage Gateway is a hybrid cloud storage service that connects your existing on-premises environments with the AWS Cloud. Customers use Storage Gateway to simplify storage management and reduce costs for key hybrid cloud storage use cases.

Just remember that **only S3 and DynamoDB support VPC Endpoint Gateway**. All other services that support VPC Endpoints use a VPC Endpoint Interface.

These include moving tape backups to the cloud, reducing on-premises storage with cloud-backed file shares, providing low latency access to data in AWS for on-premises applications, as well as various migration, archiving, processing, and disaster recovery use cases.

AWS Storage Gateway service provides three different types of gateways – **Tape Gateway, File Gateway, and Volume Gateway** – that seamlessly connect on-premises applications to cloud storage, caching data locally for low-latency access.

**EBS volume can be attached to a single instance in the same Availability Zone whereas EFS file system can be mounted on instances across multiple Availability Zones**

Amazon Elastic File System (Amazon EFS) provides a simple, scalable, fully managed elastic NFS file system for use with AWS Cloud services and on-premises resources. It is built to scale on-demand to petabytes without disrupting applications, growing and shrinking automatically as you add and remove files, eliminating the need to provision and manage capacity to accommodate growth.

The service is designed to be highly scalable, highly available, and highly durable. Amazon EFS file systems store data and metadata across multiple Availability Zones in an AWS Region. EFS file system can be mounted on instances across multiple Availability Zones.

Amazon Elastic Block Store (EBS) is an easy to use, high-performance block storage service designed for use with Amazon Elastic Compute Cloud (EC2) for both throughput and transaction-intensive workloads at any scale.

Designed for mission-critical systems, EBS volumes are replicated within an Availability Zone (AZ) and can easily scale to petabytes of data. You can attach an available EBS volume to one instance that is in the same Availability Zone as the volume.

