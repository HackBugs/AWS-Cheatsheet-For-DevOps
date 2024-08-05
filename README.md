# AWS-Cheatsheet-Devops
- Author : ✍️ Hackbugs

## list of open-source DevOps tools along with their equivalents used in AWS DevOps:

| Open Source DevOps Tool | AWS Equivalent | Purpose | Default Port |
|-------------------------|----------------|---------|--------------|
| Kubernetes              | Amazon EKS (Elastic Kubernetes Service) | Container orchestration | N/A (Uses multiple ports) |
| SonarQube               | AWS CodeGuru Reviewer | Code quality and security analysis | 9000 |
| Nexus                   | AWS CodeArtifact | Artifact repository management | 8081 |
| Jenkins                 | AWS CodePipeline | Continuous Integration/Continuous Deployment (CI/CD) | 8080 |
| Prometheus              | Amazon CloudWatch | Monitoring and alerting | 9090 |
| Grafana                 | Amazon Managed Grafana | Visualization and analytics | 3000 |
| Ansible                 | AWS Systems Manager (for automation) | Configuration management and automation | N/A (SSH-based, uses port 22) |
| Terraform               | AWS CloudFormation | Infrastructure as Code (IaC) | N/A |
| Docker                  | Amazon ECS (Elastic Container Service) | Containerization and container management | N/A (Uses multiple ports) |
| Nagios                  | Amazon CloudWatch | Monitoring and alerting | 5666 (NRPE), 5667 (NSCA), 8080 (Web interface) |
| Git                     | AWS CodeCommit | Source code management | N/A (Uses SSH - 22, HTTP/S - 80/443) |
| GitHub                  | AWS CodeCommit | Source code management and collaboration | N/A (Uses SSH - 22, HTTP/S - 80/443) |
| Helm                    | AWS App Mesh (for managing microservices) | Kubernetes package management | N/A |
| GitLab                  | AWS CodeCommit, CodePipeline | Source code management, CI/CD | 80 (HTTP), 443 (HTTPS), 22 (SSH) |
| Travis CI               | AWS CodePipeline | Continuous Integration (CI) | N/A |
| CircleCI                | AWS CodePipeline | Continuous Integration (CI) | N/A |
| Bamboo                  | AWS CodePipeline | Continuous Integration/Continuous Deployment (CI/CD) | 8085 |
| Vault (HashiCorp)       | AWS Secrets Manager | Secrets management | 8200 |
| Consul (HashiCorp)      | AWS Cloud Map | Service discovery and configuration | 8500 (HTTP API), 8300 (Server RPC), 8301 (Serf LAN), 8600 (DNS) |
| ELK Stack (Elasticsearch, Logstash, Kibana) | Amazon OpenSearch Service | Logging, search, and analytics | 9200 (Elasticsearch), 5601 (Kibana), 5044 (Logstash) |
| Splunk                  | Amazon CloudWatch Logs | Logging and monitoring | 8000 (Web UI), 8089 (Management), 9997 (Forwarding) |
| Puppet                  | AWS OpsWorks | Configuration management and automation | 8140 |
| Chef                    | AWS OpsWorks | Configuration management and automation | 443 (HTTPS) |
| SaltStack               | AWS Systems Manager | Configuration management and automation | 4505 (Publisher), 4506 (Worker) |
| Selenium                | AWS Device Farm | Automated testing | 4444 (Hub) |
| JFrog Artifactory       | AWS CodeArtifact | Artifact repository management | 8081 |
| Rundeck                 | AWS Systems Manager | Operations automation | 4440 |
| Vagrant                 | AWS CloudFormation (for infrastructure as code) | Development environment automation | N/A |
| Packer                  | AWS EC2 Image Builder | Automated machine image creation | N/A |
| Spinnaker               | AWS CodePipeline | Continuous Delivery (CD) | 9000 |
| Argo CD                 | AWS CodePipeline | Continuous Delivery (CD) for Kubernetes | 8080 |
| Harbor                  | Amazon ECR (Elastic Container Registry) | Container image registry | 80 (HTTP), 443 (HTTPS) |
| Maven                   | AWS CodeBuild | Build automation and dependency management | N/A |
| Ant                     | AWS CodeBuild | Build automation | N/A |

This table now includes the default ports for the various DevOps tools where applicable.
_______________________________________________________________________________________________________________________________________________________________________________________________________

## Here's an extended table categorizing DevOps tools into their respective types (IaaS, PaaS, SaaS) for both open source and AWS equivalents:

### DevOps Tools
| Open Source DevOps Tool | AWS Equivalent | Purpose | Default Port |
|-------------------------|----------------|---------|--------------|
| Kubernetes              | Amazon EKS (Elastic Kubernetes Service) | Container orchestration | N/A (Uses multiple ports) |
| SonarQube               | AWS CodeGuru Reviewer | Code quality and security analysis | 9000 |
| Nexus                   | AWS CodeArtifact | Artifact repository management | 8081 |
| Jenkins                 | AWS CodePipeline | Continuous Integration/Continuous Deployment (CI/CD) | 8080 |
| Prometheus              | Amazon CloudWatch | Monitoring and alerting | 9090 |
| Grafana                 | Amazon Managed Grafana | Visualization and analytics | 3000 |
| Ansible                 | AWS Systems Manager (for automation) | Configuration management and automation | N/A (SSH-based, uses port 22) |
| Terraform               | AWS CloudFormation | Infrastructure as Code (IaC) | N/A |
| Docker                  | Amazon ECS (Elastic Container Service) | Containerization and container management | N/A (Uses multiple ports) |
| Nagios                  | Amazon CloudWatch | Monitoring and alerting | 5666 (NRPE), 5667 (NSCA), 8080 (Web interface) |
| Git                     | AWS CodeCommit | Source code management | N/A (Uses SSH - 22, HTTP/S - 80/443) |
| GitHub                  | AWS CodeCommit | Source code management and collaboration | N/A (Uses SSH - 22, HTTP/S - 80/443) |
| Helm                    | AWS App Mesh (for managing microservices) | Kubernetes package management | N/A |
| GitLab                  | AWS CodeCommit, CodePipeline | Source code management, CI/CD | 80 (HTTP), 443 (HTTPS), 22 (SSH) |
| Travis CI               | AWS CodePipeline | Continuous Integration (CI) | N/A |
| CircleCI                | AWS CodePipeline | Continuous Integration (CI) | N/A |
| Bamboo                  | AWS CodePipeline | Continuous Integration/Continuous Deployment (CI/CD) | 8085 |
| Vault (HashiCorp)       | AWS Secrets Manager | Secrets management | 8200 |
| Consul (HashiCorp)      | AWS Cloud Map | Service discovery and configuration | 8500 (HTTP API), 8300 (Server RPC), 8301 (Serf LAN), 8600 (DNS) |
| ELK Stack (Elasticsearch, Logstash, Kibana) | Amazon OpenSearch Service | Logging, search, and analytics | 9200 (Elasticsearch), 5601 (Kibana), 5044 (Logstash) |
| Splunk                  | Amazon CloudWatch Logs | Logging and monitoring | 8000 (Web UI), 8089 (Management), 9997 (Forwarding) |
| Puppet                  | AWS OpsWorks | Configuration management and automation | 8140 |
| Chef                    | AWS OpsWorks | Configuration management and automation | 443 (HTTPS) |
| SaltStack               | AWS Systems Manager | Configuration management and automation | 4505 (Publisher), 4506 (Worker) |
| Selenium                | AWS Device Farm | Automated testing | 4444 (Hub) |
| JFrog Artifactory       | AWS CodeArtifact | Artifact repository management | 8081 |
| Rundeck                 | AWS Systems Manager | Operations automation | 4440 |
| Vagrant                 | AWS CloudFormation (for infrastructure as code) | Development environment automation | N/A |
| Packer                  | AWS EC2 Image Builder | Automated machine image creation | N/A |
| Spinnaker               | AWS CodePipeline | Continuous Delivery (CD) | 9000 |
| Argo CD                 | AWS CodePipeline | Continuous Delivery (CD) for Kubernetes | 8080 |
| Harbor                  | Amazon ECR (Elastic Container Registry) | Container image registry | 80 (HTTP), 443 (HTTPS) |
| Maven                   | AWS CodeBuild | Build automation and dependency management | N/A |
| Ant                     | AWS CodeBuild | Build automation | N/A |

### Infrastructure as a Service (IaaS)
| Open Source IaaS Tool | AWS IaaS Equivalent | Purpose | Default Port |
|-----------------------|---------------------|---------|--------------|
| OpenStack             | Amazon EC2          | Compute resources | N/A |
| KVM (Kernel-based Virtual Machine) | Amazon EC2 | Virtualization | N/A |
| Apache CloudStack     | Amazon EC2          | Cloud computing | N/A |
| Xen Project           | Amazon EC2          | Virtualization | N/A |
| Proxmox VE            | Amazon EC2          | Virtualization and container management | N/A |

### Platform as a Service (PaaS)
| Open Source PaaS Tool | AWS PaaS Equivalent | Purpose | Default Port |
|-----------------------|---------------------|---------|--------------|
| OpenShift             | AWS Elastic Beanstalk | Application deployment and management | N/A |
| Cloud Foundry         | AWS Elastic Beanstalk | Application deployment and management | N/A |
| Dokku                 | AWS Elastic Beanstalk | Application deployment and management | N/A |
| Tsuru                 | AWS Elastic Beanstalk | Application deployment and management | N/A |

### Software as a Service (SaaS)
| Open Source SaaS Tool | AWS SaaS Equivalent | Purpose | Default Port |
|-----------------------|---------------------|---------|--------------|
| Mattermost            | Amazon Chime        | Team collaboration and messaging | 8065 |
| Nextcloud             | Amazon WorkDocs     | File sharing and collaboration | 443 |
| Discourse             | Amazon SES          | Forum and discussion platform | 80, 443 |
| Taiga                 | AWS CodeStar        | Project management | 8000 |
| Rocket.Chat           | Amazon Chime        | Team collaboration and messaging | 3000 |
| SuiteCRM              | Amazon Connect      | Customer relationship management (CRM) | 80, 443 |
| EspoCRM               | Amazon Connect      | Customer relationship management (CRM) | 80, 443 |

This extended table categorizes various DevOps tools, their AWS equivalents, purposes, and default ports where applicable. It also includes additional categories for IaaS, PaaS, and SaaS tools.
________________________________________________________________________________________________________________________________________________________________________________________________________
This repository provides a concise and comprehensive guide to essential AWS services, including **EC2, S3, IAM, RDS, VPC, CloudFormation, Lambda, and CloudWatch** . Ideal for both beginners and advanced users, it offers quick references for commands, tips, and best practices. Contributions are welcome to enhance this resource.

## AWS

Here's a description for your AWS cheat sheet repository on GitHub:

---

# AWS Cheat Sheet

- AWS Cheat Sheet repository! This repo serves as a comprehensive and easy-to-navigate guide for Amazon Web Services (AWS) essentials. Whether you're a beginner just getting started or an advanced user looking for quick references, this cheat sheet will provide you with the necessary commands, tips, and best practices for efficiently managing your AWS environment.

## Contents

- **EC2 (Elastic Compute Cloud)**
  - Launching instances
  - Managing instances
  - Security groups
  - Key pairs
  - AMIs (Amazon Machine Images)

- **S3 (Simple Storage Service)**
  - Creating and managing buckets
  - Uploading, downloading, and managing objects
  - Bucket policies and access control

- **IAM (Identity and Access Management)**
  - Users, groups, and roles
  - Policies and permissions
  - Multi-Factor Authentication (MFA)

- **RDS (Relational Database Service)**
  - Creating and managing databases
  - Security and backups
  - Performance tuning

- **VPC (Virtual Private Cloud)**
  - Creating and managing VPCs
  - Subnets, route tables, and gateways
  - Network ACLs and security groups

- **CloudFormation**
  - Writing templates
  - Stacks and change sets
  - Resource management

- **Lambda**
  - Creating and deploying functions
  - Managing triggers and permissions
  - Monitoring and logging

- **CloudWatch**
  - Setting up alarms and metrics
  - Log management
  - Dashboard creation

## How to Use

1. **Clone the Repository**
   ```sh
   git clone https://github.com/yourusername/aws-cheat-sheet.git
   cd aws-cheat-sheet
   ```

2. **Navigate the Contents**
   Browse through the various sections to find the information you need. Each section is designed to provide quick and clear references for commonly used AWS services and commands.

3. **Contribute**
   Contributions are welcome! If you have additional tips, commands, or best practices, feel free to submit a pull request.
```sh
   ## **EC2 (Elastic Compute Cloud)**
    - Instances
    - Images
    - Elastic Block Store
    - Network & Security
    - Load Balancing
    - Auto Scaling
  ## **S3 (Simple Storage Service)**
  ## **IAM (Identity and Access Management)**
  ## **RDS (Relational Database Service)**
  ## **VPC (Virtual Private Cloud)**
  ## **CloudFormation**
  ## **Lambda**
  ## **CloudWatch**
```
   ---
# Here is a categorized list of AWS services based on your request:
### Compute
- EC2
- Lightsail
- Lambda
- Batch
- Elastic Beanstalk
- Serverless Application Repository
- AWS Outposts
- EC2 Image Builder
- AWS App Runner
- AWS SimSpace Weaver

### Containers
- Elastic Container Service (ECS)
- Elastic Kubernetes Service (EKS)
- Red Hat OpenShift Service on AWS
- Elastic Container Registry (ECR)

### Storage
- S3
- EFS
- FSx
- S3 Glacier
- Storage Gateway
- AWS Backup
- AWS Elastic Disaster Recovery

### Database
- RDS
- ElastiCache
- Neptune
- Amazon QLDB
- Amazon DocumentDB
- Amazon Keyspaces
- Amazon Timestream
- DynamoDB
- Amazon MemoryDB

### Migration & Transfer
- AWS Migration Hub
- AWS Application Migration Service
- Application Discovery Service
- Database Migration Service
- AWS Transfer Family
- AWS Snow Family
- DataSync
- AWS Mainframe Modernization

### Networking & Content Delivery
- VPC
- CloudFront
- Route 53
- API Gateway
- Direct Connect
- AWS App Mesh
- Global Accelerator
- AWS Cloud Map
- Route 53 Application Recovery Controller
- AWS Private 5G

### Developer Tools
- CodeStar
- CodeCommit
- CodeBuild
- CodeDeploy
- CodePipeline
- Cloud9
- CloudShell
- X-Ray
- AWS FIS
- CodeArtifact
- Amazon CodeCatalyst
- AWS AppConfig
- Amazon Q Developer (Including Amazon CodeWhisperer)
- Application Composer
- AWS App Studio

### Customer Enablement
- AWS IQ
- Managed Services
- Activate for Startups

### Support
- AWS re:Post Private

### Robotics
- AWS RoboMaker

### Blockchain
- Amazon Managed Blockchain

### Satellite
- Ground Station

### Quantum Technologies
- Amazon Braket

### Management & Governance
- AWS Organizations
- CloudWatch
- AWS Auto Scaling
- CloudFormation
- AWS Config
- OpsWorks
- Service Catalog
- Systems Manager
- Trusted Advisor
- Control Tower
- AWS Well-Architected Tool
- AWS Chatbot
- Launch Wizard
- AWS Compute Optimizer
- Resource Groups & Tag Editor
- Amazon Grafana
- Amazon Prometheus
- AWS Resilience Hub
- Incident Manager
- AWS License Manager
- Service Quotas
- AWS Proton
- CloudTrail
- AWS Resource Explorer
- AWS User Notifications
- AWS Health Dashboard
- AWS Telco Network Builder

### Media Services
- Kinesis Video Streams
- MediaConvert
- MediaLive
- MediaPackage
- MediaStore
- MediaTailor
- Elemental Appliances & Software
- Elastic Transcoder
- Nimble Studio
- MediaConnect
- Amazon Interactive Video Service
- AWS Deadline Cloud

### Machine Learning
- Amazon SageMaker
- Amazon Augmented AI
- Amazon CodeGuru
- Amazon DevOps Guru
- Amazon Comprehend
- Amazon Forecast
- Amazon Fraud Detector
- Amazon Kendra
- Amazon Personalize
- Amazon Polly
- Amazon Rekognition
- Amazon Textract
- Amazon Transcribe
- Amazon Translate
- AWS DeepComposer
- AWS DeepRacer
- AWS Panorama
- Amazon Monitron
- AWS HealthLake
- Amazon Lookout for Vision
- Amazon Lookout for Equipment
- Amazon Lookout for Metrics
- Amazon Lex
- Amazon Comprehend Medical
- AWS HealthOmics
- Amazon Bedrock

### Analytics
- Athena
- Amazon Redshift
- CloudSearch
- Amazon OpenSearch Service
- Kinesis
- QuickSight
- Data Pipeline
- AWS Data Exchange
- AWS Lake Formation
- MSK
- AWS Glue DataBrew
- Amazon FinSpace
- AWS Glue
- Amazon Data Firehose
- EMR
- AWS Clean Rooms
- Amazon DataZone
- AWS Entity Resolution
- Managed Apache Flink

### Security, Identity, & Compliance
- Resource Access Manager
- Cognito
- Secrets Manager
- GuardDuty
- Amazon Inspector
- Amazon Macie
- IAM Identity Center
- Certificate Manager
- Key Management Service
- CloudHSM
- Directory Service
- WAF & Shield
- AWS Firewall Manager
- AWS Artifact
- Detective
- AWS Signer
- AWS Private Certificate Authority
- Security Hub
- AWS Audit Manager
- Security Lake
- Amazon Verified Permissions
- AWS Payment Cryptography
- IAM

### Cloud Financial Management
- AWS Marketplace
- AWS Billing Conductor
- Billing and Cost Management

### Front-end Web & Mobile
- AWS Amplify
- AWS AppSync
- Device Farm
- Amazon Location Service

### Application Integration
- Step Functions
- Amazon AppFlow
- Amazon MQ
- Simple Notification Service (SNS)
- Simple Queue Service (SQS)
- SWF
- Managed Apache Airflow
- Amazon EventBridge
- AWS B2B Data Interchange

### Business Applications
- Amazon Connect
- Amazon Chime
- Amazon Simple Email Service (SES)
- Amazon WorkDocs
- Amazon WorkMail
- AWS Supply Chain
- AWS AppFabric
- AWS Wickr
- Amazon Chime SDK
- Amazon One Enterprise
- Amazon Pinpoint

### End User Computing
- WorkSpaces
- AppStream 2.0
- WorkSpaces Secure Browser
- WorkSpaces Thin Client

### Internet of Things
- IoT Analytics
- IoT Device Defender
- IoT Device Management
- IoT Greengrass
- IoT SiteWise
- IoT Core
- IoT Events
- AWS IoT FleetWise
- IoT TwinMaker

### Game Development
- Amazon GameLift
