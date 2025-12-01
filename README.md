# AWS DevOps Projects

Welcome!  
This repository is my **AWS DevOps Portfolio**, where I collect all my hands-on projects demonstrating architecture, automation, and DevOps best practices on AWS.  
Each project is built with real-world scenarios and Infrastructure as Code (IaC) principles.

---

## Overview

This repo serves as a **central hub** linking to my individual AWS and DevOps projects.  
Each project repository includes documentation, Terraform code, architecture diagrams, and deployment steps.

---

## Completed Projects

| # | Project | Description | Link |
|---|----------|--------------|------|
| 1 | **EKS Cluster Bootstrap with Terraform** | Deploys and bootstraps an Amazon EKS cluster using Terraform. Focuses on modular infrastructure design and automation for Kubernetes workloads. | [terraform-aws-eks-bootstrap](https://github.com/alianjo/terraform-aws-eks-bootstrap) |
| 2 | **Immutable Infrastructure on AWS** | Demonstrates creating immutable infrastructure using Terraform — ensuring consistency, version control, and safe deployment practices. | [aws-immutable-infra](https://github.com/alianjo/aws-immutable-infra) |
| 3 | **aws-lambda-ec2-backup** | A serverless AWS backup automation system using Lambda and EventBridge. Automatically creates and cleans up EC2 volume snapshots on a schedule built with Terraform. | [aws-lambda-ec2-backup](https://github.com/alianjo/aws-lambda-ec2-backup) |
| 4 | Three-Tier Web App on AWS | EC2 + RDS + ALB with Terraform — showcase scalability and fault tolerance. |  [aws-three-tier-webapp-terraform](https://github.com/alianjo/aws-three-tier-webapp-terraform) |
| 5 | AWS serverless API | API Gateway (HTTP API) → Lambda → DynamoDB. Provisioned with Terraform. CI via GitHub Actions. |  [aws-serverless-terraform-backend](https://github.com/alianjo/aws-serverless-terraform-backend) |
| 6 | AWS multi-region web stack | Multi-region EC2 + Auto Scaling + Nginx stack on AWS, fronted by CloudFront and Route53 latency-based routing. Demonstrates active-active deployment across us-east-1 and us-west-2 with per-region responses. |  [multi-region-ec2-asg-stack](https://github.com/alianjo/multi-region-ec2-asg-stack) |


---

## Upcoming / TODO Projects

| # | Planned Project | Goal |
|---|------------------|------|
| 1 | CI/CD Pipeline with GitHub Actions | Automate build and deploy processes with GitHub Actions and Terraform. |
| 2 | Observability Stack | Implement Prometheus, Grafana, and Loki for monitoring and logging. |
| 3 | Cost Optimization Dashboard | Create a dashboard for AWS cost monitoring and optimization insights. |


