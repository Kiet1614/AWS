---
title: "Week 5 Worklog"
date: 2024-01-01
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

**Week 5:** 18–24 May 2026

### Week 5 Objectives:

- Set up CI/CD pipelines for ECS containers and deploy a Node.js application to EC2 using the Code* service suite.
- Strengthen security with AWS Security Hub and optimize EC2 costs through Lambda automation.
- Connect multi-VPC networks via VPC Peering and AWS Transit Gateway.

### Tasks for this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | - **CI/CD with ECS Container:** learn CI/CD concepts and prepare the environment <br> - **Hands-on:** deploy pipelines with GitLab, GitHub Actions, and CodeBuild <br> - Monitor with Container Insights (CloudWatch); route logs with Firelens and clean up | 18/05/2026 | 18/05/2026 | [https://000017.awsstudygroup.com/](https://000017.awsstudygroup.com/) |
| 3 | - **AWS Security Hub:** overview and aggregating alerts from GuardDuty, Inspector, Macie <br> - **Hands-on:** enable Security Hub, review scores per security standard (CIS, PCI, etc.) <br> - Track compliance on the dashboard; clean up resources | 19/05/2026 | 19/05/2026 | [https://000018.awsstudygroup.com/](https://000018.awsstudygroup.com/) |
| 4 | - **VPC Peering:** learn private connectivity between two VPCs without the public internet <br> - **Hands-on:** prepare VPCs, update Network ACLs, create a Peering connection <br> - Enable Cross-Peer DNS; verify subnet connectivity and clean up | 20/05/2026 | 20/05/2026 | [https://000019.awsstudygroup.com/](https://000019.awsstudygroup.com/) |
| 5 | - **AWS Transit Gateway:** learn hub-and-spoke architecture for multi-VPC connectivity <br> - **Hands-on:** create Transit Gateway, attachments for 4 VPCs, Transit Gateway Route Tables <br> - Add routes to VPC Route Tables; verify EC2 host connectivity and clean up | 21/05/2026 | 21/05/2026 | [https://000020.awsstudygroup.com/](https://000020.awsstudygroup.com/) |
| 6 | - **Optimize EC2 costs with Lambda:** automate scheduled start/stop to reduce spending <br> - **Hands-on:** tag instances, create IAM Role and Lambda Function <br> - Set up CloudWatch Rule (EventBridge) to trigger Lambda; send Slack notifications and clean up | 22/05/2026 | 22/05/2026 | [https://000022.awsstudygroup.com/](https://000022.awsstudygroup.com/) |
| 7 | - **CI/CD to EC2 with CodePipeline:** learn DevOps and CI/CD culture on AWS <br> - **Hands-on:** install CodeDeploy Agent, set up CodeCommit, CodeBuild, CodeDeploy <br> - Create CodePipeline to build & deploy a Node.js app to EC2; troubleshoot and clean up | 23/05/2026 | 23/05/2026 | [https://000023.awsstudygroup.com/](https://000023.awsstudygroup.com/) |

### Week 5 Outcomes:

- Deployed CI/CD pipelines for ECS containers via GitLab, GitHub Actions, and CodeBuild; monitored with Container Insights and routed logs with Firelens.
- Enabled AWS Security Hub, tracked compliance scores, and aggregated security alerts from multiple AWS services on a single dashboard.
- Established VPC Peering between two VPCs, configured NACLs, Cross-Peer DNS, and verified secure internal connectivity.
- Connected 4 VPCs through AWS Transit Gateway with attachments, route tables, and proper routing.
- Automated EC2 start/stop with Lambda and EventBridge for cost optimization, including status notifications.
- Built a full CI/CD pipeline (CodeCommit → CodeBuild → CodeDeploy → CodePipeline) deploying a Node.js application to EC2.
