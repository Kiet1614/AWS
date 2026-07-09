---
title: "Week 6 Worklog"
date: 2024-01-01
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

**Week 6:** 25–31 May 2026

### Week 6 Objectives:

- Deploy hybrid file storage with AWS Storage Gateway and Amazon FSx for Windows.
- Protect web applications with AWS WAF and manage resources centrally via Tags, Resource Groups, and IAM.
- Set up AWS infrastructure monitoring with Grafana on EC2.

### Tasks for this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | - **File Storage Gateway:** learn hybrid cloud–on-premises file sharing <br> - **Hands-on:** prepare environment, create Storage Gateway and File Share <br> - Connect file share to on-premises machine; clean up resources | 25/05/2026 | 25/05/2026 | [https://000024.awsstudygroup.com/](https://000024.awsstudygroup.com/) |
| 3 | - **FSx on Windows:** learn FSx for Windows File Server architecture (SMB, S3, VPC) <br> - **Hands-on:** prepare, create file share, test and monitor performance <br> - Enable deduplication, shadow copies, user quotas; expand throughput | 26/05/2026 | 26/05/2026 | [https://000025.awsstudygroup.com/](https://000025.awsstudygroup.com/) |
| 4 | - **AWS WAF:** learn Web Application Firewall and web app protection <br> - **Hands-on:** prepare environment, configure WAF rules (allow/block) <br> - Attach WAF to ALB or CloudFront; verify malicious request blocking and clean up | 27/05/2026 | 27/05/2026 | [https://000026.awsstudygroup.com/](https://000026.awsstudygroup.com/) |
| 5 | - **Tags and Resource Groups:** learn Tags (Key/Value) for classifying AWS resources <br> - **Hands-on:** tag EC2, EBS, and related resources <br> - Create tag-based Resource Groups; manage resource sets in bulk and clean up | 28/05/2026 | 28/05/2026 | [https://000027.awsstudygroup.com/](https://000027.awsstudygroup.com/) |
| 6 | - **IAM with EC2 Resource Tags:** manage EC2 access by tag through IAM Policy and Role <br> - **Hands-on:** create IAM Policy restricting permissions by Resource Tag <br> - Create IAM Role for EC2 Administrator; verify policy behavior and clean up | 29/05/2026 | 29/05/2026 | [https://000028.awsstudygroup.com/](https://000028.awsstudygroup.com/) |
| 7 | - **Grafana on AWS:** learn Grafana for visualizing and monitoring AWS resources <br> - **Hands-on:** prepare Linux EC2, install Grafana <br> - Connect CloudWatch data source; build monitoring dashboards and clean up | 30/05/2026 | 30/05/2026 | [https://000029.awsstudygroup.com/](https://000029.awsstudygroup.com/) |

### Week 6 Outcomes:

- Deployed AWS Storage Gateway and File Share for hybrid file sharing between cloud and on-premises.
- Configured Amazon FSx for Windows File Server with advanced file management (deduplication, shadow copies, quotas, throughput).
- Set up AWS WAF to protect web applications against malicious requests.
- Used Tags and Resource Groups to systematically classify and manage AWS resource sets.
- Applied tag-based IAM Policies to control EC2 access following least privilege.
- Installed Grafana on EC2, connected CloudWatch, and built infrastructure monitoring dashboards.
