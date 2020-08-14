**Add a cover photo like:**
![placeholder image](https://via.placeholder.com/1200x600)

# Second Dat

## Introduction

✍️ I have decide to start with AWS and started going through acloudguru courses.

✍️No Prior knowledge is needed for this day

##Cloud Research

✍️ Notes for the concepts learned today.
 

Aws Intro:

      Networking   
Region is a geographical area – Each Region consists of 2 more availability zones
Availability zone – is simply data centre
Edge Location – Content Delivery network (cached location) for cloud front
Networking           
VPC – virtual data centre
Route 53 – Amazon DNS service (53 is DNS port)
CloudFront – Part of cdn 
Direct connect – connecting physical datacentres to aws (using dedicated lines)
EC2(Elastic compute cloud) -- virtual machines in aws
EC2 container services – docker and cluster management (ECS)

Elastic Beanstalk – deploy your code in to aws, you can upload into elastic beanstalk and it will identify underlying resources

Lambda – serverless (we upload our code and code will respond to underlying resources
LightSail – will deploy WordPress kind of sites

Storage:
4 different components
S3 – Simple Storage Service (Virtual disk in cloud where we can store objects)
Object based storage and block-based storage
Glacier – where we archive from s3, we do not need instant access of the files those files are stored in Glaciers
EFS – Elastic File Service – File based storage (we can install databases, application and share the volume with multiple machines.
Storage Gateway – Used to Connect s3 to on premises data centre.
 Databases:
RDS – Relational Database Service (MySQL, aurora, Postgress, ….)
DynamoDB – Non-Relational Database
Redshift -- Amazons data warehousing solution.
Elastic Cache – Caching data in the cloud

Migration Service:
Snowball:  started as import and export,
                       Used to transfer the files from the disk to s3
                       Snowball appliance
                        Snowball edge 

DMS: Data migration services
This allows you to migrate on premise database to aws cloud.

SMS: Server Migration Service – VMware machines can be migrated to AWS

Analytics:
Athena – allows you to run sql queries on s3 (turning files into searchable database)
EMR - Elastic map reduce (used to process large amount of data uses a framework called Hadoop, spark)
Cloud Search, Elastic Search – Cloud search is a managed service
                                                         Elastic search is based on open source framework
                                                           Can be used to add search capability

Kinesis – Used for analysing market, sentiment analysis, social media feeds.

Data Pipeline – Used to move data from one service to another example from s3 to dynamo db.

Quick sight – Business analytics tool, analyse data is s3 , rds , dynamo db.

       Security:
 Iam – Identity access management 
 Inspector – installs on virtual machines and inspects
Certificate Manager – gives certificates to sites
Directory Services – Active directory
WAF - Web application Firewall (Application level protection to firewall)
Artificats – place where we get compliance documentation

Management Tools:
	CloudWatch – monitor performance of aws environment, you can monitor disk utilization, ram utilisation.
              CloudFormation – Turning infrastructure into cloud
                                                CloudFormation template. Document describes aws environments
                                                 Entire environment can be deployed using CloudFormation template with a simple command.

      Cloud trail: Is used for auditing aws resources
     Opsworks:  way of automating deployment using shifts
    Config:  monitors environment and gives warning based on the configuration
   Service catalogue: built for bigger organisation, it allows as an enterprise what you authorize and what you do not authorize
  Trusted advisor: Designed by aws solution architecture team, automated way of scanning environment and giving tips about environments.

Application Services:
Step functions: way of visualizing what going on inside the application and what micro services are being used.

SWF: Simple workflow service - used in amazon fulfilment centre. Way of coordinating automated tasks and human lead tasks. When you order calculator (somebody must pick it up, someone must update the information about the packing of product) -swf will facilitate 

API Gateway:  as a door, it allows you to create, publish, maintain, monitor and secure apis at scale. A door for apps to access business logic or back end data or lambda.
                                               AppStream – used to stream desktop applications to users
Elastic transcoder: changes the video different formats required for users.

Developer Tools:
Code Commit:  Git hub, place to store code.
Code Build: is a way of compiling code, pay by minute

Code Deploy: Helps deploying code to ec2 instances.
Code pipeline: way of keeping tracking different versions of code in different environments.

Messaging:
Mobile hub: mobile hub is kind of aws console 
Cognito: makes it easy for user signup 

Artificial Intelligence:
Lex: for Alexa
Polly: takes any text and turns into mp3


SNS: Simple Notification Services
SQS: Simple Queue Services

Question 1: what is the difference between root user and IAM user?

Root account is the account that has control over entire aws account – Owner
The root user is created when the AWS account is created and IAM users are created by the root user or an IAM administrator for the account.


## Next Steps

✍️ Will continue with AWS Developer learning path

## Social Proof

✍️ Show that you shared your process on Twitter or LinkedIn

[Tweet](https://twitter.com/BharathMuddada/status/1294340420491546624)
