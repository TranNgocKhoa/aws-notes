**AWS Cost & Usage Report** - The AWS Cost & Usage Report contains the most comprehensive set of AWS cost and usage data available, including additional metadata about AWS services, pricing, credit, fees, taxes, discounts, cost categories, Reserved Instances, and Savings Plans. The AWS Cost & Usage Report (CUR) itemizes usage at the account or Organization level by product code, usage type and operation. These costs can be further organized by Cost Allocation tags and Cost Categories. The AWS Cost & Usage Report is available at an hourly, daily, or monthly level of granularity, as well as at the management or member account level. The AWS Cost & Usage Report cannot provide the estimate of the monthly AWS bill based on the list of AWS services.

**AWS Cost Explorer** - AWS Cost Explorer has an easy-to-use interface that lets you visualize, understand, and manage your AWS costs and usage over time. AWS Cost Explorer includes a default report that helps you visualize the costs and usage associated with your top five cost-accruing AWS services, and gives you a detailed breakdown of all services in the table view. The reports let you adjust the time range to view historical data going back up to twelve months to gain an understanding of your cost trends. AWS Cost Explorer cannot provide the estimate of the monthly AWS bill based on the list of AWS services.

**AWS Budgets** - AWS Budgets gives the ability to set custom budgets that alert you when your costs or usage exceed (or are forecasted to exceed) your budgeted amount. You can also use AWS Budgets to set reservation utilization or coverage targets and receive alerts when your utilization drops below the threshold you define. Budgets can be created at the monthly, quarterly, or yearly level, and you can customize the start and end dates. You can further refine your budget to track costs associated with multiple dimensions, such as AWS service, linked account, tag, and others. AWS Budgets cannot provide the estimate of the monthly AWS bill based on the list of AWS services.

**AWS Compute Optimizer** - AWS Compute Optimizer recommends optimal AWS resources for your workloads to reduce costs and improve performance by using machine learning to analyze historical utilization metrics. Over-provisioning resources can lead to unnecessary infrastructure costs, and under-provisioning resources can lead to poor application performance. Compute Optimizer helps you choose optimal configurations for three types of AWS resources: **Amazon EC2 instances, Amazon EBS volumes, and AWS Lambda functions,** based on your utilization data.
**Compute Optimizer recommends up to 3 options from 140+ EC2 instance types**, as well as a wide range of EBS volume and Lambda function configuration options, to right-size your workloads. Compute Optimizer also projects what the CPU utilization, memory utilization, and run time of your workload would have been on recommended AWS resource options. This helps you understand how your workload would have performed on the recommended options before implementing the recommendations.

**AWS Trusted Advisor** - AWS Trusted Advisor is an online tool that p**rovides you real-time guidance** to help you provision your resources **following AWS best practices** on cost optimization, security, fault tolerance, service limits, and performance improvement.

## The following AWS services support reservations to optimize costs:
**Amazon EC2 Reserved Instances:** You can use Amazon EC2 Reserved Instances to reserve capacity and receive a discount on your instance usage compared to running On-Demand instances.

**Amazon DynamoDB Reserved Capacity:** If you can predict your need for Amazon DynamoDB read-and-write throughput, Reserved Capacity offers significant savings over the normal price of DynamoDB provisioned throughput capacity.

**Amazon ElastiCache Reserved Nodes**: Amazon ElastiCache Reserved Nodes give you the option to make a low, one-time payment for each cache node you want to reserve and, in turn, receive a significant discount on the hourly charge for that node.

**Amazon RDS RIs**: Like Amazon EC2 RIs, Amazon RDS RIs can be purchased using No Upfront, Partial Upfront, or All Upfront terms. All Reserved Instance types are available for Aurora, MySQL, MariaDB, PostgreSQL, Oracle, and SQL Server database engines.

**Amazon Redshift Reserved Nodes**: If you intend to keep an Amazon Redshift cluster running continuously for a prolonged period, you should consider purchasing reserved-node offerings. These offerings provide significant savings over on-demand pricing, but they require you to reserve compute nodes and commit to paying for those nodes for either a 1- or 3-year duration.

**There are three fundamental drivers of cost with AWS: compute, storage, and outbound data transfer**. These characteristics vary somewhat, depending on the AWS product and pricing model you choose. **Outbound data to the internet** from all AWS regions is billed at region-specific, tiered data transfer rates. Inbound data transfer into all AWS regions from the internet is free.



