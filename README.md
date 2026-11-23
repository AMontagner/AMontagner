# Hey, I’m Angelo Montagner 👋

**Senior DevOps Engineer · AI Platform Engineering**

I’m a Senior DevOps Engineer with a software engineering background and 10+ years in enterprise environments. I build and secure Azure and AWS infrastructure, automate software releases, and lead production incident response. My current focus is applying those practices to Kubernetes-based AI platforms.

Orlando, FL · English and Spanish

[Selected experience](#selected-experience) · [Technical stack](#technical-stack) · [AI platform focus](#ai-platform-focus) · [Projects and research](#projects-and-research) · [Certifications](#certifications)

## Selected experience

- Designed AKS clusters for microservices serving 4M+ daily users, moving releases from weekly to multiple times a day while maintaining 99.97% uptime. Reduced incident MTTR from 47 to 12 minutes with Dynatrace monitoring and Splunk-to-PagerDuty alerting. Standardized Azure Pipelines and Terraform releases, migrated Bicep-managed resources to Terraform, and integrated Wiz CLI into Jenkins and Azure Pipelines.
- Cut infrastructure deployments from 45 minutes to under 5 minutes with GitHub Actions. Migrated on-premises applications to Azure, implemented network segmentation and shared API Management, and rolled out HashiCorp Vault across 50+ microservices with 30-day credential rotation.
- Migrated legacy .NET monoliths to containerized microservices and improved resource utilization by 60%. Reduced annual AWS infrastructure costs by $100K through rightsizing, autoscaling, Spot instances, and Lambda. Operated ECS workloads with CloudWatch and configured cross-region RDS replication for disaster recovery.

## Technical stack

- **Cloud and containers** — Azure, AWS, AKS, EKS, ECS, Azure Container Apps, Docker, Argo CD
- **Infrastructure and delivery** — Terraform, Bicep/ARM, AWS CloudFormation, AWS CDK, Ansible, Jenkins, Azure Pipelines, GitHub Actions
- **Security and identity** — Wiz, Prisma Cloud, Microsoft Defender for Cloud, Entra ID, Azure RBAC, AWS IAM, HashiCorp Vault
- **Observability and automation** — Splunk, Dynatrace, Datadog, New Relic, Python, PowerShell, C#/.NET Core

## AI platform focus

I’m exploring how to operate model inference on Kubernetes. I’m particularly interested in GPU scheduling and utilization, versioned model deployments with rollback, and monitoring for latency, throughput, and GPU saturation.

- **[Fieldnotes — Hybrid Search RAG](https://github.com/AMontagner/hybrid-search-rag)** — A deployed document search and Q&A app with a FastAPI backend, web UI, and Docker packaging. Its cloud mode combines Pinecone vector search with BM25 using reciprocal rank fusion, reranks results with Cohere, and uses Claude to generate answers with source citations.


## Projects and research

- **[Kubernetes Rollout Recovery](https://github.com/AMontagner/kubernetes-rollout-recovery)** — A reproducible Kubernetes failure and recovery workflow that shows how to diagnose stalled deployments, inspect Pod events, and verify a rollback.
- **[Availability SLO Checker](https://github.com/AMontagner/availability-slo-checker)** — A Python CLI that turns request and failure counts into availability, error-budget burn rate, and remaining error budget. It returns a failing exit code when the SLO is missed, so it can run in CI.
- **[NetCoreAppDeployment](https://github.com/AMontagner/NetCoreAppDeployment)** — My .NET application deployment repository.
- **[ZappyApply](https://zappyapply.com)** — A browser-based project I built to streamline job applications.
- **D.R.O.N.E.S.** — A Java Android app for DJI Phantom drones with flight controls and waypoint mission integration. [App demo](https://www.youtube.com/watch?v=l-W9j8QPAhs) · [Flight test](https://www.youtube.com/watch?v=yQ9hOt_C9mM) · [Critical design review](https://docs.google.com/presentation/d/1VMN4eEQsCah8OuNE7A0J4Y-3l-ItyDGlp9vXd8OrSeI/edit?usp=sharing)
- **Lockheed Martin engineering work** — Developed C++ simulation software and automated manual tests with Python. [Public program overview](https://www.youtube.com/watch?v=h449oIjg2kY)
- **UCF honors thesis** — Used R to study socioeconomic influences on Hispanic voter party affiliation. [Published thesis](https://stars.library.ucf.edu/honorstheses1990-2015/1815/)

## Certifications

- **Azure** — DevOps Engineer Expert (AZ-400), Azure Administrator (AZ-104), Azure Developer (AZ-204), Azure Fundamentals (AZ-900), Security, Compliance, and Identity Fundamentals (SC-900)
- **AWS** — DevOps Engineer – Professional, Solutions Architect – Associate, Cloud Practitioner
- **Kubernetes and Docker** — Certified Kubernetes Administrator (CKA), Docker Certified Associate (DCA)
- **HashiCorp** — Terraform Associate, Vault Associate

## Education

**University of Central Florida** · B.S. in Computer Science and B.A. in Political Science · Magna Cum Laude
