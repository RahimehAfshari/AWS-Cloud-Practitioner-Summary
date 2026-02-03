# AWS Cloud Practitioner Essentials – Summary

## Cloud Computing & AWS Benefits
- Trade fixed expense for variable expense  
- Benefit from massive economies of scale  
- Stop guessing capacity  
- Increase speed and agility  
- Stop spending money on data centers  
- Go global in minutes  

**Cloud Concepts:**  
- High availability (Availability Zone)  
- Fault tolerance  

**AWS Shared Responsibility:**  
- **AWS:** Security *of* the cloud  
- **Customer:** Security *in* the cloud (encrypt client-side data, manage OS patches)  

---

## Compute & EC2
- Amazon Elastic Compute Cloud (EC2): flexible, cost-effective, quick  
- Vertical scaling, full networking control, choose instance type & OS  
- **Multitenancy:** sharing hardware between VMs while maintaining isolation  
- **Memory-optimized instances:** high-memory workloads, real-time analytics  
- **APIs:** AWS Management Console, CLI, SDK  
- **Amazon Machine Image (AMI):** pre-configured OS + software for consistent instance launches  

---

## Key AWS Services
- Elastic Load Balancing (ELB)  
- Amazon SQS & SNS  
- Elastic Container Service (ECS), EKS, ECR  
- Infrastructure as Code (IaC)  
- Amazon VPC, Network ACL, DNS  
- Storage: EBS, S3, EFS  
- Amazon RDS & NoSQL databases  

---

## EC2 & Pricing
- Create EC2 instance: choose AMI, instance type, storage  
- Pricing options: Dedicated Host, Spot, Savings Plans, On-Demand, Reserved  
- Scalability: scale up/out  
- Elasticity: auto-scale based on demand  

---

## Serverless & Containers
- **Lambda:** run code without managing servers, auto-scale, pay per execution  
- **Docker:** platform for building, testing, deploying apps  
- **Elastic Beanstalk:** managed deployment + scaling for web apps  
- **AWS Batch:** manage batch workloads automatically  
- **Lightsail:** simple VPS + storage + DB for small businesses  
- **Outposts:** hybrid cloud, on-prem AWS infrastructure  

---

## Networking & Global Infrastructure
- Key factors when choosing regions: compliance, proximity, feature availability, pricing  
- High availability, agility, elasticity  
- AWS Regions, Availability Zones, Edge Locations  
- Connect: Client VPN, Site-to-Site VPN, PrivateLink, Direct Connect  
- Route 53, CloudFront, Global Accelerator  

---

## Storage
- **Block Storage:** EC2 Instance Store, EBS, EBS Snapshots  
- **Object Storage:** S3 (unlimited, encrypted, lifecycle rules, bucket policies)  
- **File Storage:** EFS (elastic, multi-AZ, shared access)  
- **Hybrid Storage:** AWS Storage Gateway  

---

## Database
- **Shared Responsibility:** fully managed, managed, unmanaged  
- **RDS:** managed relational DB  
- **Aurora:** cost-effective, high performance  
- **NoSQL / DynamoDB:** flexible schema, fast performance  
- **ElastiCache:** in-memory caching  
- **DocumentDB:** JSON data, frequent schema changes  

---

## Machine Learning & AI
- **Tier 1 (pre-built AI services):** Comprehend, Polly, Transcribe, Translate, Rekognition, Textract, Lex, Personalize  
- **Tier 2:** SageMaker AI  
- **Tier 3:** ML frameworks & infrastructure  

---

## Data Pipeline & Analytics
- Kinesis, Data Firehose, S3, Redshift, Glue, EMR, Athena, QuickSight, OpenSearch  

---

## Security & Compliance
- **Authentication & Authorization**  
- **IAM:** root, groups, users, roles  
- DDoS → AWS Shield, WAF  
- Data protection: KMS, Macie, Certificate Manager (ACM)  

---


