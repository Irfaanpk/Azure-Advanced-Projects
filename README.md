<div align="center">

<img src="./assets/z2h.jpeg" alt="Azure Advanced Projects Banner">

<br><br>

<img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white">
<img src="https://img.shields.io/badge/Level-Advanced-purple?style=for-the-badge">
<img src="https://img.shields.io/badge/Networking-Networking-blue?style=for-the-badge&logo=microsoftazure&logoColor=white">
<img src="https://img.shields.io/badge/Security-Security-red?style=for-the-badge&logo=microsoftazure&logoColor=white">
<img src="https://img.shields.io/badge/DevOps-CI%2FCD-0078D4?style=for-the-badge">
<img src="https://img.shields.io/badge/IaC-Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white">

<br>

<img src="https://img.shields.io/badge/Contributions-Welcome-brightgreen?style=for-the-badge">

</div>

<div align="center">

# Azure Advanced Projects

### From cloud fundamentals to enterprise-grade Azure architecture — hands-on projects, automation, security, and real-world DevOps practices.

</div>

---

## About This Repository

**Azure Advanced Projects** is a structured, hands-on repository focused on designing, deploying, securing, and managing advanced solutions on Microsoft Azure.

Each project is organized into its own folder with a dedicated `README.md` covering detailed explanations, architecture diagrams, Azure Portal walkthroughs, Azure CLI commands, implementation steps, validation procedures, troubleshooting, and cleanup instructions.

The repository focuses on practical cloud engineering scenarios, enterprise architecture, infrastructure automation, security, and DevOps.

By working through these projects, you will learn to:

- Design secure, scalable, and highly available Azure architectures.
- Implement advanced networking using Hub-and-Spoke, Azure Firewall, Private Endpoints, and hybrid connectivity.
- Manage identities and access using Microsoft Entra ID, Azure RBAC, and Managed Identities.
- Secure Azure resources using Key Vault, Defender for Cloud, and Azure Policy.
- Deploy and manage compute, storage, and database services.
- Automate infrastructure provisioning using Terraform.
- Build CI/CD pipelines and implement DevSecOps practices.
- Deploy and manage containerized applications using Azure Kubernetes Service (AKS).
- Implement monitoring, backup, disaster recovery, and cost optimization.
- Integrate Azure with hybrid and multi-cloud environments.

---

## Table of Contents

## 1. Advanced Networking

This section covers advanced Azure networking, including hub-and-spoke architecture, Azure Firewall, private connectivity, hybrid networking, and global traffic management.

📂 **[Explore → Advanced Networking](./01.%20Advanced%20Networking/)**

| # | Sub-Topic | Description |
|---|-----------|-------------|
| 1.1 | [Hub and Spoke with Azure Firewall](./01.%20Advanced%20Networking/Hub%20and%20Spoke%20with%20Azure%20Firewall/) | Hub-and-spoke architecture, Azure Firewall, routing, and network segmentation |
| 1.2 | [Private Endpoints and Private DNS](./01.%20Advanced%20Networking/Private%20Endpoints%20and%20Private%20DNS/) | Private Link, private endpoints, and private DNS zones |
| 1.3 | [Hybrid Connectivity with VPN](./01.%20Advanced%20Networking/Hybrid%20Connectivity%20with%20VPN/) | Azure VPN Gateway and hybrid network connectivity |
| 1.4 | [Global Load Balancing and WAF](./01.%20Advanced%20Networking/Global%20Load%20Balancing%20and%20WAF/) | Azure Front Door, global routing, and Web Application Firewall |

---

## 2. Compute and Application Hosting

This section covers Azure compute services, application hosting, deployment strategies, availability, and virtual machine automation.

📂 **[Explore → Compute and Application Hosting](./02.%20Compute%20and%20Application%20Hosting/)**

| # | Sub-Topic | Description |
|---|-----------|-------------|
| 2.1 | [High Availability Web Application](./02.%20Compute%20and%20Application%20Hosting/High%20Availability%20Web%20Application/) | Application availability, load balancing, health probes, and resilient application architecture |
| 2.2 | [App Service Deployment Slots](./02.%20Compute%20and%20Application%20Hosting/App%20Service%20Deployment%20Slots/) | Deployment slots, staging environments, configuration settings, and application swaps |
| 2.3 | [Automated VM Operations](./02.%20Compute%20and%20Application%20Hosting/Automated%20VM%20Operations/) | Automated VM start and stop, scheduling, and operational tasks |

---

## 3. Storage and Data Services

This section covers secure Azure storage, disaster recovery, private database connectivity, and globally distributed data services.

📂 **[Explore → Storage and Data Services](./03.%20Storage%20and%20Data%20Services/)**

| # | Sub-Topic | Description |
|---|-----------|-------------|
| 3.1 | [Secure Storage Platform](./03.%20Storage%20and%20Data%20Services/Secure%20Storage%20Platform/) | Storage account security, encryption, network restrictions, and access control |
| 3.2 | [Cross Region Storage Recovery](./03.%20Storage%20and%20Data%20Services/Cross%20Region%20Storage%20Recovery/) | Storage redundancy, replication, and recovery planning |
| 3.3 | [Private Azure SQL Database](./03.%20Storage%20and%20Data%20Services/Private%20Azure%20SQL%20Database/) | Azure SQL Database, private endpoints, private DNS, and secure connectivity |
| 3.4 | [Cosmos DB Global Distribution](./03.%20Storage%20and%20Data%20Services/Cosmos%20DB%20Global%20Distribution/) | Azure Cosmos DB, regional replication, consistency levels, and global distribution |

---

## 4. Identity and Security

This section covers enterprise identity governance, workload authentication, secrets management, security posture, and Azure governance policies.

📂 **[Explore → Identity and Security](./04.%20Identity%20and%20Security/)**

| # | Sub-Topic | Description |
|---|-----------|-------------|
| 4.1 | [Enterprise Identity Governance](./04.%20Identity%20and%20Security/Enterprise%20Identity%20Governance/) | Microsoft Entra ID, role assignments, access reviews, and identity governance |
| 4.2 | [Managed Identity Integration](./04.%20Identity%20and%20Security/Managed%20Identity%20Integration/) | System-assigned and user-assigned managed identities for passwordless authentication |
| 4.3 | [Key Vault Security](./04.%20Identity%20and%20Security/Key%20Vault%20Security/) | Secrets, keys, certificates, access control, and secure application integration |
| 4.4 | [Defender for Cloud Posture Management](./04.%20Identity%20and%20Security/Defender%20for%20Cloud%20Posture%20Management/) | Security recommendations, secure score, and cloud security posture management |
| 4.5 | [Azure Policy Governance](./04.%20Identity%20and%20Security/Azure%20Policy%20Governance/) | Policy definitions, initiatives, assignments, and compliance evaluation |

---

## 5. Infrastructure as Code

This section covers repeatable Azure infrastructure deployment using Terraform, reusable modules, environment separation, and policy validation.

📂 **[Explore → Infrastructure as Code](./05.%20Infrastructure%20as%20Code/)**

| # | Sub-Topic | Description |
|---|-----------|-------------|
| 5.1 | [Azure Landing Zone](./05.%20Infrastructure%20as%20Code/Azure%20Landing%20Zone/) | Landing zone architecture, subscription organization, governance, and shared services |
| 5.2 | [Reusable Terraform Modules](./05.%20Infrastructure%20as%20Code/Reusable%20Terraform%20Modules/) | Modular Terraform design, variables, outputs, and reusable infrastructure components |
| 5.3 | [Multi Environment Infrastructure](./05.%20Infrastructure%20as%20Code/Multi%20Environment%20Infrastructure/) | Development, testing, and production environments managed using Terraform |
| 5.4 | [Terraform CI/CD](./05.%20Infrastructure%20as%20Code/Terraform%20CI%2FCD/) | Automated formatting, validation, planning, approvals, and deployment |
| 5.5 | [Policy as Code](./05.%20Infrastructure%20as%20Code/Policy%20as%20Code/) | Infrastructure policy validation, compliance checks, and deployment guardrails |

---

## 6. Azure DevOps and CI/CD

This section covers automated build and deployment pipelines, secure container delivery, and passwordless authentication.

📂 **[Explore → Azure DevOps and CI/CD](./06.%20Azure%20DevOps%20and%20CI%2FCD/)**

| # | Sub-Topic | Description |
|---|-----------|-------------|
| 6.1 | [End to End CI/CD Pipeline](./06.%20Azure%20DevOps%20and%20CI%2FCD/End%20to%20End%20CI%2FCD%20Pipeline/) | Source control, build automation, testing, artifact management, and application deployment |
| 6.2 | [Secure Container Delivery](./06.%20Azure%20DevOps%20and%20CI%2FCD/Secure%20Container%20Delivery/) | Container image building, vulnerability scanning, Azure Container Registry, and secure deployment |
| 6.3 | [Passwordless Pipeline Authentication](./06.%20Azure%20DevOps%20and%20CI%2FCD/Passwordless%20Pipeline%20Authentication/) | Workload identity federation, service connections, and secretless authentication |

---

## 7. Containers and Kubernetes

This section covers Azure Kubernetes Service, including cluster architecture, ingress, private networking, observability, GitOps, and secrets management.

📂 **[Explore → Containers and Kubernetes](./07.%20Containers%20and%20Kubernetes/)**

| # | Sub-Topic | Description |
|---|-----------|-------------|
| 7.1 | [Production Ready AKS](./07.%20Containers%20and%20Kubernetes/Production%20Ready%20AKS/) | AKS architecture, node pools, identity, scaling, availability, and cluster security |
| 7.2 | [AKS Ingress and HTTPS](./07.%20Containers%20and%20Kubernetes/AKS%20Ingress%20and%20HTTPS/) | Ingress controllers, TLS certificates, and HTTPS configuration |
| 7.3 | [Private AKS Networking](./07.%20Containers%20and%20Kubernetes/Private%20AKS%20Networking/) | Private clusters, network integration, private DNS, and secure API access |
| 7.4 | [AKS Observability](./07.%20Containers%20and%20Kubernetes/AKS%20Observability/) | Container Insights, metrics, logs, monitoring, and alerting |
| 7.5 | [AKS GitOps with Flux](./07.%20Containers%20and%20Kubernetes/AKS%20GitOps%20with%20Flux/) | GitOps workflows, Flux reconciliation, and configuration management |
| 7.6 | [AKS Secrets with Key Vault](./07.%20Containers%20and%20Kubernetes/AKS%20Secrets%20with%20Key%20Vault/) | Key Vault integration, workload identity, and secure application configuration |

---

## 8. Monitoring and Reliability

This section covers centralized monitoring, automated incident response, backup and recovery, disaster recovery, and cost optimization.

📂 **[Explore → Monitoring and Reliability](./08.%20Monitoring%20and%20Reliability/)**

| # | Sub-Topic | Description |
|---|-----------|-------------|
| 8.1 | [Centralized Monitoring Platform](./08.%20Monitoring%20and%20Reliability/Centralized%20Monitoring%20Platform/) | Azure Monitor, Log Analytics, diagnostic settings, dashboards, and centralized logging |
| 8.2 | [Automated Incident Response](./08.%20Monitoring%20and%20Reliability/Automated%20Incident%20Response/) | Alert rules, action groups, automated remediation, and incident notifications |
| 8.3 | [Azure Backup and Restore](./08.%20Monitoring%20and%20Reliability/Azure%20Backup%20and%20Restore/) | Recovery Services vaults, backup policies, restore operations, and recovery validation |
| 8.4 | [Disaster Recovery Exercise](./08.%20Monitoring%20and%20Reliability/Disaster%20Recovery%20Exercise/) | Recovery objectives, failover planning, and disaster recovery testing |
| 8.5 | [Cost Optimization Automation](./08.%20Monitoring%20and%20Reliability/Cost%20Optimization%20Automation/) | Cost analysis, budgets, scheduled operations, and cost control automation |

---

## 9. Hybrid and Multi-Cloud

This section covers hybrid resource management, cloud-to-cloud connectivity, multi-cloud infrastructure provisioning, and centralized logging.

📂 **[Explore → Hybrid and Multi-Cloud](./09.%20Hybrid%20and%20Multi-Cloud/)**

| # | Sub-Topic | Description |
|---|-----------|-------------|
| 9.1 | [Azure Arc Hybrid Management](./09.%20Hybrid%20and%20Multi-Cloud/Azure%20Arc%20Hybrid%20Management/) | Azure Arc-enabled resources, hybrid governance, inventory, and centralized management |
| 9.2 | [AWS to Azure Connectivity](./09.%20Hybrid%20and%20Multi-Cloud/AWS%20to%20Azure%20Connectivity/) | Cross-cloud networking, secure connectivity, routing, and access controls |
| 9.3 | [Multi Cloud Terraform](./09.%20Hybrid%20and%20Multi-Cloud/Multi%20Cloud%20Terraform/) | Terraform-based infrastructure management across Azure and AWS |
| 9.4 | [Centralized Multi Cloud Logging](./09.%20Hybrid%20and%20Multi-Cloud/Centralized%20Multi%20Cloud%20Logging/) | Centralized log collection, monitoring integration, and cross-cloud operational visibility |

---

## 10. Enterprise Capstone Projects

This section combines multiple Azure services and engineering practices into larger end-to-end projects.

📂 **[Explore → Enterprise Capstone Projects](./10.%20Enterprise%20Capstone%20Projects/)**

| # | Sub-Topic | Description |
|---|-----------|-------------|
| 10.1 | [Enterprise Azure Landing Zone](./10.%20Enterprise%20Capstone%20Projects/Enterprise%20Azure%20Landing%20Zone/) | Enterprise-scale subscriptions, networking, governance, identity, and shared platform services |
| 10.2 | [Secure Three Tier Application](./10.%20Enterprise%20Capstone%20Projects/Secure%20Three%20Tier%20Application/) | Multi-tier application architecture with network segmentation, secure data access, and monitoring |
| 10.3 | [End to End Azure DevSecOps Platform](./10.%20Enterprise%20Capstone%20Projects/End%20to%20End%20Azure%20DevSecOps%20Platform/) | Infrastructure as code, CI/CD, security scanning, secrets management, and automated deployment |
| 10.4 | [Resilient Global Application](./10.%20Enterprise%20Capstone%20Projects/Resilient%20Global%20Application/) | Global traffic distribution, application resilience, regional recovery, and monitoring |
| 10.5 | [Governed Multi Environment Platform](./10.%20Enterprise%20Capstone%20Projects/Governed%20Multi%20Environment%20Platform/) | Environment separation, policy enforcement, access controls, and reusable infrastructure |
| 10.6 | [Automated Cloud Operations Platform](./10.%20Enterprise%20Capstone%20Projects/Automated%20Cloud%20Operations%20Platform/) | Monitoring, operational automation, resource lifecycle management, and cost controls |

---



