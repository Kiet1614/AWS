---
title: "Week 11 Worklog"
date: 2024-01-01
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

**Week 11:** 29 June – 5 July 2026

### Week 11 Objectives:

- Launch the **DACSWEBSK** workshop: prepare IAM, build VPC, and deploy RDS SQL Server.
- Deploy the ASP.NET Core app on EC2, integrate S3/SES, and route traffic through ALB + WAF.

### Tasks for this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | - **Workshop [5.1–5.2]:** review DACSWEBSK architecture on AWS <br> - Create IAM user `dacswebsk-dev`, configure AWS CLI; verify access | 29/06/2026 | 29/06/2026 | [5.1 Overview](../../5-Workshop/5.1-Workshop-overview/) · [5.2 Prerequisite](../../5-Workshop/5.2-Prerequisite/) |
| 3 | - **Workshop [5.3]:** create VPC `dacswebsk-vpc`, public/private subnets (2 AZ) <br> - Configure IGW, route tables, Security Groups for EC2 and RDS | 30/06/2026 | 30/06/2026 | [5.3 VPC & Networking](../../5-Workshop/5.3-VPC-Networking/) |
| 4 | - **Workshop [5.4]:** create RDS SQL Server Express `dacswebsk-db` <br> - DB subnet group, SG inbound 1433; migrate schema and sample data | 01/07/2026 | 01/07/2026 | [5.4 Amazon RDS](../../5-Workshop/5.4-RDS/) |
| 5 | - **Workshop [5.6 — EC2]:** launch EC2 `dacswebsk-app`, install .NET 8 runtime <br> - Deploy DACSWEBSK, configure RDS connection string; verify app on port 80 | 02/07/2026 | 02/07/2026 | [5.6 EC2, ALB & WAF](../../5-Workshop/5.6-EC2-ALB-WAF/) |
| 6 | - **Workshop [5.5]:** create S3 buckets (images, videos, certificates, uploads) <br> - Configure SES replacing Gmail SMTP; test file upload and notification email | 03/07/2026 | 03/07/2026 | [5.5 S3 & SES](../../5-Workshop/5.5-S3-SES/) |
| 7 | - **Workshop [5.6 — ALB & WAF]:** create ALB `dacswebsk-alb` + healthy target group <br> - Attach AWS WAF protection pack; access app via ALB DNS | 04/07/2026 | 04/07/2026 | [5.6 EC2, ALB & WAF](../../5-Workshop/5.6-EC2-ALB-WAF/) |

### Week 11 Outcomes:

- Workshop foundation complete: IAM, VPC, RDS, and EC2 running DACSWEBSK connected to the database.
- File storage migrated to S3; transactional email via SES working.
- Application accessible through ALB with WAF protection in front.
