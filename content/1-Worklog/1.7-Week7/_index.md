---
title: "Week 7 Worklog"
date: 2024-01-01
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

**Week 7:** 1–7 June 2026

### Week 7 Objectives:

- Advance IAM knowledge with Permission Boundaries and manage infrastructure operations with AWS Systems Manager.
- Optimize EC2 sizing, encrypt data with KMS, and monitor costs following the Well-Architected Framework.
- Build a Data Lake on AWS from data ingestion through analysis and visualization.

### Tasks for this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | - **IAM Permission Boundary:** learn maximum permission limits for Users/Groups <br> - **Hands-on:** create Boundary Policy and a limited IAM User <br> - Verify effective permissions (intersection of identity policy and boundary); clean up | 01/06/2026 | 01/06/2026 | [https://000030.awsstudygroup.com/](https://000030.awsstudygroup.com/) |
| 3 | - **AWS Systems Manager:** centralized management and automation across multiple servers <br> - **Hands-on:** prepare environment, use Patch Manager for patching <br> - Run bulk commands with Run Command; clean up resources | 02/06/2026 | 02/06/2026 | [https://000031.awsstudygroup.com/](https://000031.awsstudygroup.com/) |
| 4 | - **Right-sizing EC2:** collect memory metrics via CloudWatch Agent <br> - **Hands-on:** create IAM Role, attach to EC2, install CloudWatch Agent <br> - Update EC2 Resource Optimization; apply AWS Compute Optimizer recommendations | 03/06/2026 | 03/06/2026 | [https://000032.awsstudygroup.com/](https://000032.awsstudygroup.com/) |
| 5 | - **Encryption with AWS KMS:** encrypt S3 data at rest using KMS keys <br> - **Hands-on:** create KMS key, encrypted S3 bucket, set up CloudTrail and Athena <br> - Test encrypted data sharing; query logs via Athena and clean up | 04/06/2026 | 04/06/2026 | [https://000033.awsstudygroup.com/](https://000033.awsstudygroup.com/) |
| 6 | - **Cost visualization:** monitor cost & usage per Well-Architected Framework <br> - **Hands-on:** view costs by service/account, Savings Plan and Reserved Instance coverage <br> - Analyze with Cost Explorer; create custom EC2 reports, review data transfer out | 05/06/2026 | 05/06/2026 | [https://000034.awsstudygroup.com/](https://000034.awsstudygroup.com/) |
| 7 | - **Data Lake on AWS:** learn Data Lake concepts and ingest–store–analyze architecture <br> - **Hands-on:** collect & store data, create Data Catalog with AWS Glue <br> - Transform data; analyze and visualize with QuickSight; clean up | 06/06/2026 | 06/06/2026 | [https://000035.awsstudygroup.com/](https://000035.awsstudygroup.com/) |

### Week 7 Outcomes:

- Applied IAM Permission Boundaries to cap user permissions and understood effective permissions.
- Used Systems Manager Patch Manager and Run Command for patching and bulk command execution on EC2.
- Collected CloudWatch Agent metrics and right-sized EC2 with Resource Optimization and Compute Optimizer.
- Encrypted S3 data with KMS, logged audits via CloudTrail, and queried logs through Athena.
- Analyzed and visualized AWS costs with Cost Explorer, tracking Savings Plan/RI coverage.
- Built a basic Data Lake pipeline: ingest → Glue Catalog → transform → analyze with QuickSight.
