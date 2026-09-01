# CloudNova Technologies - Client Recommendations

## Client A - Startup Company

### Recommended Cloud Platform: Amazon Web Services (AWS)

AWS is recommended for the startup because it provides a broad range of services that can support a mobile application from its initial launch through rapid growth. The startup can begin with relatively small resources and scale them as the number of users increases, helping control costs during the early stages. AWS also provides serverless and managed services that can reduce the amount of infrastructure the startup needs to maintain. Its large ecosystem gives the company flexibility to add databases, authentication, storage, monitoring, and other capabilities as the application grows.

### Recommended Services

1. **Amazon EC2** - Provides scalable virtual servers for application workloads.
2. **Amazon S3** - Provides scalable object storage for images, files, backups, and application data.
3. **Amazon RDS** - Provides managed relational databases for application data.
4. **Amazon Cognito** - Provides user authentication and identity management for mobile and web applications.
5. **AWS Lambda** - Provides serverless computing so the company can run application code without managing servers.

---

## Client B - University

### Recommended Cloud Platform: Microsoft Azure

Microsoft Azure is the best choice for the university because it already uses Windows Server, Microsoft 365, and Active Directory. Azure provides strong integration with Microsoft's identity and enterprise technologies, making migration and management easier. The university can use Microsoft Entra ID to extend its existing identity environment and can connect on-premises systems with Azure services. Azure also supports hybrid-cloud architectures, allowing the university to gradually migrate services instead of moving everything at once.

### Recommended Services

1. **Azure Virtual Machines** - Provides Windows and Linux virtual machines for migrating server workloads.
2. **Microsoft Entra ID** - Provides cloud identity and access management and integrates with Microsoft's identity ecosystem.
3. **Azure SQL Database** - Provides a managed relational database service for applications and university systems.
4. **Azure Virtual Network** - Provides private networking for Azure resources and connectivity to on-premises systems.
5. **Azure Backup** - Provides backup capabilities for protecting important university data and workloads.

---

## Client C - AI Research Company

### Recommended Cloud Platform: Google Cloud Platform (GCP)

Google Cloud is recommended because the company specializes in Artificial Intelligence and Machine Learning and requires high-performance computing. Google Cloud provides specialized AI and machine-learning infrastructure, including hardware accelerators and services designed for large-scale AI workloads. Google Cloud also provides Vertex AI for developing, training, deploying, and managing machine-learning models. Its strong data-processing capabilities can help the research company process large datasets efficiently.

### Recommended Services

1. **Vertex AI** - Provides a platform for developing, training, deploying, and managing machine-learning models.
2. **Compute Engine** - Provides configurable virtual machines and high-performance computing resources.
3. **Cloud TPU** - Provides Google's specialized Tensor Processing Units for accelerating machine-learning workloads.
4. **Google Kubernetes Engine (GKE)** - Provides managed Kubernetes for containerized AI and ML applications.
5. **Cloud Storage** - Provides scalable object storage for large datasets, models, and research files.

---

## Client D - Global E-Commerce Company

### Recommended Cloud Platform: Amazon Web Services (AWS)

AWS is recommended for the global e-commerce company because it provides extensive global infrastructure and services designed for highly available and scalable applications. The company can distribute workloads across multiple Availability Zones and Regions to improve availability and resilience. AWS Auto Scaling and Elastic Load Balancing can automatically adjust application capacity and distribute traffic as demand changes. AWS also provides services for databases, content delivery, storage, monitoring, and security, making it suitable for a large international e-commerce platform.

### Recommended Services

1. **Amazon EC2 Auto Scaling** - Automatically adjusts the number of EC2 instances according to application demand.
2. **Elastic Load Balancing (ELB)** - Distributes incoming application traffic across multiple resources.
3. **Amazon RDS** - Provides managed relational databases for e-commerce applications.
4. **Amazon CloudFront** - Delivers web content through a global content delivery network.
5. **Amazon S3** - Provides scalable storage for product images, documents, backups, and other objects.
6. **Amazon Route 53** - Provides scalable DNS and domain-name routing services.

---

## Summary

| Client | Recommended Platform | Main Reason |
|---|---|---|
| Client A - Startup | AWS | Broad services, scalability, and flexible infrastructure |
| Client B - University | Microsoft Azure | Strong integration with Microsoft technologies |
| Client C - AI Research | Google Cloud | Strong AI/ML and high-performance computing capabilities |
| Client D - Global E-Commerce | AWS | Global infrastructure, high availability, and automatic scaling |

## Final Recommendation

The four clients have different requirements, so there is no single cloud provider that is best for every scenario. AWS is recommended for the startup and global e-commerce company because of its broad services, scalability, and global infrastructure. Azure is the best fit for the university because of its Microsoft ecosystem integration. Google Cloud is the best fit for the AI research company because of its strong AI, machine-learning, data, and high-performance computing capabilities.




## Checkpoint 6 – Multi-Cloud Decision Matrix

| Business Requirement | Recommended Platform | Justification |
|---|---|---|
| Startup Company | AWS | Widest range of services, generous free-tier/startup credit programs (AWS Activate), and pay-as-you-go pricing that scales with limited upfront budget. |
| Enterprise Organization | Azure | Deep integration with existing enterprise tools (Active Directory, Office 365), strong compliance/governance features, and flexible enterprise agreements/licensing. |
| Microsoft Environment | Azure | Native, first-party integration with Windows Server, .NET, SQL Server, and Active Directory; simplest hybrid-cloud path for Microsoft-based stacks. |
| AI / Machine Learning | Google Cloud Platform (GCP) | Vertex AI, TPUs, and BigQuery ML give strong native ML tooling; GCP is widely regarded as the leader in data analytics and AI infrastructure. |
| Kubernetes Deployment | Google Cloud Platform (GCP) | Kubernetes originated at Google; GKE is the most mature managed Kubernetes offering with the tightest upstream integration and automated cluster management. |
| Global Web Application | AWS | Largest number of global regions and edge locations (via CloudFront), giving the broadest low-latency reach for a worldwide user base. |
