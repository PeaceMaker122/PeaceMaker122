# Stiaan Terblanche

🏪 Retail Business Owner turned Cloud Engineer | 2x AWS Certified Professional

## About Me

I spent 7 years running a retail business and a nationwide e-commerce operation before moving into cloud. It taught me to solve real problems under real constraints: budget, time, and things breaking at the worst moment. I bring that same ownership mindset to cloud, with a focus on security and AI: infrastructure that is secure by design, cost-aware, and tested by breaking it on purpose, and AI that supports human decisions instead of replacing them.

My portfolio mirrors real consulting engagements, not isolated tutorials. Every project comes with architecture diagrams, a decisions log, and evidence.

## 🛠️ Technical Expertise

- **Cloud Security:** ![least privilege IAM](https://img.shields.io/badge/-Least_privilege_IAM-1f6feb?style=flat) ![MFA enforcement](https://img.shields.io/badge/-MFA_enforcement-1f6feb?style=flat) ![network segmentation](https://img.shields.io/badge/-Network_segmentation-1f6feb?style=flat) ![Secrets Manager](https://img.shields.io/badge/-Secrets_Manager-1f6feb?style=flat) ![OIDC short lived credentials](https://img.shields.io/badge/-OIDC_short_lived_credentials-1f6feb?style=flat) ![GuardDuty](https://img.shields.io/badge/-GuardDuty-1f6feb?style=flat)
- **AI in the Cloud:** ![Amazon Bedrock](https://img.shields.io/badge/-Amazon_Bedrock-1f6feb?style=flat) ![PR security review](https://img.shields.io/badge/-PR_security_review-1f6feb?style=flat) ![template review](https://img.shields.io/badge/-Template_review-1f6feb?style=flat) ![incident triage](https://img.shields.io/badge/-Incident_triage-1f6feb?style=flat)
- **Infrastructure as Code:** ![Terraform](https://img.shields.io/badge/-Terraform-1f6feb?style=flat) ![AWS CDK](https://img.shields.io/badge/-AWS_CDK-1f6feb?style=flat) ![TypeScript](https://img.shields.io/badge/-TypeScript-1f6feb?style=flat) ![CloudFormation](https://img.shields.io/badge/-CloudFormation-1f6feb?style=flat)
- **DevOps & Automation:** ![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-1f6feb?style=flat) ![CI/CD](https://img.shields.io/badge/-CI%2FCD-1f6feb?style=flat) ![staging and production pipelines](https://img.shields.io/badge/-Staging_and_production_pipelines-1f6feb?style=flat) ![tested rollback](https://img.shields.io/badge/-Tested_rollback-1f6feb?style=flat)
- **Containers:** ![Docker](https://img.shields.io/badge/-Docker-1f6feb?style=flat) ![ECS](https://img.shields.io/badge/-ECS-1f6feb?style=flat) ![Fargate](https://img.shields.io/badge/-Fargate-1f6feb?style=flat) ![ECS Service Connect](https://img.shields.io/badge/-ECS_Service_Connect-1f6feb?style=flat)
- **Observability:** ![CloudWatch](https://img.shields.io/badge/-CloudWatch-1f6feb?style=flat) ![Container Insights](https://img.shields.io/badge/-Container_Insights-1f6feb?style=flat) ![EventBridge](https://img.shields.io/badge/-EventBridge-1f6feb?style=flat) ![SNS](https://img.shields.io/badge/-SNS-1f6feb?style=flat) ![Lambda health checks](https://img.shields.io/badge/-Lambda_health_checks-1f6feb?style=flat)
- **Cloud Platforms:** ![AWS](https://img.shields.io/badge/-AWS-1f6feb?style=flat) ![EC2](https://img.shields.io/badge/-EC2-1f6feb?style=flat) ![S3](https://img.shields.io/badge/-S3-1f6feb?style=flat) ![RDS](https://img.shields.io/badge/-RDS-1f6feb?style=flat) ![Aurora](https://img.shields.io/badge/-Aurora-1f6feb?style=flat) ![DynamoDB](https://img.shields.io/badge/-DynamoDB-1f6feb?style=flat) ![VPC](https://img.shields.io/badge/-VPC-1f6feb?style=flat) ![Lambda](https://img.shields.io/badge/-Lambda-1f6feb?style=flat) ![CloudFront](https://img.shields.io/badge/-CloudFront-1f6feb?style=flat) ![Route 53](https://img.shields.io/badge/-Route_53-1f6feb?style=flat)
- **Cloud Migration:** ![multi AZ](https://img.shields.io/badge/-Multi_AZ-1f6feb?style=flat) ![three tier architecture](https://img.shields.io/badge/-Three_tier_architecture-1f6feb?style=flat) ![legacy modernisation](https://img.shields.io/badge/-Legacy_modernisation-1f6feb?style=flat)

## 🏆 Certifications

- [AWS Certified Cloud Practitioner](https://www.credly.com/badges/683a7039-9c43-4a23-abcb-07c405b9cd72/public_url)
- [AWS Certified Solutions Architect – Associate](https://www.credly.com/badges/4f450030-f867-47d5-b328-cf65bc7a37fd/public_url)
- [Cloud Engineering Academy Graduate](https://cloudengineeracademy.io/)

## 🏅 Badges & Achievements

<p align="left">
  <a href="https://www.credly.com/badges/683a7039-9c43-4a23-abcb-07c405b9cd72/public_url">
    <img src="aws-certified-cloud-practitioner.png" width="150" height="150" alt="AWS Certified Cloud Practitioner">
  </a>
  <a href="https://www.credly.com/badges/4f450030-f867-47d5-b328-cf65bc7a37fd/public_url">
    <img src="aws-certified-solutions-architect-associate.png" width="150" height="150" alt="AWS Certified Solutions Architect Associate">
  </a>
  <a href="https://cloudengineeracademy.io/">
    <img src="academy-badge.png" width="150" height="150" alt="Cloud Engineering Academy Graduate">
  </a>
</p>

## 🤝 Open to Collaborate On

- Cloud infrastructure & IaC projects
- Cloud security and IAM design
- DevOps automation
- Ethical AI/ML on cloud platforms

⚡ **Fun fact:** Running a retail business for 7 years means I've already spent years thinking about uptime, customer trust, and what happens when a "small" failure cascades - turns out that's basically the job description for cloud architecture too.

## Completed Projects

### 🛒 [ShopMesh: Containerized Microservices Platform](https://github.com/PeaceMaker122/05-ShopMesh-Containerized-Microservices)
A containerized microservices platform that decomposes a coupled product catalog and shopping cart application into independently deployable and scalable Node.js services. Docker Compose supports local multi-container development, while AWS CDK provisions the production platform on ECS Fargate with private service-to-service communication through ECS Service Connect. Catalog owns product data in Aurora Serverless v2 PostgreSQL, Cart owns cart data in DynamoDB, and Secrets Manager handles database credentials without hardcoding them.

The platform uses a single HTTPS Application Load Balancer with path-based routing, private subnets for ECS tasks and databases, and ECR image scanning. GitHub Actions provides CI/CD with short-lived OIDC credentials, building and pushing only the affected service image through separate staging and production workflows. CloudWatch logs, Container Insights, alarms, EventBridge, a Lambda triage function, Amazon Bedrock, and SNS provide human-reviewed operational feedback. Failure testing deliberately triggered an unhealthy deployment and an application alarm, proving both ECS circuit-breaker rollback and the alarm-to-AI-triage notification path.

### ⚙️ [CloudPipe: CI/CD Pipeline Automation](https://github.com/PeaceMaker122/04-CloudPipe-Automation)
A DevOps consulting case study for a small web development company whose developers deployed changes by manually uploading files to production - slow, error-prone, and stressful. This project replaces that workflow with a fully automated CI/CD pipeline: code pushed to GitHub is automatically reviewed, deployed to a private staging environment, and promoted to production only on merge to `main`, with the merge acting as the promotion gate.

All infrastructure is defined as code with AWS CDK. GitHub Actions authenticates to AWS via OIDC instead of long-lived access keys, with three tightly scoped IAM roles using exact-match trust conditions so feature branches can only reach staging and only merges to `main` can reach production. The delivery layer serves the live site through CloudFront backed by fully private S3 buckets with OAC, HTTPS via ACM, and a real domain through Route 53. Each pull request is also scanned by an AI reviewer powered by Amazon Bedrock, which flags risky changes as a non-blocking comment for the human reviewer - and during the build it caught a real authentication-breaking issue.

Rollback and monitoring were both tested end to end, not just documented: a deliberately broken deployment was restored using S3 object versioning plus a CloudFront cache invalidation, and a Lambda synthetic check with a CloudWatch alarm and SNS notification alerted the team when the live site failed. The production site was `stiaan.click`.

### 🖥️ [Cloud Engineering Portfolio Website](https://github.com/PeaceMaker122/03-Portfolio-Website-Public)
A responsive Next.js and React portfolio built to present my cloud engineering experience through technical evidence rather than a conventional résumé alone. The site uses the App Router, structured TypeScript data, and a focused architecture-led design to bring together my professional background, capabilities, certifications, project work, contact details, and direct repository links. It is deployed through a GitHub-connected Vercel workflow, with content and presentation separated so profile information can be updated consistently.

The website also includes a server-side AI Architecture Guide powered by the Vercel AI SDK and AI Gateway. It loads the documented project knowledge base from Markdown files and provides grounded answers about architecture decisions, security controls, trade-offs, and implementation choices without exposing credentials or inventing unsupported claims. An anonymous contact form adds server-side validation, honeypot bot protection, and a Resend delivery path, demonstrating practical attention to secure defaults, operational boundaries, and maintainable cloud application design.

### 🏥 [TechHealth Inc.: AWS Infrastructure Migration](https://github.com/PeaceMaker122/02-TechHealth-Inc-AWS-Migration)
A healthcare infrastructure migration case study focused on moving a manually managed AWS patient-portal environment toward an auditable, repeatable platform with AWS CDK and TypeScript. The target design uses a two-Availability-Zone VPC, layered web/app/data architecture, Auto Scaling Groups, a Multi-AZ MySQL RDS database in private subnets, Secrets Manager, least-privilege security groups, and Systems Manager Session Manager instead of SSH.

As a consultant-led enhancement, I also built an AWS-native AI security review pipeline: synthesized CloudFormation templates are uploaded to S3, EventBridge triggers a Lambda reviewer, Amazon Bedrock evaluates RDS exposure, SSH access, IAM permissions, and network segmentation, and the findings are stored in S3 with CloudWatch execution logs for an auditable trail. The end-to-end pipeline was deployed and tested successfully, and the review surfaced genuine risks in the demonstration environment - including public web-tier placement and a shared EC2 IAM role - showing how automated review can support, rather than replace, human engineering judgment.

### 🔐 [StartupCo: Cloud Security & IAM Hardening](https://github.com/PeaceMaker122/01-StartupCo-Security-Project)
A portfolio consulting case study for a fictional fitness-tracking startup that launched fast and left security behind - 10 employees sharing root credentials, no MFA, no least-privilege access, no separation between dev and prod. This project takes that environment from "click-and-pray" to a governed, auditable baseline: role-based IAM groups (Developers, Operations, Finance, Data Analysts), enforced MFA policy, and a GuardDuty detection layer designed into the target-state architecture.

The console-built environment was then codified into Terraform using declarative `terraform import`, verified against a clean `terraform plan` - proving the code matches the live account, not just the intended design. Documented with a clear scale-up path to a multi-account AWS Organizations model with centralized identity, policy-as-code guardrails, and CI-validated Terraform.

### 🌐 [Portfolio Site Deployment: Next.js on AWS via Terraform](https://github.com/PeaceMaker122/00-Terraform-Portfolio-Project)
A freelance client project: deploying a Next.js static portfolio site on AWS with full Infrastructure as Code ownership. The architecture serves the site through CloudFront backed by a private S3 bucket, locked down with Origin Access Control - the current AWS-recommended approach, replacing the legacy OAI method. Terraform manages the entire stack end-to-end, including S3 native state locking rather than the older DynamoDB-based approach, so the project reflects present-day best practice rather than a copy-pasted tutorial pattern.

## Links & Social Media

| Service  | URL |
|----------|-----|
| Website  | https://www.stiaan.dev |
| GitHub   | https://github.com/PeaceMaker122 |
| Medium   | https://medium.com/@PeaceMaker122 |
| LinkedIn | https://www.linkedin.com/in/stiaan-terblanche |

## How to Reach Me

📫 stiaant1@gmail.com
