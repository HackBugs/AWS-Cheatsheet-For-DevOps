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

## AWS Cheat Sheet

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
________________________________________________________________________________________________________________________________________________________________________________________________________

## list of AWS services categorized with their open-source tool equivalents and purposes:

## Compute

| AWS Service | Open Source Tool | Purpose |
|-------------|-------------------|---------|
| EC2 | VirtualBox, VMware | Virtual servers (instances) |
| Lightsail | DigitalOcean, Linode | Simple virtual private servers |
| Lambda | OpenFaaS, Kubeless | Serverless compute functions |
| Batch | Apache Airflow | Batch job processing |
| Elastic Beanstalk | Heroku | Platform as a Service (PaaS) |
| Serverless Application Repository | Serverless Framework | Serverless application templates |
| AWS Outposts | OpenStack | On-premises hybrid cloud solution |
| EC2 Image Builder | Packer | Automated machine image creation |
| AWS App Runner | OpenShift | Managed application deployment |
| AWS SimSpace Weaver | No direct open-source equivalent | Large-scale spatial simulations |

### Containers

| AWS Service | Open Source Tool | Purpose |
|-------------|-------------------|---------|
| Elastic Container Service (ECS) | Docker Swarm | Container orchestration |
| Elastic Kubernetes Service (EKS) | Kubernetes | Container orchestration |
| Red Hat OpenShift Service on AWS | OpenShift | Kubernetes distribution with additional features |
| Elastic Container Registry (ECR) | Harbor | Container image registry |

### Storage

| AWS Service | Open Source Tool | Purpose |
|-------------|-------------------|---------|
| S3 | MinIO | Object storage |
| EFS | GlusterFS | Network file system |
| FSx | Lustre, OpenZFS | File systems for high performance |
| S3 Glacier | Glacier (open-source) | Archival storage |
| Storage Gateway | NFS, Samba | Hybrid cloud storage |

### Database

| AWS Service | Open Source Tool | Purpose |
|-------------|-------------------|---------|
| RDS | PostgreSQL, MySQL, MariaDB | Managed relational databases |
| ElastiCache | Redis, Memcached | In-memory caching |
| Neptune | Neo4j | Graph databases |
| Amazon QLDB | Hyperledger | Ledger databases |
| Amazon DocumentDB | MongoDB | Document databases |
| Amazon Keyspaces | Cassandra | Managed Cassandra service |
| Amazon Timestream | InfluxDB | Time series databases |
| DynamoDB | Cassandra | NoSQL databases |
| Amazon MemoryDB | Redis | Managed Redis-compatible database |

### Migration & Transfer

| AWS Service | Open Source Tool | Purpose |
|-------------|-------------------|---------|
| AWS Migration Hub | Apache Nifi | Migration tracking |
| AWS Application Migration Service | Clonezilla | Server migration |
| Application Discovery Service | OpenSource Discovery Tools | Application dependency discovery |
| Database Migration Service | pg_dump, mysqldump | Database migration |
| AWS Transfer Family | FileZilla | Managed file transfer |
| AWS Snow Family | Open-source data transfer tools | Physical data transport |
| DataSync | rsync | Data transfer automation |
| AWS Mainframe Modernization | No direct open-source equivalent | Mainframe modernization |

### Networking & Content Delivery

| AWS Service | Open Source Tool | Purpose |
|-------------|-------------------|---------|
| VPC | Open vSwitch | Virtual private cloud |
| CloudFront | Apache Traffic Server | Content delivery network (CDN) |
| Route 53 | BIND, CoreDNS | Domain name system (DNS) |
| API Gateway | Kong, Tyk | API management |
| Direct Connect | No direct open-source equivalent | Dedicated network connection |
| AWS App Mesh | Envoy | Service mesh |
| Global Accelerator | No direct open-source equivalent | Global traffic management |
| AWS Cloud Map | Consul | Service discovery |
| Route 53 Application Recovery Controller | No direct open-source equivalent | DNS-based application recovery |
| AWS Private 5G | No direct open-source equivalent | Private 5G networks |

### Developer Tools

| AWS Service | Open Source Tool | Purpose |
|-------------|-------------------|---------|
| CodeStar | GitLab | Integrated development environment |
| CodeCommit | Git | Source code management |
| CodeBuild | Jenkins | Build automation |
| CodeDeploy | Ansible, Chef | Deployment automation |
| CodePipeline | Jenkins | CI/CD pipeline |
| Cloud9 | Visual Studio Code | Cloud-based IDE |
| CloudShell | No direct open-source equivalent | Browser-based command-line interface |
| X-Ray | Zipkin | Distributed tracing |
| AWS FIS | Chaos Monkey | Fault injection testing |
| CodeArtifact | Nexus, Artifactory | Artifact repository |
| Amazon CodeCatalyst | GitHub, GitLab | Development workflow automation |
| AWS AppConfig | No direct open-source equivalent | Application configuration management |
| Amazon Q Developer (Including Amazon CodeWhisperer) | OpenAI Codex | AI-driven code suggestions |
| Application Composer | No direct open-source equivalent | Application design and orchestration |
| AWS App Studio | No direct open-source equivalent | Application development and management |

### Managed Services

| AWS Service | Open Source Tool | Purpose |
|-------------|-------------------|---------|
| Activate for Startups | No direct open-source equivalent | Startup support and resources |
| Support | No direct open-source equivalent | Technical support and troubleshooting |

### Robotics

| AWS Service | Open Source Tool | Purpose |
|-------------|-------------------|---------|
| AWS RoboMaker | ROS (Robot Operating System) | Robotics development and simulation |

### Blockchain

| AWS Service | Open Source Tool | Purpose |
|-------------|-------------------|---------|
| Amazon Managed Blockchain | Hyperledger Fabric | Managed blockchain service |

### Satellite

| AWS Service | Open Source Tool | Purpose |
|-------------|-------------------|---------|
| Ground Station | No direct open-source equivalent | Satellite data management |

### Quantum Technologies

| AWS Service | Open Source Tool | Purpose |
|-------------|-------------------|---------|
| Amazon Braket | Qiskit | Quantum computing service |

### Management & Governance

| AWS Service | Open Source Tool | Purpose |
|-------------|-------------------|---------|
| AWS Organizations | No direct open-source equivalent | Multi-account management |
| CloudWatch | Prometheus | Monitoring and logging |
| AWS Auto Scaling | Kubernetes Horizontal Pod Autoscaler | Automated scaling |
| CloudFormation | Terraform | Infrastructure as Code (IaC) |
| AWS Config | OpenSCAP | Configuration compliance |
| OpsWorks | Chef, Puppet | Configuration management |
| Service Catalog | No direct open-source equivalent | Service provisioning |
| Systems Manager | Ansible | Systems management and automation |
| Trusted Advisor | No direct open-source equivalent | Best practices and cost optimization |
| Control Tower | No direct open-source equivalent | Governance and management |
| AWS Well-Architected Tool | No direct open-source equivalent | Best practices assessment |
| AWS Chatbot | No direct open-source equivalent | Chat-based notifications |
| Launch Wizard | No direct open-source equivalent | Simplified deployment |
| AWS Compute Optimizer | No direct open-source equivalent | Resource optimization |
| Resource Groups & Tag Editor | No direct open-source equivalent | Resource management |

### Media Services

| AWS Service | Open Source Tool | Purpose |
|-------------|-------------------|---------|
| Kinesis Video Streams | No direct open-source equivalent | Video streaming data |
| MediaConvert | FFmpeg | Video transcoding |
| MediaLive | OBS Studio | Live video streaming |
| MediaPackage | No direct open-source equivalent | Video packaging and delivery |
| MediaStore | No direct open-source equivalent | Video storage |
| MediaTailor | No direct open-source equivalent | Video ad insertion |
| Elemental Appliances & Software | No direct open-source equivalent | Video processing |

### Machine Learning

| AWS Service | Open Source Tool | Purpose |
|-------------|-------------------|---------|
| Amazon SageMaker | TensorFlow, PyTorch | Machine learning model development |
| Amazon Augmented AI | No direct open-source equivalent | Human review of ML predictions |
| Amazon CodeGuru | SonarQube | Code quality and recommendations |
| Amazon DevOps Guru | No direct open-source equivalent | Operational insights and recommendations |
| Amazon Comprehend | spaCy | Natural language processing |
| Amazon Forecast | No direct open-source equivalent | Time series forecasting |
| Amazon Fraud Detector | No direct open-source equivalent | Fraud detection |
| Amazon Kendra | Elasticsearch | Enterprise search |
| Amazon Personalize | No direct open-source equivalent | Personalized recommendations |
| Amazon Polly | Festival, Google Text-to-Speech | Text-to-speech |
| Amazon Rekognition | OpenCV, Dlib | Image and video analysis |
| Amazon Textract | Tesseract | Document text extraction |
| Amazon Transcribe | DeepSpeech | Speech-to-text |
| Amazon Translate | OpenNMT | Language translation |
| AWS DeepComposer | No direct open-source equivalent | Music generation with AI |
| AWS DeepRacer | No direct open-source equivalent | Reinforcement learning |
| AWS Panorama | No direct open-source equivalent | Edge computer vision |
| Amazon Monitron | No direct open-source equivalent | Equipment monitoring |
| AWS HealthLake | No direct open-source equivalent | Health data management |
| Amazon Lookout for Vision | No direct open-source equivalent | Visual anomaly detection |
| Amazon Lookout for Equipment | No direct open-source equivalent | Equipment anomaly detection |
| Amazon Lookout for Metrics | No direct open-source equivalent | Anomaly detection in metrics |
| Amazon Lex | Rasa | Conversational AI |
| Amazon Comprehend Medical | No direct open-source equivalent | Medical text analysis |
| AWS HealthOmics | No direct open-source equivalent | Omics data management |
| Amazon Bedrock | No direct open-source equivalent | Foundation models for generative AI |

### Analytics

| AWS Service | Open Source Tool | Purpose |
|-------------|-------------------|---------|
| Athena | Presto | Interactive query service for S3 |
| Amazon Redshift | Apache Hive | Data warehousing |
| CloudSearch | Elasticsearch | Search service |
| Amazon OpenSearch Service | Elasticsearch | Search and analytics |
| Kinesis | Apache Kafka | Real-time data streaming |
| QuickSight | Metabase | Business intelligence and visualization |
| Data Pipeline | Apache Oozie | Data workflow management |
| AWS Data Exchange | No direct open-source equivalent | Data exchange marketplace |
| AWS Lake Formation | No direct open-source equivalent | Data lake management |
| MSK | Apache Kafka | Managed Kafka service |
| AWS Glue DataBrew | No direct open-source equivalent | Data preparation |
| Amazon FinSpace | No direct open-source equivalent | Financial data management |
| AWS Glue | Apache NiFi | Data integration and ETL |
| Amazon Data Firehose | No direct open-source equivalent | Data delivery |
| EMR | Apache Hadoop | Big data processing |
| AWS Clean Rooms | No direct open-source equivalent | Secure data collaboration |
| Amazon DataZone | No direct open-source equivalent | Data governance |
| AWS Entity Resolution | No direct open-source equivalent | Entity resolution |
| Managed Apache Flink | Apache Flink | Stream processing |

### Security, Identity, & Compliance

| AWS Service | Open Source Tool | Purpose |
|-------------|-------------------|---------|
| Resource Access Manager | No direct open-source equivalent | Resource sharing |
| Cognito | Keycloak | User authentication and management |
| Secrets Manager | HashiCorp Vault | Secrets management |
| GuardDuty | OSSEC | Threat detection |
| Amazon Inspector | OpenVAS | Vulnerability assessment |
| Amazon Macie | No direct open-source equivalent | Data privacy |
| IAM Identity Center | Keycloak | Identity management |
| Certificate Manager | Let's Encrypt | SSL/TLS certificate management |
| Key Management Service | HashiCorp Vault | Key management |
| CloudHSM | No direct open-source equivalent | Hardware security module |
| Directory Service | OpenLDAP | Directory management |
| WAF & Shield | ModSecurity | Web application firewall |
| AWS Firewall Manager | No direct open-source equivalent | Centralized firewall management |
| AWS Artifact | No direct open-source equivalent | Compliance reports |
| Detective | No direct open-source equivalent | Security investigation |
| AWS Signer | No direct open-source equivalent | Code signing |
| AWS Private Certificate Authority | No direct open-source equivalent | Private CA management |
| Security Hub | OpenSCAP | Security posture management |
| AWS Audit Manager | No direct open-source equivalent | Audit management |
| Security Lake | No direct open-source equivalent | Security data lake |
| Amazon Verified Permissions | No direct open-source equivalent | Fine-grained access control |
| AWS Payment Cryptography | No direct open-source equivalent | Payment data protection |
| IAM | Keycloak | Identity and access management |
| Cloud Financial Management | No direct open-source equivalent | Financial management |
| AWS Marketplace | No direct open-source equivalent | Software marketplace |
| AWS Billing Conductor | No direct open-source equivalent | Billing management |

### Front-end Web & Mobile

| AWS Service | Open Source Tool | Purpose |
|-------------|-------------------|---------|
| AWS Amplify | Firebase | Full-stack app development |
| AWS AppSync | Apollo GraphQL | Managed GraphQL service |
| Device Farm | Appium | Mobile app testing |
| Amazon Location Service | OpenStreetMap | Location-based services |

### Application Integration

| AWS Service | Open Source Tool | Purpose |
|-------------|-------------------|---------|
| Step Functions | Apache Airflow | Workflow automation |
| Amazon AppFlow | No direct open-source equivalent | Data integration |
| Amazon MQ | RabbitMQ | Managed message broker |
| Simple Notification Service (SNS) | Apache Kafka | Pub/Sub messaging |
| Simple Queue Service (SQS) | RabbitMQ | Message queuing |
| SWF | Apache Airflow | Workflow management |
| Managed Apache Airflow | Apache Airflow | Workflow orchestration |
| Amazon EventBridge | Apache Kafka | Event-driven architecture |
| AWS B2B Data Interchange | No direct open-source equivalent | Business data interchange |

### Business Applications

| AWS Service | Open Source Tool | Purpose |
|-------------|-------------------|---------|
| Amazon Connect | Asterisk | Cloud-based contact center |
| Amazon Chime | Jitsi Meet | Communication and collaboration |
| Amazon Simple Email Service (SES) | Mailgun | Email sending service |
| Amazon WorkDocs | Nextcloud | Document collaboration |
| Amazon WorkMail | Zimbra | Email and calendar service |
| AWS Supply Chain | No direct open-source equivalent | Supply chain management |
| AWS AppFabric | No direct open-source equivalent | Application integration |
| AWS Wickr | Signal | Secure messaging |
| Amazon Chime SDK | Jitsi Meet | Real-time communication |
| Amazon One Enterprise | No direct open-source equivalent | Biometric authentication |
| Amazon Pinpoint | SendGrid | Customer engagement |

### End User Computing

| AWS Service | Open Source Tool | Purpose |
|-------------|-------------------|---------|
| WorkSpaces | VMware Horizon | Virtual desktops |
| AppStream 2.0 | Apache Guacamole | Application streaming |
| WorkSpaces Secure Browser | No direct open-source equivalent | Secure browsing |
| WorkSpaces Thin Client | No direct open-source equivalent | Thin client management |

### Internet of Things

| AWS Service | Open Source Tool | Purpose |
|-------------|-------------------|---------|
| IoT Analytics | ThingsBoard | IoT data analysis |
| IoT Device Defender | No direct open-source equivalent | Device security |
| IoT Device Management | OpenRemote | Device management |
| IoT Greengrass | EdgeX Foundry | Edge computing |
| IoT SiteWise | No direct open-source equivalent | Industrial IoT |
| IoT Core | Mosquitto | Device connectivity |
| IoT Events | No direct open-source equivalent | Event detection |
| AWS IoT FleetWise | No direct open-source equivalent | Fleet management |
| IoT TwinMaker | No direct open-source equivalent | Digital twins |

### Game Development

| AWS Service | Open Source Tool | Purpose |
|-------------|-------------------|---------|
| Amazon GameLift | No direct open-source equivalent | Game server hosting |

This table aligns each AWS service with its closest open-source tool equivalents and their purposes. Let me know if you need any more details or adjustments!
