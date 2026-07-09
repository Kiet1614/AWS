---
title: "Week 4 Worklog"
date: 2024-01-01
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

**Week 4:** 11–17 May 2026

### Week 4 Objectives:

* Get familiar with and practice AWS operations through the Command Line Interface (CLI).
* Understand centralized identity management with IAM Identity Center and backup/migration models.
* Practice application containerization with Docker, ECR, and deployment on Amazon ECS.

### Tasks for this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | - **Getting started with AWS CLI:** introduction, environment setup, and CLI installation on Windows <br> - Check resources via CLI; work with **Amazon S3**, **SNS**, **IAM**, and **VPC** <br> - **Hands-on:** create EC2 via CLI, troubleshoot common errors, and clean up resources | 11/05/2026 | 11/05/2026 | [https://000011.awsstudygroup.com/](https://000011.awsstudygroup.com/) |
| 3 | - **IAM Identity Center:** learn centralized identity management across multiple AWS accounts <br> - Configure AWS CLI access through Identity Center; set up **Time-based access control** <br> - **Hands-on:** Customer Managed Policies, Identity Store APIs, and cleanup | 12/05/2026 | 12/05/2026 | [https://000012.awsstudygroup.com/](https://000012.awsstudygroup.com/) |
| 4 | - **AWS Backup:** overview of centralized backup for EBS, RDS, DynamoDB, and EFS <br> - **Hands-on:** create a Backup plan and configure success/failure notifications <br> - Verify backup & restore operations; clean up resources | 13/05/2026 | 13/05/2026 | [https://000013.awsstudygroup.com/](https://000013.awsstudygroup.com/) |
| 5 | - **VM Import/Export:** understand importing/exporting VMs between on-premises and EC2 <br> - Prepare a virtual machine (VMware Workstation, AWS CLI); import VM into AWS via S3 <br> - **Hands-on:** export EC2 instance from AWS, review reference videos, and clean up | 14/05/2026 | 14/05/2026 | [https://000014.awsstudygroup.com/](https://000014.awsstudygroup.com/) |
| 6 | - **Docker on AWS:** deploy the application locally with Docker; prepare the AWS environment <br> - Configure **Amazon RDS** and **EC2**; deploy with Docker image and **Docker Compose** <br> - **Hands-on:** push image to **Amazon ECR**, configure Security Groups, and clean up | 15/05/2026 | 15/05/2026 | [https://000015.awsstudygroup.com/](https://000015.awsstudygroup.com/) |
| 7 | - **Amazon ECS:** learn container deployment architecture with Fargate, ALB, and Service Discovery <br> - **Hands-on:** register Cloud Map namespace, create ECS Cluster, Task Definition, and ECS Service <br> - Configure Application Load Balancer; verify frontend/backend + RDS deployment and clean up | 16/05/2026 | 16/05/2026 | [https://000016.awsstudygroup.com/](https://000016.awsstudygroup.com/) |

### Week 4 Outcomes:

* Installed and used AWS CLI to manage S3, SNS, IAM, VPC, and create EC2 from the command line without relying solely on the Console.
* Understood how to deploy IAM Identity Center with least privilege, time-based access, and Customer Managed Policies across accounts.
* Created centralized Backup plans for multiple resource types (EBS, RDS, DynamoDB, EFS), set up notifications, and verified restore operations.
* Grasped the VM Import/Export workflow for migrating on-premises workloads to EC2 and exporting back, using S3 as intermediate storage.
* Containerized applications with Docker on EC2, deployed via Docker Compose, pushed images to ECR, and applied network security configuration.
* Deployed a multi-tier application (frontend/backend) on Amazon ECS Fargate with ALB, Cloud Map Service Discovery, and RDS MySQL connectivity.
