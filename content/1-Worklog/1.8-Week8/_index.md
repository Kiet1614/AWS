---
title: "Week 8 Worklog"
date: 2024-01-01
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

**Week 8:** 8–14 June 2026

### Week 8 Objectives:

- Deploy Infrastructure as Code with CloudFormation and AWS CDK.
- Deepen DynamoDB skills, analyze data with Glue/Athena, and integrate federated identity with Azure AD.
- Complete a Data Lake architecture from data ingestion through visualization.

### Tasks for this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | - **Data Lake on AWS:** learn Data Lake concepts — collect-all, multi-user, flexible access <br> - **Hands-on:** collect & store data, create Data Catalog with AWS Glue <br> - Transform data; analyze and visualize with QuickSight; clean up | 08/06/2026 | 08/06/2026 | [https://000036.awsstudygroup.com/](https://000036.awsstudygroup.com/) |
| 3 | - **AWS CloudFormation:** model infrastructure with YAML/JSON templates <br> - **Hands-on:** prepare environment (Cloud9), basic and advanced CloudFormation <br> - Deploy, update, and delete stacks automatically; clean up resources | 09/06/2026 | 09/06/2026 | [https://000037.awsstudygroup.com/](https://000037.awsstudygroup.com/) |
| 4 | - **Basic CDK:** define infrastructure with TypeScript/Python instead of raw YAML <br> - **Hands-on:** learn CDK on top of CloudFormation, create CDK Template <br> - Update template, deploy basic architecture to AWS; clean up | 10/06/2026 | 10/06/2026 | [https://000038.awsstudygroup.com/](https://000038.awsstudygroup.com/) |
| 5 | - **Amazon DynamoDB Immersion Day:** advanced DynamoDB hands-on labs <br> - **Hands-on:** LHOL basics, design patterns (LADV), Change Data Capture (LCDC) <br> - Event-driven architecture (LEDA), global serverless apps (LMR), data modeling (LGME) | 11/06/2026 | 11/06/2026 | [https://000039.awsstudygroup.com/](https://000039.awsstudygroup.com/) |
| 6 | - **Cost & performance analysis with Glue and Athena:** set up a platform for system report analysis <br> - **Hands-on:** Glue Crawler scans S3 data, create Parquet Data Catalog <br> - Run SQL queries via Athena for cost/performance analysis; clean up | 12/06/2026 | 12/06/2026 | [https://000040.awsstudygroup.com/](https://000040.awsstudygroup.com/) |
| 7 | - **IAM Federation from Azure AD:** integrate Microsoft Entra ID (Azure AD) with AWS via SAML SSO <br> - **Hands-on:** create Enterprise Application, Identity Provider, and IAM Role on AWS <br> - Sync roles, configure Provisioning; federate Azure AD users to access AWS; clean up | 13/06/2026 | 13/06/2026 | [https://000041.awsstudygroup.com/](https://000041.awsstudygroup.com/) |

### Week 8 Outcomes:

- Built a complete Data Lake pipeline: ingest → Glue Catalog → transform → QuickSight visualization.
- Deployed and managed AWS infrastructure with CloudFormation templates and AWS CDK.
- Grasped advanced DynamoDB patterns: CDC, event-driven design, global tables, and data modeling.
- Analyzed system cost and performance using AWS Glue Crawler and Athena queries on Parquet catalog.
- Set up SAML IAM Federation between Azure AD and AWS for SSO login and role-based access.
