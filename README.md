<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://svgl.app/library/aws_dark.svg" />
    <img alt="AWS Logo" src="https://svgl.app/library/aws_light.svg" width="80" />
  </picture>
</p>

<h1 align="center">Awesome AWS</h1>

<p align="center">
  <a href="https://awesome.re"><picture><source media="(prefers-color-scheme: dark)" srcset="https://shieldcn.dev/badge/awesome.svg?variant=outline&amp;mode=dark&amp;font=geist&amp;logo=awesomelists" /><img alt="awesome" src="https://shieldcn.dev/badge/awesome.svg?variant=outline&amp;mode=light&amp;font=geist&amp;logo=awesomelists" /></picture></a>
  <a href="https://aws.amazon.com/"><picture><source media="(prefers-color-scheme: dark)" srcset="https://shieldcn.dev/badge/AWS-Cloud.svg?variant=outline&amp;mode=dark&amp;font=geist&amp;logo=amazonaws" /><img alt="AWS" src="https://shieldcn.dev/badge/AWS-Cloud.svg?variant=outline&amp;mode=light&amp;font=geist&amp;logo=amazonaws" /></picture></a>
  <a href="LICENSE"><picture><source media="(prefers-color-scheme: dark)" srcset="https://shieldcn.dev/badge/license-MIT.svg?variant=outline&amp;mode=dark&amp;font=geist" /><img alt="license" src="https://shieldcn.dev/badge/license-MIT.svg?variant=outline&amp;mode=light&amp;font=geist" /></picture></a>
  <a href="https://github.com/bhagirath00/awesome-aws"><picture><source media="(prefers-color-scheme: dark)" srcset="https://shieldcn.dev/views/repo/bhagirath00/awesome-aws.svg?variant=outline&amp;mode=dark&amp;font=geist" /><img alt="views" src="https://shieldcn.dev/views/repo/bhagirath00/awesome-aws.svg?variant=outline&amp;mode=light&amp;font=geist" /></picture></a>
</p>

## Table of Contents

- [Introduction](#introduction)
- [Why AWS for DevOps?](#why-aws-for-devops)
- [Learning Modules](#learning-modules)
  - [Phase 1: Cloud Foundations & Identity](#phase-1-cloud-foundations--identity)
  - [Phase 2: Compute, Networking & Storage Architecture](#phase-2-compute-networking--storage-architecture)
  - [Phase 3: Modern Application Platforms & CI/CD](#phase-3-modern-application-platforms--cicd)
  - [Phase 4: Serverless Computing, Monitoring & FinOps](#phase-4-serverless-computing-monitoring--finops)
- [Resources](#resources)
- [Contributing](#contributing)
- [Security](#security)
- [License](#license)

---

## Introduction

Welcome to **Awesome AWS**! This repository serves as an exhaustive, hands-on architectural roadmap and reference manual designed for site reliability engineers (SREs), DevOps practitioners, and cloud architects building resilient infrastructure on Amazon Web Services.

> **"Everything fails, all the time."** — Werner Vogels (CTO, Amazon.com)

---

## Why AWS for DevOps?

Amazon Web Services is the world's most comprehensive and broadly adopted cloud platform:

| Capability | Importance in DevOps |
| :--- | :--- |
| **Global Resiliency** | 30+ geographic regions with multi-AZ fault isolation and low-latency edge caching |
| **Enterprise Identity** | Granular access control using AWS IAM, temporary STS credentials, and Organizations SCPs |
| **Elastic Infrastructure** | Dynamic auto scaling across serverless, containerized (ECS/EKS), and virtual compute (EC2) |
| **Comprehensive Tooling** | Turnkey services spanning managed Kubernetes, private VPCs, GitOps pipelines, and FinOps |

---

## Learning Modules

Organized into 11 comprehensive modules covering 46 chapters of foundational cloud architecture, security, and automated delivery.

### Phase 1: Cloud Foundations & Identity

| Module | Description |
| :--- | :--- |
| [**Module 01 - Introduction**](./Module%2001%20-%20Introduction/) | Global infrastructure, regions, availability zones, AWS Management Console, and AWS CLI v2 |
| [**Module 02 - Free Tier Guide**](./Module%2002%20-%20Free%20Tier%20Guide/) | Free Tier service allocation, billing alarms, AWS Budgets, and sandbox security constraints |
| [**Module 03 - IAM and Security**](./Module%2003%20-%20IAM%20and%20Security/) | Users, Groups, Roles, Policies, STS AssumeRole, AWS KMS, GuardDuty, and Security Hub |

### Phase 2: Compute, Networking & Storage Architecture

| Module | Description |
| :--- | :--- |
| [**Module 04 - Compute**](./Module%2004%20-%20Compute/) | EC2 instance lifecycles, AMIs, Launch Templates, Auto Scaling Groups (ASG), and ALB/NLB load balancers |
| [**Module 05 - Networking**](./Module%2005%20-%20Networking/) | Custom VPCs, Subnets, Route Tables, Internet/NAT Gateways, Security Groups, Route 53, and CloudFront |
| [**Module 06 - Storage**](./Module%2006%20-%20Storage/) | S3 object storage, bucket policies, lifecycle rules, EBS block volumes, and EFS shared filesystems |

### Phase 3: Modern Application Platforms & CI/CD

| Module | Description |
| :--- | :--- |
| [**Module 07 - Containers**](./Module%2007%20-%20Containers/) | Elastic Container Service (ECS), Fargate serverless containers, ECR registries, and AWS EKS Kubernetes |
| [**Module 08 - CI-CD**](./Module%2008%20-%20CI-CD/) | AWS CodeCommit, CodeBuild (buildspec.yml), CodeDeploy (appspec.yml), and CodePipeline orchestration |
| [**Module 09 - Infrastructure as Code**](./Module%2009%20-%20Infrastructure%20as%20Code/) | AWS CloudFormation templates, AWS Cloud Development Kit (CDK), and HashiCorp Terraform AWS provider |

### Phase 4: Serverless Computing, Monitoring & FinOps

| Module | Description |
| :--- | :--- |
| [**Module 10 - Serverless**](./Module%2010%20-%20Serverless/) | AWS Lambda event-driven functions, concurrency, execution roles, API Gateway, and Step Functions |
| [**Module 11 - Monitoring and Cost**](./Module%2011%20-%20Monitoring%20and%20Cost/) | CloudWatch Metrics, Alarms, Logs Insights, AWS X-Ray distributed tracing, and Cost Explorer FinOps |

---

## Resources

### Official Documentation

| Resource | Link |
| :--- | :--- |
| AWS Documentation | [docs.aws.amazon.com](https://docs.aws.amazon.com/) |
| AWS Architecture Center | [aws.amazon.com/architecture](https://aws.amazon.com/architecture/) |
| AWS Well-Architected Tool | [aws.amazon.com/architecture/well-architected](https://aws.amazon.com/architecture/well-architected/) |
| AWS CLI Command Reference | [docs.aws.amazon.com/cli](https://docs.aws.amazon.com/cli/latest/reference/) |

### Recommended Tools

- **AWS CLI v2**: Primary command-line tool for interacting with AWS services.
- **awsume / granted**: Fast CLI profile switching and AWS STS assume-role utilities.
- **LocalStack**: Fully functional local cloud stack for testing AWS applications offline.
- **Infracost**: Cloud cost estimates for AWS Terraform pull requests.

---

## Contributing

Contributions are welcome! Please read our [Contributing Guidelines](CONTRIBUTING.md) before submitting a Pull Request.

---

## Security

Please review our [Security Policy](SECURITY.md) for IAM hardening practices, credential governance, and vulnerability reporting.

---

## License

This educational content is open source and available under the **MIT License**. See [LICENSE](LICENSE) for details.

<p align="center">
  <strong>Happy Cloud Building!</strong>
</p>
