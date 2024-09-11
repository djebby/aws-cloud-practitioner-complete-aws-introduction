
![Udemy Copletion Certificate](./UC-2ddabb3f-17bf-4f42-b12d-19cf57f396e0.jpg)

[Certificate](https://www.udemy.com/certificate/UC-2ddabb3f-17bf-4f42-b12d-19cf57f396e0/)



## AWS Certified Cloud Practitioner - Practice Exam

### :grey_question: Question 01 
  A company runs multiple microservice applications in a containerized environment. The company wants to deeply analyze application performance and cross-application communication problems.
  Which services should be used? (Select TWO.)

### Answer 01
  Amazon Simple Notification Service (SNS). :x:
  AWS X-Ray :heavy_check_mark:
  AWS CloudTrail. :x:
  Amazon CloudWatch :heavy_check_mark:
  Amazon Simple Queue Service (SQS). :x:

### Overall explanation
  :heavy_check_mark: Correct - Amazon CloudWatch
  CloudWatch is a service that can be used to collect and analyze various cloud resource and application metrics and logs. It also integrates with X-Ray to analyze cross-resource / cross-application traffic flow and communication. With help of CloudWatch, users can analyze and chart various performance metrics and explore application logs.

  :heavy_check_mark: Correct - X-Ray
  X-Ray is a service that can be used to collect cross-workload traffic metrics and information. This service allows users to understand how requests travel through their applications. It integrates with CloudWatch where X-Ray data can be analyzed in greater detail.

  :x: Incorrect - AWS CloudTrail
  CloudTrail is a service for identifying and analyzing AWS API calls and account actions. It's not a service for analyzing application performance or communication.

  :x: Incorrect - SQS
  SQS is a service that could be used to implement cross-application communication but it's not a service that would be used to analyze this communication in-depth.

  :x: Incorrect - SNS
  Just like SQS, SNS can be used to implement cross-application communication but it's not a service that would be used to analyze this communication in-depth.


### :grey_question: Question 02
  A company must migrate data from its on-premises infrastructure to the AWS cloud. The data transfer must be conducted offline without a direct network connection.
  Which AWS service can the company use?

### Answer 02
  AWS DataSync. :x:
  AWS Storage Gateway. :x:
  AWS Snowball. :heavy_check_mark:
  AWS Direct Connect. :x:

### Overall explanation
  :heavy_check_mark: Correct - AWS Snowball
  AWS Snowball is a physical device that's sent to AWS customers. This device can be connected to the local network and infrastructure to save any data that should be migrated to the cloud on it. Once sent back to AWS, data is transferred into the AWS cloud. This is therefore the perfect solution for use-cases like the one described in the question.

  :x: Incorrect - AWS DataSync
  DataSync is a data migration service that can be used to synchronize (copy) data from on-premises to the AWS cloud. However, it's not an offline service - it uses a network connection instead.

  :x: Incorrect - AWS Storage Gateway
  Storage Gateway is a service that could be used to build a hybrid (local + cloud) environment. It makes accessing cloud data (e.g., stored in S3) from local infrastructure easy. It can also be used to copy data into the cloud but it does use a network connection for that.

  :x: Incorrect - AWS Direct Connect
  Direct Connect is not a data transfer service or feature. Instead, it's a network connectivity option (an alternative to the public internet). With Direct Connect you use a dedicated network connection. It's still a network connection though, and therefore not suitable for this use-case.


### :grey_question: Question 03
  A company has a big group of users and needs to restrict access to its AWS resources.
  What is the SIMPLEST way to achieve this?

### Answer 03
  Add users to IAM User groups and apply IAM policies to IAM User groups. :heavy_check_mark:
  Attach IAM policies to every individual IAM user. :x:
  Attach IAM roles to grant access to all the users. :x:
  Apply the same IAM policies to all IAM users. :x:

### Overall explanation
  :heavy_check_mark: Correct - Add users to IAM User groups and apply IAM policies to IAM User groups
  By using IAM user groups, common access permissions don't have to be added to all users individually.

  :x: Incorrect - Attach IAM policies to every individual IAM user
  This would work but would require more effort than if IAM user groups were used. With groups, users only need to be assigned to their fitting groups and group permissions will be assumed automatically (as long as a user is part of a group).

  :x: Incorrect - Attach IAM roles to grant access to all the users
  IAM roles can't be attached (they can only temporarily be assumed).

  :x: Incorrect - Apply the same IAM policies to all IAM users
  As mentioned above, this requires more effort than if groups were used. In addition, you typically don't want all users to have the same permissions.


### :grey_question: Question 04
  Thanks to which cloud computing benefit can AWS customers benefit from lower pay-as-you-go prices?

### Answer 04
  Agility. :x:
  Economies of Scale. :heavy_check_mark:
  Pay-as-you pricing. :x:
  Trading fixed for variable expense. :x:

### Overall explanation
  :heavy_check_mark: Correct - Economies of Scale
  This option is the correct choice because AWS is able to achieve significant discounts and price reductions thanks to their scale. By achieving significant economies of scale, AWS is able to offer low cloud resource prices to their customers.

  :x: Incorrect - Agility
  This option is incorrect because Agility is only about being able to use AWS services (almost) instantly. It's not related to low prices being offered.

  :x: Incorrect - Pay-as-you-go pricing
  This option is incorrect because "Pay-as-you-go pricing" means that you only pay for the resources you are using. This can of course lead to a low monthly bill or lower costs than with on-premises infrastructure, but this concept is not related to the absolute per-unit prices charged by AWS.

  :x: Incorrect - Trading fixed for variable expense
  This concept is also about being able to (potentially) pay less in the AWS cloud than in a local, self-owned data center. But this concept is also not related to the absolute per-unit prices charged by AWS.


### :grey_question: Question 05
  How can AWS customers benefit from using Amazon RDS MySQL database instances instead of self-managed EC2-based MySQL instances? (Select TWO.)

### Answer 05
  Setting up a MySQL database instance requires less technical knowledge when using Amazon RDS. :heavy_check_mark:
  Amazon EC2 instances can be started and stopped at any time. :x:
  Customers have more fine-grained configuration options when using Amazon RDS. :x:
  Users are only billed when EC2 instances are running. :x:
  When using Amazon RDS, customers don't need to manage the underlying operating system. :heavy_check_mark:

### Overall explanation
  :heavy_check_mark: Correct - When using Amazon RDS, customers don't need to manage the underlying operating system.
  This can be a major advantage of using RDS over self-managed database instances (e.g., running on EC2). RDS is a managed service and therefore, AWS takes care of many crucial things like operating system management, database software installation etc.

  :heavy_check_mark: Correct - Setting up a MySQL database instance requires less technical knowledge when using Amazon RDS.
  Since RDS is a managed service and AWS takes care of many "under the hood" things, getting started with RDS (and launching a database instance) is typically easier than doing it manually via an EC2 instance.

  :x: Incorrect - Customers have more fine-grained configuration options when using Amazon RDS.
  Indeed, customers would have more fine-grained configuration options when using self-managed database instances on EC2. In that case, users would be able to control all details. When using RDS, customers have less configuration options, not more.

  :x: Incorrect - Amazon EC2 instances can be started and stopped at any time.
  Whilst this is correct, the same is true for RDS database instances. Hence it's not an advantage or benefit of either solution.

  :x: Incorrect - Users are only billed when EC2 instances are running.
  This is also correct, but the same is true for RDS database instances.


### :grey_question: Question 06
  A customer needs to encrypt data on-premises before uploading it to Amazon S3. Which encryption option should be used?

### Answer 06
  Server-side encryption with client-managed keys via CloudHSM. :x:
  Server-side encryption with AWS KMS managed keys. :x:
  Client-side encryption. :heavy_check_mark:
  In-transit encryption via AWS Certificate Manager (ACM). :x:

### Overall explanation
  :heavy_check_mark: Correct - Client-side encryption
  If data must be encrypted BEFORE it is uploaded, it must already be encrypted on the client-side. Both in-transit and server-side encryption happens too late.

  :x: Incorrect - Server-side encryption with KMS managed keys
  Server-side encryption happens too late - it does not satisfy the requirement of encrypting data BEFORE uploading it. No matter if KMS or any other key service is used.

  :x: Incorrect - Server-side encryption via CloudHSM
  Server-side encryption happens too late - it does not satisfy the requirement of encrypting data BEFORE uploading it. No matter if CloudHSM or any other key service is used.

  :x: Incorrect - In-transit encryption via ACM
  Whilst in-transit encryption makes sense, it's too late if data should be encrypted even BEFORE it's uploaded.


### :grey_question: Question 07
  Which service can AWS users use to receive cost-related alerts?

### Answer 07
  AWS Pricing Calculator. :x:
  AWS Cost and Usage Reports. :x:
  AWS Cost Explorer. :x:
  AWS Budgets. :heavy_check_mark:

### Overall explanation
  :heavy_check_mark: Correct - AWS Budgets
  AWS Budgets is a service that can be used to set cost budgets and alerts. Alerts can be configured to send an email notification once spending reaches a defined threshold.

  :x: Incorrect - AWS Cost Explorer
  Cost Explorer is a service that can be used to analyze and understand costs. It's not a service that notifies users or controls any budgets.

  :x: Incorrect - AWS Cost and Usage Reports
  Cost and Usage Reports is a service that produces fine-grained cost data that's stored in CSV files. This data can be analyzed with various tools (e.g., QuickSight). It's not a service that monitor any budgets.

  :x: Incorrect - AWS Pricing Calculator
  Pricing Calculator can be used to calculate the estimated cost of some service usage. It's not a budgeting tool.

### :grey_question: Question 08
  A user wants to determine whether their cloud infrastructure and applications follow common cloud best practices.
  Which service can be used to manually review the state of your cloud applications and workloads?

### Answer 08
  Amazon CloudWatch. :x:
  AWS CloudTrail. :x:
  AWS Well-Architected Tool. :heavy_check_mark:
  AWS Trusted Advisor. :x:

### Overall explanation
  :heavy_check_mark: Correct - AWS Well-Architected Tool
  This is a service that can be used to manually review your cloud infrastructure and applications against the Well-Architected Framework recommendations and best practices. Users can go through a set of questions to identify improvement opportunities.

  :x: Incorrect - AWS CloudTrail
  This is a service that can be used to track account API calls and user actions. It does not help with manually reviewing cloud infrastructure or applications.

  :x: Incorrect - AWS Trusted Advisor
  AWS Trusted Advisor is a service that helps with identifying best practice violations and improvement opportunities. It performs its checks automatically though - it's not a tool for manually reviewing.

  :x: Incorrect - Amazon CloudWatch
  Amazon CloudWatch is a service that's used to collect and analyze service metrics and logs. It's very useful for gaining application and workload insights but it's not a service for evaluating best practice conformance.


### :grey_question: Question 09
  Where can users perform detailed cost analyses?

### Answer 09
  AWS Cost Explorer. :heavy_check_mark:
  Amazon CloudWatch. :x:
  AWS Budgets. :x:
  AWS Pricing Calculator. :x:

### Overall explanation
  :heavy_check_mark: Correct - AWS Cost Explorer
  Cost Explorer is a service that allows users to perform detailed cost analyses. You can filter and group costs by Region, account, tags and many other fields. This service helps understand current and (potential) future costs.

  :x: Incorrect - AWS Budgets
  Budgets is a service that helps with managing spending budgets and taking action once a budget is (close to being) exceeded. For example, you can register an email that should be notified once a budget is exceeded. This is not a service for analysing costs though.

  :x: Incorrect - Amazon CloudWatch
  Amazon CloudWatch is a service that can be used to collect and analyze cloud resource and application metrics and logs. It's not a cost analysis service.

  :x: Incorrect - AWS Pricing Calculator
  Pricing Calculator can be used to calculate the estimated cost of some service usage. It's not a tool for exploring and understanding incurred cost.


### :grey_question: Question 10
  Which AWS services can be used to loosely couple multiple microservice applications? (Select TWO.)

### Answer 10
  Amazon CloudFront. :x:
  Amazon Simple Email Service (SES). :x:
  Amazon Simple Queue Service (SQS). :heavy_check_mark:
  Amazon Simple Notification Service (SNS). :heavy_check_mark:
  Amazon Kinesis. :x:

### Overall explanation
  :heavy_check_mark: Correct - Amazon SQS
  Amazon SQS can be used to send messages asynchronously from application A to application B. The two applications are therefore decoupled / loosely coupled: they run separately but may communicate with each other.

  :heavy_check_mark: Correct - Amazon SNS
  Just like SQS, SNS can be used to help applications communicate with each other. Unlike SQS, SNS is about synchronous communication. Nonetheless, it helps with decoupling / loosely coupling applications.

  :x: Incorrect - Amazon CloudFront
  Amazon CloudFront can be used to configure and use AWS' Edge Location network and cache and deliver content to users. It does not help with loose application coupling as it's not a service for connecting applications.

  :x: Incorrect - Amazon Kinesis
  Amazon Kinesis is a service for processing and handling streaming data (high frequency data ingestion). It's not a service that focuses on connecting applications.

  :x: Incorrect - Amazon SES
  Even though it sounds similar to SQS or SNS, SES is not about connecting applications. Instead, it is a service for sending transactional or bulk emails to end users (e.g., to customers of your online shop).


### :grey_question: Question 11
  Amazon Simple Storage Service (Amazon S3) is a service that provides object-level storage. Which of the following statements about Amazon S3 is true? (Select TWO.)

### Answer 11
  S3 is best for temporary data that is not kept long-term. :x:
  S3 can be used to store and query structured, relational data. :x:
  S3 can be used to create a data lake for performing big data analytics. :heavy_check_mark:
  S3 can be used to create a file system that's accessed by multiple applications. :x:
  S3 can be used to host a static website. :heavy_check_mark:

### Overall explanation
  :heavy_check_mark: Correct - Used as a data lake
  S3 can indeed be used to create data lake buckets. Data lakes are file storages that contain data files from various sources, with different formats and structures.

  :heavy_check_mark: Correct - Static Website Hosting
  S3 can be used as a static website hosting service. This feature can be enabled for every S3 bucket (the bucket and its content must be public though). Websites that require server-side code execution can't be hosted via S3.

  :x: Incorrect - Store relational, structured data
  S3 is not a database service - it's not a service that can be used to store structured or relational data. Instead, you store files (which don't need to have a similar structure or format).

  :x: Incorrect - Best for temporary data
  S3 is ideal for all kinds of data and files. You can store short term data as well as long term data. Different storage classes also help you reduce costs (based on file access patterns).

  :x: Incorrect - Create a file system
  S3 is not a file system service. You don't create any file systems with it, instead files are simply dumped into a bucket.


### :grey_question: Question 12
  Which AWS service can analyze raw data stored in S3 buckets via SQL queries?

### Answer 12
  AWS Storage Gatway. :x:
  Amazon Kinesis. :x:
  Amazon Athena. :heavy_check_mark:
  Amazon RDS. :x:

### Overall explanation
  :heavy_check_mark: Correct - Athena
  Athena is a serverless service that can be used to run SQL queries on data (files) stored in S3 buckets. Athena therefore enables users to run SQL queries on data in S3 (e.g., in a data lake) without moving that data into some relational database first.

  :x: Incorrect - Amazon Kinesis
  Kinesis is a streaming data service that helps with ingesting (and analyzing or forwarding) high-frequency streaming data. It does not provide any capabilities for running SQL queries on files stored in S3.

  :x: Incorrect - AWS Storage Gateway
  Storage Gateway is a service that can be used to extend a S3 bucket to a local file system / local network. It can be used to move files into the cloud but it's not a service that can be used for running SQL queries on S3 buckets.

  :x: Incorrect - Amazon RDS
  RDS (Relational Database Service) is a service that can be used to create relational database instances (e.g., MySQL instances). Data stored in such databases would be queries via SQL but RDS does not support querying data in S3 buckets.


### :grey_question: Question 13
  An application needs to connect to a RDS database instance. Which service should be used to manage the database connection credentials?

### Answer 13
  AWS AppConfig. :x:
  AWS Secrets Manager. :heavy_check_mark:
  AWS Key Management Store (KMS). :x:
  AWS SSM Parameter Store. :x:

### Overall explanation
  :heavy_check_mark: Correct - AWS Secrets Manager
  Secrets Manager is a service that securely stores and provides sensitive values like database credentials. Application code can access stored secrets via the AWS SDK.

  :x: Incorrect - AWS SSM Parameter Store
  Whilst Parameter Store can be used to store and manage application code values, the values are not stored securely. They can be viewed by everyone. Hence this service should only be used for values that may be publicly exposed, not for sensitive values.

  :x: Incorrect - AWS AppConfig
  AppConfig is a service that can be used to manage application code values (and automatically push value updates to applications). But like Parameter Store, it does not protect the values - hence the service should not be used for sensitive data.

  :x: Incorrect - AWS KMS
  AWS KMS is used for data encryption (e.g., user-generated files). It's not a service for managing sensitive application values.


### :grey_question: Question 14
  A colleague needs to evaluate the status of running EC2 instances. How should this access be granted? (Select TWO.)

### Answer 14
  Share the root user credentials with the colleague. :x:
  Assign a full-access EC2 policy. :x:
  Assign a read-only EC2 access policy. :heavy_check_mark:
  Create an IAM role for the colleague. :x:
  Create an IAM user for the colleague. :heavy_check_mark:

### Overall explanation
  :heavy_check_mark: Correct - Create an IAM user
  You should not share root user credentials. Therefore, it's correct to create IAM users for people that must connect to an AWS account. Of course that IAM user should also be protected with a safe password and MFA.

  :heavy_check_mark: Correct - Assign a read-only policy
  Since the user must only evaluate EC2 resources (and not create any), a read-only policy is all that's needed. According to the principle of least privilege, you should not grant more access rights or permissions than needed.

  :x: Incorrect - Create an IAM role
  Whilst users can indeed temporarily assume roles, that would not help the colleague gain access to the account. Typically, roles are therefore used to assign them to other services / service resources.

  :x: Incorrect - Share the root user credentials
  These credentials should never be shared with anyone!

  :x: Incorrect - Assign a full-access EC2 policy
  Whilst this would allow the colleague to perform their work, it violates the principle of least privilege. You should not grant more permissions than needed. Since the colleague only needs to evaluate (i.e., inspect) EC2 resources, read-only permissions are sufficient.


### :grey_question: Question 15
  A company needs to execute code whenever a new image is uploaded to a S3 bucket. Which service can be used with the least operational overhead?

### Answer 15
  AWS EC2. :x:
  AWS Lambda. :heavy_check_mark:
  Amazon Elastic Container Service (ECS). :x:
  Amazon Kinesis. :x:

### Overall explanation
  :heavy_check_mark: Correct - AWS Lambda
  AWS Lambda is AWS' serverless compute service. With it, you can execute code based on events without managing any underlying infrastructure or (virtual) servers. You just need to upload the code, define some base settings (e.g., timeout time) and the events that should trigger code execution.

  :x: Incorrect - AWS EC2
  Of course, AWS EC2 could be used to execute code based on events. You could trigger an application running on an EC2 instance via EventBridge for example. Or by sending an HTTP request to an exposed HTTP (REST) API. But all these solutions come with extra work. Provisioning and configuring an EC2 instance is more work than creating an AWS Lambda function. The same is true for writing an application that also needs to contain the event-listening code (instead of just the code that should be executed upon the event occurrence). Hence AWS EC2 is a suboptimal choice in this case.

  :x: Incorrect - Amazon ECS
  Just as with EC2, Amazon ECS could be used as a solution. It's a service that helps with running containerized workloads. But you need to go through more configuration steps and create a more elaborate environment than with AWS Lambda. Hence it's a suboptiomal solution.

  :x: Incorrect - Amazon Kinesis
  Amazon Kinesis is not a compute service. It's not a service you could use to execute code.


### :grey_question: Question 16
  A company needs to set up a data warehouse in the AWS cloud. Which AWS service should it use?

### Answer 16
  Amazon Redshift. :heavy_check_mark:
  Amazon DynamoDB. :x:
  Amazon Aurora. :x:
  Amazon Relational Database Service (RDS). :x:

### Overall explanation
  :heavy_check_mark: Correct - Amazon Redshift
  Redshift is Amazon's data warehouse solution. It's a database that's optimized for storing non-transactional, structured or semi-structured data. It's therefore the default data warehouse service that should be considered.

  :x: Incorrect - RDS
  RDS is a managed database service for structured and relational data. It's a service that's typically used for running databases used by applications or workloads to store transactional data. It's not optimized for data warehouse tasks and hence not an ideal choice for this use-case.

  :x: Incorrect - DynamoDB
  DynamoDB is a managed, key-value NoSQL database service. You can create tables that can store data of any format as long as all entries have the same key name. DynamoDB is a highly scalable and high-performance database service that's ideal for unstructured data.
  It's not a good fit for data warehousing tasks.

  :x: Incorrect - Amazon Aurora
  Aurora is Amazon's own database engine - it's essentially an alternative to MySQL, PostgreSQL etc. (and it offers MySQL + PostgreSQL compatibility). It's configured and used via the RDS service and it's a database engine that focuses on structured, relational data. Therefore, the same arguments as for RDS apply.


### :grey_question: Question 17
  Which service could be used to automatically resolve the failure of an EC2 instance?

### Answer 17
  AWS Lambda. :x:
  AWS Auto Scaling. :heavy_check_mark:
  AWS Simple Queue Service (SQS). :x:
  Amazon Elastic Block Store (EBS). :x:

### Overall explanation
  :heavy_check_mark: Correct - AWS Auto Scaling
  AWS Auto Scaling can be used to automatically launch new EC2 instances when existing instances terminate (or more instances are required due to an increase in demand). Therefore, AWS Auto Scaling can be a crucial building block when designing a failure-resistant cloud infrastructure.

  :x: Incorrect - Amazon EBS
  EBS is a block store service that can be used to add storage volumes ("hard drives") to EC2 instances. It does not help with handling EC2 instance failures.

  :x: Incorrect - AWS SQS
  SQS is a messaging service that can be used for cross-application communication. It's a great service for decoupling application components but it's not a service that can be used to handle EC2 instance failures.

  :x: Incorrect - AWS Lambda
  AWS Lambda is a serverless compute service that allows for running code without managing the underlying (virtual) server. It could (in some cases) be used to replace EC2 instances but it does not help with handling instance failure.


### :grey_question: Question 18
  Which of the following statement best describes the relationship between AWS Regions and Availability Zones?

### Answer 18
  Availability Zones contain one or more data centers. Regions contain multiple Availability Zones. :heavy_check_mark:
  A Region contains one or more data centers. An Availability Zone contains one or more Regions. :x:
  Availability Zones are separate physical geographical locations containing Regions. :x:
  Regions are clusters of data centers. Availability Zones are zones inside a data center. :x:

### Overall explanation
  :heavy_check_mark: Correct - AZs contain one or more data centers, Regions contain multiple AZs
  Every Availability Zone (AZ) includes at least one data center (sometimes more than one). AZs are phyiscally isolated from other AZs (e.g., separate power supply). Regions contain AZs - currently at least three AZs per Region.

  :x: Incorrect - Other Options
  All other options are wrong because AZs are not inside of data centers (instead, data centers are inside AZs) and AZs don't contain Regions (the opposite is the case).


### :grey_question: Question 19
  An organization with multiple AWS accounts wants to use consolidated billing across all its accounts. Which of the following are benefits of consolidated billing? (Select TWO.)

### Answer 19
  Use Service Control Policies (SCPs). :x:
  Receive a single bill for usage in multiple accounts. :heavy_check_mark:
  Calculate estimated service usage cost. :x:
  Combine resource usage across accounts to receive volume pricing discounts. :heavy_check_mark:
  Manage budgets on a per-account basis via AWS Budgets. :x:

### Overall explanation
  :heavy_check_mark: Correct - Combine usage for discounts
  When using AWS Organizations and Consolidated Billing, resource usage can be aggregated to benefit from various discounts. An organization could, for example, set up a Compute Savings Plan that applies to compute resources from various accounts. This helps reduce costs.

  :heavy_check_mark: Correct - Receive a single bill
  With Consolidated Billing, organizations receive a single bill for all included accounts instead of multiple bills. Especially in large companies this can significantly reduce administrative complexity.

  :x: Incorrect - Use SCPs
  SCPs are not a billing or cost management feature. Instead, these policies can be used to set maximum permission guardrails.

  :x: Incorrect - Calculate estimated service usage cost
  This could be done with the AWS Pricing Calculator but it's not a AWS Organizations or Consolidated Billing feature.


### :grey_question: Question 20
  A user runs multiple applications via different compute services. All applications must access a shared file system. Which AWS storage service can be used?

### Answer 20
  Amazon Elastic Block Store (EBS). :x:
  Amazon Elastic File System (EFS). :heavy_check_mark:
  Amazon Elastic Container Registry (ECR). :x:
  Amazon S3. :x:

### Overall explanation
  :heavy_check_mark: Correct - Amazon EFS
  EFS is a service that allows users to create file systems that can be used by multiple services and cloud resources simultaneously. It's perfect for scenarios like the one described in this question where multiple workloads or applications should access the same file system.

  :x: Incorrect - Amazon EBS
  The EBS service allows users to add block store volumes (virtual hard drives) to EC2 instances. Whilst EBS supports multi-attach (one volume can be attached to multiple instances), it's not the focus of this service. It's also not a file system that's created but a raw volume that must be formatted first. Last but not least, it's not usable with other compute services (other than EC2).

  :x: Incorrect - S3
  S3 is a file storage service that can be used with all compute services. It also supports simultaneous access. But it's not a file system service. Instead, files are organized in buckets and there is no file system structure or functionality.

  :x: Incorrect - ECR
  The ECR service has nothing to do with file storage or file systems. It's a registry for storing container images that can be used by ECS or other container services.


### :grey_question: Question 21
  Which AWS service can be used to run container clusters in the cloud serverlessly?

### Answer 21
  Amazon EC2. :x:
  AWS Lambda. :x:
  AWS Fargate. :heavy_check_mark:
  Amazon ECR. :x:

### Overall explanation
  :heavy_check_mark: Correct - Fargate
  Fargate is a serverless, pay-as-you-go compute engine that can be used via ECS or EKS to run container clusters in the cloud. It's a serverless alternative to using EC2 instances (via ECS).

  :x: Incorrect - Lambda
  Lambda is a serverless service and you can indeed provide code that should be executed (upon certain events) as a container image. But it's not a service that deals with container clusters or container cluster orchestration. Hence it's not a good choice if you want to operate a cluster of containers.

  :x: Incorrect - Amazon EC2
  EC2 instances can be used to install any software and run any workloads on them. You can also use EC2 in conjunction with ECS to run container clusters on top of EC2. Per definition, you don't get a serverless environment though. Because EC2 instances are virtual servers in the cloud.

  :x: Incorrect - Amazon ECR
  ECR (Elastic Container Registry) is a service that's used to store and distribute container images. It's not a service that's used to run containers or container clusters.


### :grey_question: Question 22
  An AWS user wants to deploy a web application to the AWS cloud. The application should also connect to a RDS database instance. Which AWS service can be used to simplify application environment creation and deployment?

### Answer 22
  AWS Systems Manager. :x:
  AWS Elastic Beanstalk. :heavy_check_mark:
  AWS CodeDeploy. :x:
  AWS Service Catalog. :x:

### Overall explanation
  :heavy_check_mark: Correct - Elastic Beanstalk
  Elastic Beanstalk is a service that uses other AWS services (like EC2 or RDS) under the hood. It simplifies the creation of (web) application environments in the cloud by offering a simplified user interface and offering various templates. This service can also be used to configure application deployments.

  :x: Incorrect - AWS CodeDeploy
  CodeDeploy indeed can be used to deploy application code to EC2 or other compute services. But it does not necessarily simplify this process - instead it offers various options for automating deployments and using different deployment strategies. It also does not create a cloud environment. It can't be used to create the environment required by the web application.

  :x: Incorrect - AWS Systems Manager
  Systems Manager is a service that can be used to manage (huge) server fleets (EC2 instances and on-premises infrastructure). It can also be used to orchestrate and manage applications. It's not a simplification service and it does not help with the creation of a web application environment.

  :x: Incorrect - AWS Service Catalog
  Service Catalog can be used to create pre-defined cloud resource solutions that can be used by other AWS account users. Service catalog can therefore reduce the complexity of creating cloud resources. Creating those pre-defined cloud solutions takes considerable initial effort and knowledge though. It's also not focused on or limited to (web) application solutions.


### :grey_question: Question 23
  Which AWS service can be used to store unstructured key-value data?

### Answer 23
  Amazon Aurora. :x:
  Amazon Redshift. :x:
  Amazon DynamoDB. :heavy_check_mark:
  Amazon Relational Database Service (RDS). :x:

### Overall explanation
  :heavy_check_mark: Correct - DynamoDB
  DynamoDB is a managed, key-value NoSQL database service. You can create tables that can store data of any format as long as all entries have the same key name. DynamoDB is a highly scalable and high-performance database service that's ideal for unstructured data.

  :x: Incorrect - RDS
  RDS is a managed database service for structured and relational data (i.e., NOT NoSQL). It's a great service but not a great choice for the kind of data described in this question.

  :x: Incorrect - Amazon Aurora
  Aurora is Amazon's own database engine - it's essentially an alternative to MySQL, PostgreSQL etc. (and it offers MySQL + PostgreSQL compatibility). It's configured and used via the RDS service and it's a database engine that focuses on structured, relational data. Hence it's not a good fit for the kind of data described in this question.

  :x: Incorrect - Amazon Redshift
  Redshift is Amazon's data warehouse solution. It's a database that's optimized for storing non-transactional, structured or semi-structured data.


### :grey_question: Question 24
  Which AWS service enables a company to create its own virtual cloud network within AWS?

### Answer 24
  AWS VPN. :x:
  Amazon Virtual Private Cloud (VPC). :heavy_check_mark:
  Amazon CloudFront. :x:
  Amazon Route 53. :x:

### Overall explanation
  :heavy_check_mark: Correct - VPC
  Amazon Virtual Private Cloud (VPC) is a service that allows users to create their own private network in the AWS cloud. This network can be split into subnets which are either private or public. Some services like EC2 then use VPCs and subnets to create cloud resources inside of that private cloud network (e.g., EC2 instances launched into private or public subnets).

  :x: Incorrect - Amazon Route 53
  Route 53 is AWS' DNS service. This service can be used to register and manage domains and domain routing records. You could, for example, forward incoming requests to cloud resources. It's a not a service that creates a cloud-internal private network though.

  :x: Incorrect - Amazon CloudFront
  CloudFront is a service that can be used to cache and deliver content to application users or website visitors. It's not a service for creating a cloud-internal network though.

  :x: Incorrect - AWS VPN
  AWS VPN is a service that allows users to establish a private network connection between their local infrastructure and the AWS cloud resources / AWS network. It's not a service for creating a cloud-internal network.


### :grey_question: Question 25
  Under the AWS shared responsibility model, which of the following are the user's duties and responsibilities? (Select TWO.)

### Answer 25
  Protecting the global infrastructure that runs AWS services. :x:
  Securing software installed on EC2 instances. :heavy_check_mark:
  Configuring security groups for Amazon EC2 instances. :heavy_check_mark:
  Patching AWS Lambda operating systems. :x:
  Maintaining physical server infrastructure. :x:

### Overall explanation
  :heavy_check_mark: Correct - Configuring security groups for Amazon EC2 instances
  Security groups are (software) firewalls for EC2 instances (and some other services). It's the user's responsibility to configure security groups such that they securely meet workload requirements.

  :heavy_check_mark: Correct - Securing software installed on EC2 instances
  Since users can install any software of their choice on EC2 instances, it's also the responsibilty of AWS cloud users to secure that software (e.g., keep it patched).

  :x: Incorrect - Maintaining physical server infrastructure
  AWS owns and operates the phyiscal infrastructure, therefore it's their responsibility to maintain it. Indeed, AWS customers have no access to the phyiscal infrastructure.

  :x: Incorrect - Protecting the global infrastructure that runs AWS services
  As mentioned, AWS owns and operates the infrastructure. Hence, AWS customers don't have to worry about infrastructure protection.

  :x: Incorrect - Patching AWS Lambda operating systems.
  AWS Lambda is a managed, serverless service. As a user, you don't have access to the underlying operating system, hence it's AWS' responsibility to keep that OS updated and patched.


### :grey_question: Question 26
  How could an AWS user achieve high application availability?

### Answer 26
  By paying for compute resources upfront instead of on-demand. :x:
  By using AZs instead of Regions. :x:
  By deploying an application into multiple Availability Zones or even Regions. :heavy_check_mark:
  By picking a Region close to the application users. :x:

### Overall explanation
  :heavy_check_mark: Correct - By deploying an application across multiple AZs or Regions
  By running the same application on top of the same service in multiple AZs or Regions (e.g., multiple EC2 instances, placed in different AZs or Regions) AWS users can improve the availability of the application. If one AZ or Region would be affected by a disaster (or anything like that), the application would continue to run in a different AZ or Region. It would therefore still be available to the application users (even if performance would suffer because of less compute resources being used).

  :x: Incorrect - By paying for compute resources upfront
  This can help you reduce costs but it does not make the application more available.

  :x: Incorrect - By picking a Region close to your application users
  This can improve the performance / latency experienced by the application users but it does not affect the application availability.

  :x: Incorrect - By using AZs instead of Regions
  AZs and Regions are not an "either-or" choice. Some services like EC2 use AZs as another layer inside of Regions. Hence you always have to pick both for such services (and the picked Region determines which AZs are available). For other services, AZs don't matter and you can only pick which Region you want to use.


### :grey_question: Question 27
  An AWS user is running Microsoft SQL Server on Amazon RDS DB instance. Which security tasks must be handled by the AWS customer? (Select TWO.)

### Answer 27
  Replicating data between a primary DB instance and a read replica. :x:
  Installing operating system patches for the RDS database instance. :x:
  Managing access permissions to allow or deny account users to manage Amazon RDS resources. :heavy_check_mark:
  Configuring encryption to secure stored database data and snapshots at rest. :heavy_check_mark:
  Operating the underlying physical infrastructure. :x:

### Overall explanation
  :heavy_check_mark: Correct - Managing access rights
  Under the shared responsibility model, every party (AWS and the customer) is responsible for securing the parts they influence. Since account access is managed by the AWS users, its the user's responsibility to manage access rights such that no unauthorized database configuration changes can be made.

  :heavy_check_mark: Correct - Configuring encryption
  RDS is a managed service, hence AWS takes care about database software setup and the underlying operating system. The AWS customer / user has various configuration options though. Encryption is one option that can be chosen by the user - hence it's the user's responsibility to take care about it.

  Incorrect - Installing operating system patches :x:
  Since AWS manages the underlying software and hardware, it's AWS' responsibility to patch the operating system.

  Incorrect - Replicating data :x:
  RDS is a managed service. If data replication is enabled by the AWS user, AWS will automatically perform all necessary steps.

  Incorrect - Operating the underlying infrastructure :x:
  AWS is responsible for operating the underlying infrastructure.


### :grey_question: Question 28
  Which AWS service can help you automatically detect malicious or suspicious account activities?

### Answer 28
  Amazon GuardDuty. :heavy_check_mark:
  Amazon Inspector. :x:
  Amazon Detective. :x:
  AWS CloudTrail. :x:

### Overall explanation
  :heavy_check_mark: Correct - Amazon GuardDuty
  Amazon GuardDuty is a managed service that automatically monitors your account for suspicious activities. It monitors both user and application actions as well as network traffic. Findings are surfaced so that you can inspect them and take appropriate action.

  :x: Incorrect - AWS CloudTrail
  AWS CloudTrail does allow you to analyze cloud resource usage and API calls. You could use this service to detect and analyze suspicious activities but it's not a service that offers any automatic monitoring or warnings.

  :x: Incorrect - Amazon Detective
  Amazon Detective is a service that can be used to analyze and explore security incidents. It's a great service for diving deeper into security issues or findings but it's not a service that would automatically surface suspicious account usage or activities.

  :x: Incorrect - Amazon Inspector
  Amazon Inspector is a service that alerts you of application or workload vulnerabilities. It may, for example, detect software security holes. It does not detect or surface suspicious account activities though.


### :grey_question: Question 29
  Which part of the AWS infrastructure helps with caching and delivering content with low latency?

### Answer 29
  Availability Zones. :x:
  Regions. :x:
  AWS Outposts. :x:
  Edge Locations. :heavy_check_mark:

### Overall explanation
  :heavy_check_mark: Correct - Edge Locations
  Edge Locations are "mini data centers" that contain infrastructure that's built for content caching and delivery. You can't select Edge Locations to run EC2 instances or create S3 buckets in them (or use other services in them). Instead, AWS operates Edge Locations to deliver content to users with very low latency. This is achieved by routing user requests to the closest Edge Location and hence avoiding long network roundtrips. You utilize Edge Locations via CloudFront or the Global Accelerator services.

  :x: Incorrect - AWS Outposts
  AWS Outposts is a service that allows you to add AWS infrastructure into you local data center / on-premises infrastructure. You can then run AWS services in your own data center. This can help reduce latency of workloads that must be connected to workloads running in your data center but it's not a general service for delivering content to users or reducing latency. It's also not about caching.

  :x: Incorrect - Regions
  Regions are a major element of the AWS infrastructure. AWS groups its data centers into Availability Zones which are in turn part of Regions. For many services, you have to select in which Region you want to use them. And whilst you could run an application in multiple Regions and therefore reduce latency for your customers or users, it's not the core idea behind Regions (it could add a lot of unnecessary complexity for this use-case). Indeed they also have no built-in caching functionality or focus.
  Instead, you often combine workloads placed in Regions or Availability Zones with Edge Locations (via CloudFront) to speed up content delivery.

  :x: Incorrect - Availability Zones
  See above - AZs are part of Regions and must be selected for some services (e.g., EC2 instances).


### :grey_question: Question 30
  How can the cloud concept of Elasticity best be described?

### Answer 30
  The ability to measure a workload's performance. :x:
  The ability to distribute a workload across multiple Regions. :x:
  The ability to acquire and release resources as needed. :heavy_check_mark:
  The ability to manage on-premises infrastructure dynamically. :x:

### Overall explanation
  :heavy_check_mark: Correct - The ability to acquire and release resources as needed
  When using AWS, Elasticity refers to the ability to add or remove cloud IT resources as needed. You can for example add more or less EC2 instances based on workload demand. Or you can increase the storage size of an EBS volume.

  :x: Incorrect - The ability to measure a workload's performance
  Whilst AWS offers services that help with measuring infrastructure performance (e.g., CPU utilization), this is not part of the Elasticity concept.

  :x: Incorrect - The ability to distribute a workload across multiple Regions
  Being able to distribute infrastructure and workloads across Regions can be crucial for achieving High Availability. It's not related to Elasticity though.

  :x: Incorrect - The ability to manage on-premises infrastructure dynamically
  In this context, Elasticity is a AWS cloud concept and not focused on on-premises infrastructure.


### :grey_question: Question 31
  Which AWS service can be used to configure and create automated code deployment workflows?

### Answer 31
  AWS CodePipeline. :heavy_check_mark:
  AWS CodeDeploy. :x:
  AWS Cloud9. :x:
  AWS CodeBuild. :x:

### Overall explanation
  :heavy_check_mark: Correct - AWS CodePipeline
  CodePipeline is a service that allows users to create and configure complete code deployment pipelines. Pipelines include a source stage (i.e., the place where the source code is stored), a build stage (e.g., using CodeBuild to test and compile the code) and a deployment stage (e.g., CodeDeploy to deploy the built code to EC2 instances). You can also add other stages (e.g., manual approval stages).

  :x: Incorrect - CodeDeploy
  CodeDeploy is a service that can be used inside a CodePipeline workflow. CodeDeploy itself just focuses on one task of the overall workflow: the code deployment (e.g., to an EC2 instance).

  :x: Incorrect - CodeBuild
  Just like CodeDeploy, CodeBuild just focuses on one part of the overall deployment workflow. With CodeBuild, you can test and build (e.g., compile) code.

  :x: Incorrect - Cloud9
  Cloud9 is AWS' web-based IDE (Integrated Development Environment). It's a web-based code development environment that runs on top of a (managed) EC2 instance.



### :grey_question: Question 32
  Which AWS services can be crucial to achieve Elasticity and Reliability for an application? (Select TWO.)

### Answer 32
  AWS Organizations. :x:
  AWS Auto Scaling. :heavy_check_mark:
  AWS CloudTrail. :x:
  AWS Elastic Load Balancer. :heavy_check_mark:
  Amazon Neptune. :x:

### Overall explanation
  :heavy_check_mark: Correct - AWS Auto Scaling
  With AWS Auto Scaling, AWS users can configure that a certain amount of EC2 instances is up and running at all times. If an instance would fail (e.g., because of a crash), the Auto Scaling service replaces the failing instance with a new one (=> Reliability). The number of instances can also scale dynamically based on metrics like CPU utilization. Being able to adjust the number of instances to meet demand helps with ensuring that the instances + the application / workload running on top of them are able to perform their intended tasks.

  :heavy_check_mark: Correct - Elastic Load Balancer
  Work must be distributed evenly across all available EC2 instances (which should perform the work). Elastic Load Balancers like Application Load Balancer (ALB) or Network Load Balancer (NLB) do exactly that: they distribute load across all registered EC2 instances. Combined with AWS Auto Scaling, this can ensure that a workload is performed reliably.

  :x: Incorrect - AWS CloudTrail
  AWS CloudTrail is a service that helps with analyzing API calls and understanding account activity. The service can be used to identify which identity performed which action. It does not directly help with implementing reliable solutions.

  :x: Incorrect - Amazon Neptune
  Amazon Neptune is a graph database. This kind of database is perfect for storing complex relationships but it does not directly help with achieving Reliability.

  :x: Incorrect - AWS Organizations
  AWS Organizations can be used / enabled to manage multi-account environments. It's not a feature or service that would directly contribute to achieving Reliability for a workload though.


### :grey_question: Question 33
  Which of the following services automatically inspects AWS environments to find cost reduction opportunities?

### Answer 33
  AWS Budgets. :x:
  AWS Cost Explorer. :x:
  AWS Trusted Advisor. :heavy_check_mark:
  Consolidated Billing. :x:

### Overall explanation
  :heavy_check_mark: Correct - AWS Trusted Advisor
  This is a service that automatically scans your cloud resources and recommends actions based on its findings. One area of recommendations is related to cost reduction opportunities.

  :x: Incorrect - AWS Cost Explorer
  This is a service that can be used to (deeply) analyze costs. It's great for understanding expenses but it's not performing any automatic checks or providing any recommendations.

  :x: Incorrect - AWS Budgets
  This service can be used to set budgets and receive alerts once budgets are (close to being) exceeded. It's not a service that performs any automatic checks or provides any recommendations.

  :x: Incorrect - Consolidated Billing
  Consolidated Billing is an AWS Organizations feature that can simplify cross-account cost and bill management. It does not perform any automatic checks or provide any recommendations though.


### :grey_question: Question 34
  Which AWS service can be used to set and evaluate account-wide cloud resource configurations?

### Answer 34
  AWS Config. :heavy_check_mark:
  AWS AppConfig. :x:
  AWS CloudTrail. :x:
  AWS Systems Manager (SSM). :x:

### Overall explanation
  :heavy_check_mark: Correct - AWS Config
  AWS Config is a service that can be used to define expected cloud resource configurations. If cloud resources are configured differently, this service detects deviations and helps users analyze and resolve configuration changes.

  :x: Incorrect - AWS CloudTrail
  This service can be used to analyze and identify cloud resource API calls (e.g., if an EC2 instance was started). It's not a service that can be used to enforce or evaluate any service or cloud resource configurations.

  :x: Incorrect - AWS AppConfig
  It sounds similar to AWS Config but it's a totally different service. AWS AppConfig is a service that can be used to set, control and distribute application configurations and values that should be used by application code. It could be used to enforce application behaviors but it does not help with managing service usage or cloud resource configurations.

  :x: Incorrect - AWS SSM
  Systems Manager is a service that simplifies the management of large server fleets or applications. It does not help with cloud resource configuration management.


### :grey_question: Question 35
  Which of the following is NOT a pillar of the Well-Architected Framework?

### Answer 35
  Reliability Pillar.
  Sustainability Pillar.
  Security Pillar.
  Scalability Pillar. :heavy_check_mark:

### Overall explanation
  :heavy_check_mark: Correct - Scalability Pillar
  This is the correct choice, because this pillar does not exist as part of the Well-Architected Framework. Whilst AWS helps with application and infrastructure scaling, this is not a pillar of the framework. Instead, the Reliability Pillar is also about scaling resources.

  :x: Incorrect - Reliability Pillar
  This is a pillar of the framework. The reliability pillar focuses on workloads performing their intended functions and how to recover quickly from failure to meet demands. Key topics include distributed system design, recovery planning, and adapting to changing requirements.

  :x: Incorrect - Security Pillar
  This is a pillar of the framework. The security pillar focuses on protecting information and systems. Key topics include confidentiality and integrity of data, managing user permissions, and establishing controls to detect security events.

  :x: Incorrect - Sustainability Pillar
  This is a pillar of the framework. The sustainability pillar focuses on minimizing the environmental impacts of running cloud workloads. Key topics include a shared responsibility model for sustainability, understanding impact, and maximizing utilization to minimize required resources and reduce downstream impacts.


### :grey_question: Question 36
  Data with an unknown access pattern is stored in a S3 bucket. Which S3 storage class should be picked to automatically reduce costs?

### Answer 36
  S3 Intelligent-Tiering :heavy_check_mark:
  S3 Standard-Infrequent Access (S3 Standard-IA). :x:
  S3 Glacier Instant Retrieval. :x:
  S3 Standard. :x:

### Overall explanation
  :heavy_check_mark: Correct - S3 Intelligent-Tiering
  S3 Intelligent-Tiering is a storage class where file access patterns get analyzed automatically. The object (file) is then automatically moved to a fitting storage class based on file access patterns. Whilst cost reductions are a bit lower than with manual storage class assignments, it's a great solution if access patterns are unknown or changing.

  :x: Incorrect - S3 Standard-Infrequent Access
  This storage class is perfect if data is not accessed frequently (but access is also not highly unlikely). If data access patterns are unknown, it's not a good choice as file retrieval fees may actually increase costs.

  :x: Incorrect - S3 Standard
  This is the default storage class. It's great if data is accessed frequently but if data access patterns are unknown, potential savings may stay unrealized.

  :x: Incorrect - S3 Glacier Instant Retrieval
  The Glacier storage classes are great for long-term file storage where file access is unlikely. If data access patterns are unknown, costs may actually be (way) higher than without using this storage class. Hence it's not a good choice.


### :grey_question: Question 37
  A company plans to migrate its applications and databases to the cloud. Which AWS service can be used for migrating its SQL databases?

### Answer 37
  Amazon Aurora. :x:
  AWS Database Migration Service (AWS DMS). :heavy_check_mark:
  AWS DataSync. :x:
  AWS Application Migration Service. :x:

### Overall explanation
  :heavy_check_mark: Correct - AWS DMS
  As the name suggests, this service helps with database migrations. It supports homo- (same engines) and heterogenous (different engines) migrations and can therefore greatly simplify database migrations. You can also combine it with the Schema Conversion Tool in case data schemas must be converted.

  :x: Incorrect - AWS DataSync
  This is a service that helps with data (file) migrations from on-premises to the cloud. It's not a service that can help with database migrations.

  :x: Incorrect - Amazon Aurora
  Aurora is a relational database engine developed by Amazon. It can be used as an alternative to MySQL etc. from inside RDS. It could therefore be the target of a migration but it's not a service that helps with the migration itself.

  :x: Incorrect - AWS Application Migration Service
  This service can help with migrating applications from local data centers (local servers) to cloud resources. This service replicates local applications and their execution environment to cloud resources without interrupting the local workloads. It's not focusing on database migrations though.


### :grey_question: Question 38
  A company uses a hybrid cloud strategy. The company's on-premises infrastructure is currently connected to the AWS cloud via the public internet. Which alternative connection options could the company evaluate? (Select TWO.)

### Answer 38
  AWS Direct Connect. :heavy_check_mark:
  Amazon Virtual Private Cloud (VPC). :x:
  Amazon CloudFront. :x:
  AWS VPN. :heavy_check_mark:
  Amazon Route 53. :x:

### Overall explanation
  :heavy_check_mark: Correct - AWS VPN
  AWS VPN is a service that allows users to establish a private network connection between their local infrastructure and the AWS cloud resources / AWS network. This service can be used by companies that follow a hybrid cloud strategy where local infrastructure should be (securely) connected to cloud infrastructure.

  :heavy_check_mark: Correct - AWS Direct Connect
  With Direct Connect, users get a dedicated connection between their local infrastructure and the AWS cloud / AWS network. This connection is totally isolated from the public internet and can therefore be used to securely connect to the cloud.

  :x: Incorrect - Amazon Virtual Private Cloud (VPC)
  The VPC service is used to create and manage a cloud-internal network (which holds other cloud resources, like EC2 instances). It's not a connection option for connecting local infrastructure to the cloud.

  :x: Incorrect - Amazon Route 53
  Route 53 is AWS' DNS service. This service can be used to register and manage domains and domain routing records. You could, for example, forward incoming requests to cloud resources. It's a service that forwards request that are received via the public internet - it's not an alternative to the internet.

  :x: Incorrect - Amazon CloudFront
  CloudFront is a service that can be used to cache and deliver content to application users or website visitors. It's a service that works with requests received via the public internet, it's not a connection alternative to the public internet.


### :grey_question: Question 39
  What are benefits of migrating compute workloads from on-premises infrastructure to the AWS cloud? (Select TWO.)

### Answer 39
  Compute and storage capacity provisioning at a fixed level to meet maximum demand. :x:
  Trading fixed expense for variable expense. :heavy_check_mark:
  Trading variable expense for fixed expense. :x:
  Managing the physical security of data centers. :x:
  Faster infrastructure provisioning. :heavy_check_mark:

### Overall explanation
  :heavy_check_mark: Correct - Trading fixed for variable expense
  When moving from on-premises infrastructure to cloud infrastructure, you only pay for the resources used (i.e., variable costs). You don't incur any fixed costs as you don't need to maintain or operate any infrastructure, infrastructure-related staff etc. Hence fixed expense is traded for variable expense.

  :heavy_check_mark: Correct - Faster infrastructure provisioning
  When using cloud computing, infrastructure provisioning is just a click away. You can easily start a new EC2 instance, add an extra storage volume or adjust a load balancer configuration. Hence infrastructure provisioning is extremely fast (almost instant).

  :x: Incorrect - Trading variable for fixed expense
  As explained above, the opposite is the case.

  :x: Incorrect - Compute and storage capacity provisioning at a fixed level
  This is a disadvantage of on-premises infrastructure: you can't easily add or remove hardware / servers. Hence you have to either overprovision (to ensure you always meet the demand) or underprovision (to reduce costs). Either way, it's not optimal because you're either paying too much or you're not able to meet all demand. Therefore, it's a benefit of migrating to the cloud, that you're able to get rid of this disadvantage.

  :x: Incorrect - Managing physical security of data centers
  With on-premises infrastructure, you are responsible for data center security (i.e., for protecting the actual buildings). When moving to the cloud, you no longer have this responsibility.


### :grey_question: Question 40
  Where can you find AWS recognized third-party security solution providers?

### Answer 40
  AWS Security Hub. :x:
  AWS Marketplace. :heavy_check_mark:
  AWS Trusted Advisor. :x:
  AWS Support. :x:

### Overall explanation
  :heavy_check_mark: Correct - AWS Marketplace
  AWS Marketplace is a digital catalog that includes thousands of software listings from independent software vendors. In order to sell on the marketplace, vendors must be registered and approved by AWS. The offered services and products include security software and products.

  :x: Incorrect - AWS Security Hub
  Security Hub is a central place for managing various security-related services (e.g., Amazon Inspector) across organization accounts (or inside a single account). It's not a service where you could buy third-party security software or solutions.

  :x: Incorrect - AWS Support
  The official AWS support can help with technical or account issues but it does not sell any third-party solution services or products.

  :x: Incorrect - AWS Trusted Advisor
  This service provides automatic checks and best practice recommendations. It's not a service where you could buy any third-party security solutions.


### :grey_question: Question 41
  Which approaches could be used to connect to a running EC2 instance and execute commands on it? (Select TWO.)

### Answer 41
  Multi-Factor Authentication (MFA). :x:
  EC2 Instance Connect. :heavy_check_mark:
  SSL-encrypted HTTP request. :x:
  SSH client and a key pair. :heavy_check_mark:
  Amazon API Gateway. :x:

### Overall explanation
  :heavy_check_mark: Correct - SSH client and key pair
  You can connect to a running EC2 instance via any SSH client, as long as you have a valid key pair. The key pair must be created / assigned during instance creation. You need the private key that is created in order to connect with a SSH client. Once connected, you can run any commands of your choice on the EC2 instance.

  :heavy_check_mark: Correct - EC2 Instance Connect
  You can also connect without a key pair by using EC2 Instance Connect. This service is accessible directly from inside the Management Console. You get a browser-based command line tool interface which allows you to run commands on the EC2 instance. No key pair is required for this approach.

  :x: Incorrect - API Gateway
  API Gateway is a serverless service for creating REST APIs. It's not a service that helps with connecting to EC2 instances.

  :x: Incorrect - MFA
  Multi-Factor Authentication is important for securing your AWS account. All account users should use MFA. But it's not a connection mechanism for connecting to EC2 instances.

  :x: Incorrect - SSL-encrypted HTTP requests
  You can send HTTP requests to EC2 instances (if the security group allows it and the instance runs an application that handles such requests) but you can't use these requests to establish a connection that would allow you to execute commands on the instance.


### :grey_question: Question 42
  Which AWS service can be used to deploy cloud resources via code templates ("Infrastructure as Code")?

### Answer 42
  AWS CodeDeploy. :x:
  AWS CloudTrail. :x:
  Amazon CloudWatch. :x:
  AWS CloudFormation. :heavy_check_mark:

### Overall explanation
  :heavy_check_mark: Correct - AWS CloudFormation
  AWS CloudFormation is a service that can be used to deploy (i.e., create) cloud resources based on templates. The templates specifiy which services should be used (and which configurations should be applied). Based on the templates, cloud resources (like EC2 instances or S3 buckets) are created.

  :x: Incorrect - Amazon CloudWatch
  Amazon CloudWatch is a service for collecting and analyzing resource metrics and logs. It's not a service that helps with cloud resource deployment or management.

  :x: Incorrect - AWS CodeDeploy
  CodeDeploy is a service that can be used to automate and manage deployment of application code. You could, for example, use CodeDeploy to update an application running on an EC2 instance. CodeDeploy is not used for managing the cloud resources (i.e., the EC2 instance itself) though.

  :x: Incorrect - AWS CloudTrail
  AWS CloudTrail is a service that can be used to monitor account API calls and user activity. It's not a service that's involved with resource management.


### :grey_question: Question 43
  Which AWS tools can be used to interact with cloud resources programmatically? (Select TWO.)

### Answer 43
  AWS Config. :x:
  AWS SDK. :heavy_check_mark:
  AWS AppSync. :x:
  AWS CLI. :heavy_check_mark:
  AWS Management Console. :x:

### Overall explanation
  :heavy_check_mark: Correct - AWS CLI
  The AWS CLI (Command Line Interface) is a tool that can be used to send commands to the AWS API servers (i.e., to the AWS cloud). The same thing happens behind the scenes when using the Management console. The CLI therefore offers a programmatic way of accessing AWS cloud resources (since no graphical user interface is involved).

  :heavy_check_mark: Correct - AWS SDK
  The AWS SDK (Software Development Kit) is a tool (or actually a collection of tools, since there are multiple SDKs) that offers programmatic access to AWS cloud resources. Different SDKs exist for different programming languages. With help of the AWS SDKs, you can write code (e.g., in Python) that sends commands to the AWS API (i.e., to the AWS cloud).

  :x: Incorrect - Management Console
  The Management Console is a graphical, web-based user interface that can be used for cloud resource interaction.

  :x: Incorrect - AWS Config
  AWS Config is a service that can be used to set, control and evaluate service and cloud resource configurations. It's not a service or tool that can be used to gain programmatic cloud access.

  :x: Incorrect - AppSync
  AppSync is a service that can be used for building serverless GraphQL APIs in the AWS cloud. It's not a service or tool that helps with programmatic cloud access.


### :grey_question: Question 44
  A company has an interruptible workload running on EC2 instances. The workload runs for two hours every day and its long-term hardware requirements can't be predicted. It is planned to continue running for the next year.
  Which EC2 instance pricing models should be considered to reduce costs? (Select TWO.)

### Answer 44
Reserved Instances. :x:
On-Demand Instances. :x:
Savings Plans. :heavy_check_mark:
Infrequent Access Class. :x:
Spot Instances. :heavy_check_mark:

### Overall explanation
  :heavy_check_mark: Correct - Spot Instances
  Since the workload is interruptible, Spot Instances can be a decent alternative to On-Demand instances. With Spot Instances, AWS customers can save money because these instances are offered at a (huge) discount. They may be reclaimed by AWS at any time (with a prior warning) but for interruptible workloads, that is no problem.

  :heavy_check_mark: Correct - Savings Plans
  With Savings Plans, users can commit to a certain amount of (compute) usage upfront for 1 or 3 years. Since the workload is planned to run for more than 1 year, Savings Plans could therefore help lower EC2 instance costs.

  :x: Incorrect - On-Demand Instances
  Whilst On-Demand Instances offer the higest amount of flexibility, they don't offer any discounts or cost savings. Hence this is not a great option for this workload.

  :x: Incorrect - Reserved Instances
  Reserved Instances also offer cost reductions by commiting to a certain amount of EC2 instance usage upfront (for 1 or 3 years). Unlike with Savings Plans, you have to choose an instance profile though, which limits flexibility and adds extra complexity. That's why for this workload, Savings Plans are more attractive.

  :x: Incorrect - Infrequent Access Class
  This is not an EC2 instance pricing model, it's instead related to the S3 service.


### :grey_question: Question 45
  Which extra measures should be taken to increase account security? (Select TWO.)

### Answer 45
  Use Multi-Factor Authentication (MFA) on IAM roles. :x:
  Enable Multi-Factor Authentication (MFA). :heavy_check_mark:
  Use the root user instead of IAM users. :x:
  Assign programmatic access keys to all IAM users. :x:
  Use IAM users instead of the root user. :heavy_check_mark:

### Overall explanation
  :heavy_check_mark: Correct - Enable MFA
  Multi-Factor Authentication (MFA) adds a second authentication layer. Knowing account or user credentials is no longer enough to log into an AWS account. This ensures that even if account credentials would get compromised, attackers don't gain access to your account.

  :heavy_check_mark: Correct - Use IAM users instead of the root user
  Whilst for some tasks root user access is required (e.g., for changing payment details), most tasks should be completed by IAM users. It is therefore a good practice to avoid root user account usage as much as possible and use IAM users instead.

  :x: Incorrect - Use the root user instead of IAM users
  See above - the opposite is the case.

  :x: Incorrect - Use Multi-Factor Authentication (MFA) on IAM roles
  Adding MFA is a good practice but you can't add it to roles since IAM roles are not identities that can log into an account. Instead, roles are typically assigned to cloud resources in order to (temporarily) gain permission to perform certain tasks (e.g., store a file on S3).

  :x: Incorrect - Assign programmatic access keys to all IAM users
  Only IAM users that need programmatic access should receive access keys. The principle of least privilege suggests that entities should only receive the permissions and access rights they absolutely need.


### :grey_question: Question 46
  Which pillar of the AWS Well-Architected Framework focuses on the ability of a workload to use computing resources efficiently to meet system requirements and maintain that efficiency as demand changes?

### Answer 46
  Performance Efficiency pillar. :heavy_check_mark:
  Security pillar. :x:
  Operational Excellence pillar. :x:
  Reliability pillar. :x:

### Overall explanation
  :heavy_check_mark: Correct - Performance Efficiency pillar
  This option is correct because this pillar focuses on using compute resources efficiently - even as circumstances change.
  More details: [Performance efficiency](https://docs.aws.amazon.com/wellarchitected/latest/performance-efficiency-pillar/performance-efficiency.html)

  :x: Incorrect - Reliability pillar
  This option is incorrect because this pillar focuses on workloads being able to perform their intended function in a reliable way (i.e., recover from failure, keep up with varying demand). It's not about using resources efficiently.

  :x: Incorrect - Operational Excellence pillar
  This option is incorrect because this pillar focuses on establishing and maintaining efficient processes (e.g., Infrastructure as Code) and monitoring workloads and service usage.

  :x: Incorrect - Security pillar
  This pillar focuses on protecting systems & data.


### :grey_question: Question 47
  Which AWS service helps defend against Distributed Denial-of-Service (DDoS) attacks?

### Answer 47
  AWS IAM. :x:
  AWS WAF. :x:
  AWS Network Firewall. :x:
  AWS Shield. :heavy_check_mark:

### Overall explanation
  :heavy_check_mark: Correct - AWS Shield
  AWS Shield is a managed DDoS protection service. It helps protect against various kinds of DDoS attacks and can be upgraded to Shield Advanced for extra protection against more kinds of DDoS attacks.

  :x: Incorrect - AWS WAF
  AWS WAF (Web Application Firewall) is a firewall service that can be used to block or deny traffic based on HTTP request content. It does not focus on preventing DDoS attacks.

  :x: Incorrect - AWS Network Firewall
  AWS Network Firewall is a managed firewall service that can be used to inspect and control VPC network traffic. It does not focus on DDoS protection.

  :x: Incorrect - AWS IAM
  AWS IAM is a service that helps manage account access rights and permissions. It is not involved in DDoS protection.


### :grey_question: Question 48
  When using cloud computing, customers can stop guessing capacity.
  How does cloud computing help cloud customers with IT resource capacity planning?

### Answer 48
  Access services on-demand to prevent excess or overhead capacity. :heavy_check_mark:
  Quickly deploy applications around the world. :x:
  More time to experiment and innovate. :x:
  Trade fixed expense for variable expense. :x:

### Overall explanation
  :heavy_check_mark: Correct - Access services on-demand
  By being able to quickly deploy / use more or less IT resources / services, customers can adjust service usage to meet demand. For example, more EC2 instances could be added to handle more website traffic (of course the web server must be started on all EC2 instances). This "Elasticity" and "Agility" enables AWS customers to "stop guessing capacity".

  :x: Incorrect - Quickly deploy applications around the world
  Whilst this is a great feature and advantage of the cloud, it does not help with capacity planning. Instead, it can help with application performance or latency experienced by application users. It can also help with application or workload availability.

  :x: Incorrect - More time to experiment
  This is another useful advantage but it does not help with capacity planning.

  :x: Incorrect - Trade fixed expense for variable expense
  This is a cloud computing advantage, but it is related to costs. It's not related to capacity planning.


### :grey_question: Question 49
  Which AWS service can be used to control VPC subnet traffic?

### Answer 49
  Amazon CloudFront. :x:
  AWS WAF. :x:
  Network Access Control Lists (NACLs). :heavy_check_mark:
  Security Groups. :x:

### Overall explanation
  :heavy_check_mark: Correct - NACLs
  Network Access Control Lists are inbound + outbound traffic rules that are associated with individual subnets. You can control which traffic should be allowed into a subnet and which traffic may leave a subnet. By default, all traffic is allowed.

  :x: Incorrect - Security Groups
  Security groups also help with traffic management. They are not applied on a subnet-level though. Instead, security groups are directly applied to network devices - they can, for example, be used to control traffic for an EC2 instance. The same security group can be added to multiple instances but it's still not a tool for managing traffic on subnet-level.

  :x: Incorrect - AWS WAF
  AWS WAF (Web Application Firewall) is a managed firewall service that can be used to control and filter traffic based on HTTP request content (e.g., based on the body of an incoming HTTP request). It can be used in conjunction with CloudFront, Application Load Balancer and various other services. It's not attached to VPC subnets though.

  :x: Incorrect - Amazon CloudFront
  Amazon CloudFront is a service for caching and delivering content to end users. It's not a firewall or traffic management service.


### :grey_question: Question 50
  A company is running an application on an Amazon EC2 instance. The EC2 instance has an EBS store volume attached to it for data storage. Company compliance standards require encryption of data at rest and in-transit.
  Which service can you use to meet this requirement?

### Answer 50
  AWS SSM Parameter Store. :x:
  AWS Key Management Service (KMS). :heavy_check_mark:
  Amazon S3. :x:
  AWS Secrets Manager. :x:

### Overall explanation
  :heavy_check_mark: Correct - KMS
  KMS (Key Management Store) is a service that manages encryption keys on your behalf. It's deeply integrated with other (data storage) services like S3 or EBS. AWS users can easily enable EBS volume encryption with help of KMS.

  :x: Incorrect - AWS SSM Parameter Store
  The Systems Manager Parameter Store is a service that helps with managing application values (i.e., values used in application code). It does not help with data encryption.

  :x: Incorrect - AWS Secrets Manager
  Just like Parameter Store, Secrets Manager helps with managing application code values. Unlike Parameter Store, Secrets Manager focuses on values that must not be exposed (i.e., that should be secret). Examples would be database connection credentials. It's not a service that helps with data encryption though.

  :x: Incorrect - Amazon S3
  Amazon S3 is a data storage service. It could (in some scenarios) be used as an alternative to EBS. S3 also has built-in encryption support but that does not help with encrypting EBS volumes.


### :grey_question: Question 51
  Which AWS infrastructure component allows users to run workloads close to large populations?

### Answer 51
  AWS Local Zones. :heavy_check_mark:
  AWS Outposts. :x:
  Regions. :x:
  Availability Zones. :x:

### Overall explanation
  :heavy_check_mark: Correct - Local Zones
  Local Zones are "mini-regions" (enabled separately) that extend your cloud environment to places with large populations (e.g., metropolitan areas). They are data centers located close to (or even inside of) metropolitan areas. You can run services in Local Zones to run them even closer to your end users.

  :x: Incorrect - Regions
  Regions are the main data center clusters that are distributed across the entire world. Due to the size of the data centers (and the fact that a Region contains multiple data centers), they are not close to metropolitan areas.

  :x: Incorrect - Availability Zones
  AZs are parts of Regions and may contain one or more (big) data centers (per AZ). Hence they are not close to metropolitan areas.

  :x: Incorrect - AWS Outposts
  AWS Outposts are Region extensions that can be added your own on-premises infrastructure. You can add AWS infrastructure to run and use AWS services in your own data centers.


### :grey_question: Question 52
  A company must store accounting data for at least 10 years. The data is typically not accessed anymore once uploaded to the cloud. If it must be retrieved, it suffices if data is available after a couple of hours.
  Which S3 storage class should be picked to achieve the highest cost savings?

### Answer 52
  S3 Glacier Deep Archive. :heavy_check_mark:
  S3 Standard. :x:
  S3 Glacier Instant Retrieval. :x:
  S3 Standard-Infrequent Access (S3 Standard-IA). :x:

### Overall explanation
  :heavy_check_mark: Correct - S3 Glacier Deep Archive
  Since no instant retrieval is required and data access is highly unlikely, S3 Glacier Deep Archive is a great choice. It offers significant cost reductions at the expense of reduced flexibility and data retrieval fees. It's perfect for data where access is unlikely and long-term storage is required.

  :x: Incorrect - S3 Standard-IA
  Whilst the Infrequent Access storage class does offer cost reductions, it does not offer the same amount of reductions as S3 Glacier does. It would be a good choice if short- or medium-term storage is required and access is rare but not highly unlikely. In the scenario described in this question, it's not the best choice.

  :x: Incorrect - S3 Glacier Instant Retrieval
  S3 Glacier Instant Retrieval offers high cost reductions for long-term data storage. Unlike Deep Archive, it also supports instant data access. It's perfect for scenarios where data must be stored long-term and access is highly unlikely but instant access is needed, if data must be accessed. In the scenario described in this question, instant access is not required, hence Deep Archive is better than this storage class.

  :x: Incorrect - S3 Standard
  S3 Standard is the default storage class every object receives. It does not offer any cost reductions.


### :grey_question: Question 53
  A company considers moving its workloads to the AWS cloud. In order to create a Total Cost of Ownership (TCO) proposal, the company needs to estimate the expected costs of using certain AWS services.
  Which tool can the company use?

### Answer 53
  AWS Cost Explorer. :x:
  AWS Pricing Calculator. :heavy_check_mark:
  AWS Cost and Usage Reports. :x:
  AWS Budgets. :x:

### Overall explanation
  :heavy_check_mark: Correct - AWS Pricing Calculator
  This tool can be used to generate cost estimates for various AWS services. Users can choose service configurations (e.g., EC2 instance types) and derive cost estimates. These estimates can than be used to compare them.

  :x: Incorrect - AWS Budgets
  AWS Budgets is a tool for setting spending budgets and receiving alerts once budgets are (close to) being exceeded. It's not a tool for estimating costs.

  :x: Incorrect - AWS Cost Explorer
  Cost Explorer can be used to analyze costs. It's a great tool for understanding which service or Region contributed to the total costs. It's not a tool for estimating future costs though.

  :x: Incorrect - AWS Cost and Usage Reports
  Cost and Usage Reports is a service that helps with generating CSV file that contain detailed cost data. That data could then be evaluated with other services or tools. It's also not a tool for creating service cost estimates though.


### :grey_question: Question 54
  Which AWS services can be utilized to build serverless REST or GraphQL web APIs? (Select TWO.)

### Answer 54
  Amazon API Gateway. :heavy_check_mark:
  Amazon Route 53. :x:
  AWS AppSync. :heavy_check_mark:
  Application Load Balancer. :x:
  AWS DataSync. :x:

### Overall explanation
  :heavy_check_mark: Correct - AppSync
  The AppSync service can be used to build serverless GraphQL web APIs in the AWS cloud. It allows users to configure and create a GraphQL API that integrates with other services (e.g., Lambda) without writing any API boilerplate code.

  :heavy_check_mark: Correct - API Gateway
  The API Gateway service can be used to build serverless REST web APIs in the AWS cloud. It allows users to configure and create a REST API (including all its endpoints etc.) that integrates with other services (e.g., Lambda) without writing any API boilerplate code.

  :x: Incorrect - DataSync
  DataSync is a service that helps with migrating data (files) from local data centers to the cloud. It's not a service that could be used to build public web APIs.

  :x: Incorrect - Route 53
  Route 53 is Amazon's DNS service. It can be used for registering and managing domains and for configuring domain routing. It can, for example, forward incoming requests to an Application Load Balancer. It's not a service that can be used to build REST or GraphQL APIs.

  :x: Incorrect - Application Load Balancer (ALB)
  ALB is a service that can be used to distribute incoming load evenly across available resources (e.g., across EC2 instances). Whilst it can perform some basic routing or request forwarding tasks it's not a service that should be used for building REST APIs. It also does not offer the features required to build GraphQL APIs.


### :grey_question: Question 55
  Which Amazon EC2 instance family is designed to deliver fast performance for workloads that process large datasets in memory?

### Answer 55
  Compute Optimized. :x:
  Storage Optimized. :x:
  Memory Optimized. :heavy_check_mark:
  General Purpose. :x:

### Overall explanation
  :heavy_check_mark: Correct - Memory Optimized
  As the name suggests, instance types that belong to this family are optimized for memory-intensive computations.

  :x: Incorrect - Other Options
  The other instance families are optimized for different purposes and tasks (as suggested by their names).


### :grey_question: Question 56
  You have a workload running on top of EC2 instances that runs consistently for two hours and must not be interrupted. The workload runs once a day, for exactly one month.
  Which instance type should be used to run the workload in the most cost-efficient way?

### Answer 56
  Reserved Instances. :x:
  On-Demand Instances. :heavy_check_mark:
  Dedicated Instances. :x:
  Spot Instances. :x:

### Overall explanation
  :heavy_check_mark: Correct - On-Demand Instances
  Even though no cost savings are achieved with On-Demand Instances, this is the best option for the described workload.
  If the workload would run for more than a year, Reserved Instances may offer cost savings. If it would be interruptible, Spot Instances could help achieve cost savings. But since this all isn't the case, the standard On-Demand Instances are the best choice here.

  :x: Incorrect - Reserved Instances
  Reserved Instances can help achieve cost reductions but you must commit upfront for 1 or 3 years. Since this workload will only run for a month, no cost savings can be achieved with Reserved Instances in this case.

  :x: Incorrect - Spot Instances
  Spot Instances can offer great price reductions but they may also be reclaimed by AWS at any time. Therefore, they are great for interruptible workloads but not for workloads that must not be interrupted.

  :x: Incorrect - Dedicated Instances
  With Dedicated Instances, you can ensure that your instances are placed on hardware that's dedicated to you. This is not a pricing strategy or cost reduction model.


### :grey_question: Question 57
  Which AWS service can be used to cache static content and deliver content with low latencies to end users?

### Answer 57
  Amazon Route 53. :x:
  Amazon ElastiCache. :x:
  Amazon CloudFront. :heavy_check_mark:
  Amazon Virtual Private Cloud (VPC). :x:

### Overall explanation
  :heavy_check_mark: Correct - CloudFront
  CloudFront is a service that uses AWS' edge locations network to cache static content close to end users (e.g., close to website users). Content can be delivered with lower latencies because user requests don't have to travel to the origin (e.g., to the EC2 instance running a web server) but instead terminate at the closest edge location.

  :x: Incorrect - VPC
  The VPC service allows users to create a private virtual network in the cloud. VPCs (and their subnets) are used to hold other cloud resources like EC2 instances. The VPC service is not a service that speeds up content delivery or performs any caching.

  :x: Incorrect - Route 53
  Route 53 is Amazon's DNS service. It can be used for registering and managing domains and for configuring domain routing. It can, for example, forward incoming requests to an Application Load Balancer. It does not speed up content delivery or perform any caching though.

  :x: Incorrect - ElastiCache
  ElastiCache is a service that can be used to create caching databases (Redis or Memcached). Caching databases can be used to store arbitrary data in them - they are not used for caching static files though. ElastiCache also does not speed up content delivery in any way.


### :grey_question: Question 58
  How can AWS customers benefit from AWS' Global Reach? (Select TWO.)

### Answer 58
  A global support team can assist with issues. :x:
  Applications can be run close to end users or customers. :heavy_check_mark:
  Workloads can be distributed across the world. :heavy_check_mark:
  Applications can be run in a central place. :x:
  Users can tap into the AWS Partner Network (APN). :x:

### Overall explanation
  :heavy_check_mark: Correct - Applications can be run close to end users or customers
  Since AWS owns and operates a global infrastructure (with data centers across the entire world), AWS users can run their workloads and applications anywhere in the world. This means that applications that are used by end users can be run close to those end users.

  :heavy_check_mark: Correct - Workloads can be distributed across the world
  Due to AWS Global Reach (i.e., its global infrastructure) workloads can be split up across multiple Regions - for example, to achieve High Availability. Or to benefit from lower prices in certain Regions. Or for a variety of other reasons.

  :x: Incorrect - A global support team can assist with issues
  AWS offers support (free and paid) but the support team is not part of the Global Reach value proposition.

  :x: Incorrect - Applications can be run in a central place
  That's possible without AWS' global infrastructure - and it's not a benefit. If AWS had only one data center, all workloads would need to run there. The fact that AWS has dozens of data centers across the world is the advantage instead.

  :x: Incorrect - Users can tap into the AWS Partner Network (APN)
  The APN can be very helpful and useful but it's not related to the Global Reach advantage. It's also a network of AWS partners - not part of AWS itself.


### :grey_question: Question 59
  Which AWS features can you use to export cost data and perform analytics on the exported data? (Select TWO.)

### Answer 59
  AWS Pricing Calculator. :x:
  Cost and Usage Reports. :heavy_check_mark:
  Amazon CloudWatch. :x:
  Cost Explorer. :x:
  Amazon QuickSight. :heavy_check_mark:

### Overall explanation
  :heavy_check_mark: Correct - Cost and Usage Reports
  Cost and Usage Reports is a service that can be used to configure regular cost data exports. The exported CSV files contain detailed cost data that can be analyzed with external tools.

  :heavy_check_mark: Correct - Amazon QuickSight
  Amazon QuickSight is Amazon's business intelligence service that can be used to analyze data and create charts and reports. You can use this service to import and analyze the data exported by Cost and Usage Reports.

  :x: Incorrect - Cost Explorer
  Cost Explorer can be used to analyze cost data without exporting it first. Whilst it is a cost analysis tool, it is less granular than Cost and Usage Reports data and does not support data exporting.

  :x: Incorrect - Amazon CloudWatch
  CloudWatch is a service that can be used to collect and analyze application and cloud resource metrics and logs. It's not a cost analysis or exporting service.

  :x: Incorrect - AWS Pricing Calculator
  Pricing Calculator can be used to calculate estimated service costs. It's not a tool for analyzing actual costs or exporting any cost data.


### :grey_question: Question 60
  Which AWS Organizations feature can be used to set maximum permission guardrails for organization accounts?

### Answer 60
  Organization Policies. :x:
  Custom Policies. :x:
  Service Control Policies (SCPs). :heavy_check_mark:
  Managed Policies. :x:

### Overall explanation
  :heavy_check_mark: Correct - Service Control Policies (SCPs)
  Service Control Policies are an AWS Organizations feature that allows you to set permission guardrails for organization accounts. These guardrails set maximum access rights which can't be exceeded by permissions set inside of the affected organization accounts. Even if an identity (e.g., an IAM user) in an account would receive a policy that grants more access rights, the SCP would restrict the maximum access rights.

  :x: Incorrect - Managed Policies
  Managed Policies can be used to add pre-defined permission "packages" (=> policies) to IAM identities without manually creating them. This has nothing to do with restricting organization account permission rights.

  :x: Incorrect - Custom Policies
  Custom Policies are policies created manually. They can then be used like any other policies (e.g., they may be attached to IAM users). This has nothing to do with restricting organization account permission rights.

  :x: Incorrect - Organization Policies
  When using AWS Organizations, different kinds of policies can be set (different "Organization Policies"). For example, "Tag Policies". But it's just a term that could be used to describe this group of policies - it's not the feature that would be used to control account permissions.


### :grey_question: Question 61
  Where can users find comprehensive and detailed information about AWS services, features and pricing?

### Answer 61
  In the AWS forum. :x:
  In the AWS blog. :x:
  In the Trusted Advisor service. :x:
  On the AWS service pages on AWS' website. :heavy_check_mark:

### Overall explanation
  :heavy_check_mark: Correct - Service pages on website
  AWS has detailed service pages and tutorials on its website. Exploring the documentation for the different services and diving into the prices pages helps AWS users understand service functionalities and potential costs.

  :x: Incorrect - AWS forums
  You can find useful discussions and problem-specific help in the AWS forums but it's not a comprehensive resource that covers all services and all configuration options.

  :x: Incorrect - AWS blog
  The articles in the AWS blog are very helpful for exploring specific problems and demo implementations. Especially for advanced or non-trivial use-cases, interesting solutions and best practices can be found. It's not the place to find detailed summaries and descriptions of services though.

  :x: Incorrect - Trusted Advisor
  Trusted Advisor is a service that performs automated checks to create recommendations. It's a great service for fixing problems with your cloud infrastructure. But it's not a service or place that contains detailed information on other services or service pricing.


### :grey_question: Question 62
  Which AWS service can be used to monitor an AWS account and inspect every API request performed against its AWS resources.

### Answer 62
  AWS Trusted Advisor. :x:
  AWS CloudTrail. :heavy_check_mark:
  Amazon CloudWatch. :x:
  Amazon Inspector. :x:

### Overall explanation
  :heavy_check_mark: Correct - AWS CloudTrail
  CloudTrail is a service that can be used to monitor and analyze cloud resource API calls (i.e., actions taken against cloud resources). It can be used to find out which identity (e.g., user or role) performed which action (e.g., start an EC2 instance).

  :x: Incorrect - Amazon CloudWatch
  Amazon CloudWatch is a service for collecting and analyzing cloud resource metrics and logs. It's great for understanding workload performance and resource health but it does not help with analyzing account actions.

  :x: Incorrect - Amazon Inspector
  Amazon Inspector is a service that helps with finding application and workload vulnerabilities. It can help with detecting software vulnerabilities but it can't help with monitoring account actions.

  :x: Incorrect - AWS Trusted Advisor
  This is a service that provides automatic recommendations to follow cloud best pratices. It's not a service that helps with analyzing cloud actions.


### :grey_question: Question 63
  A company stores sensor data in a S3 bucket. Immediately after being stored, the data is frequently accessed for the next 30 days. After 30 days, it's only occassionally accessed.
  Which S3 feature can be used to reduce costs?

### Answer 63
  Lifecycle Management. :heavy_check_mark:
  S3 Transfer Acceleration. :x:
  Object Lock. :x:
  Cross-Region Replication. :x:

### Overall explanation
  :heavy_check_mark: Correct - Lifecycle Management
  With Lifecycle Management, you can set transition rules that define when objects are moved to a different storage class. This allows you to assign objects (files) to different storage classes based on changing access patterns.

  :x: Incorrect - Cross-Region Replication
  This feature can be used to automatically replicate files in one bucket to other buckets in other Regions. It's a great feature for increasing data availability but it's not a cost saving feature.

  :x: Incorrect - Object Lock
  With Object Lock, you can protect files against changes or deletion. This can be required for legal or compliance reasons. It's not a cost reduction tool.

  :x: Incorrect - S3 Transfer Acceleration
  This feature can speed up network file transfers - it's not a cost reduction tool.


### :grey_question: Question 64
  Which service can AWS users use to download AWS compliance reports?

### Answer 64
  AWS Audit Manager. :x:
  Amazon QuickSight. :x:
  AWS Artifact. :heavy_check_mark:
  AWS Config. :x:

### Overall explanation
  :heavy_check_mark: Correct - AWS Artifact
  AWS Artifact is a self-service portal for downloading reports that prove AWS' compliance with various standards or regulations. Users can use this portal to download compliance reports.

  :x: Incorrect - AWS Audit Manager
  AWS Audit Manager is, as the name suggests, also a service that helps with audits and compliance. It focuses on helping users asses their own AWS usage and compliance. It can be used to generate compliance reports for user workloads and resource usage. It is not a service for downloading AWS compliance reports.

  :x: Incorrect - AWS Config
  AWS Config is a service that can be used to set and evaluate account-wide (or even multi-account-wide) service configurations. This can be helpful for achieving application and workload compliance but it's not a service for downloading AWS compliance reports.

  :x: Incorrect - Amazon QuickSight
  QuickSight is Amazon's own business intelligence (BI) tool / service. You can use it to create reports, charts and analyses for various data sources. It is not related to compliance though.


### :grey_question: Question 65
  How can companies with varying workload demand reduce costs by moving from self-owned data centers to cloud computing resources? (Select TWO.)

### Answer 65
  AWS compute resources can be stopped at any time. :heavy_check_mark:
  On-premises infrastructure can be removed at any time. :x:
  With AWS, users only pay for resources used. :heavy_check_mark:
  In the cloud, users can use more resources than required by a workload. :x:
  AWS service usage is billed on a monthly basis. :x:

### Overall explanation
  :heavy_check_mark: Correct - With AWS, users only pay for resources used
  When using AWS compute services (EC2, ECS, Lambda), users only pay for the actual resources used. If an EC2 instance is not running, users don't pay. The same is true for a Lambda function or ECS cluster. Compared to local, self-owned infrastructure that means that there are no fixed costs.

  :heavy_check_mark: Correct - AWS compute resources can be stopped at any time
  This is kind of related to the first correct answer. Since users only pay for resources used, it's crucial that resource usage can be stopped at any time (i.e., when resources are not needed any more, due to reduced workload demand).

  :x: Incorrect - In the cloud, users can use more resources than required by a workload
  Whilst you could use more resources than required (e.g., run more EC2 instances than required), that would of course not be an advantage of the cloud. It would also be unnecessary and not help with reducing costs.

  :x: Incorrect - AWS service usage is billed on a monthly basis
  Indeed, AWS bills usage on a monthly basis but the same is probably true for local data center costs like electricity bills. It's not a cloud advantage.

  :x: Incorrect - On-premises infrastructure can be removed at any time
  The opposite is correct. On-premises infrastructure can't easily be removed and re-added. Instead, you have a fixed capacity that can only slowly change.

