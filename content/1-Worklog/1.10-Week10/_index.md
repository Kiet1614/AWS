---
title: "Week 10 Worklog"
date: 2024-01-01
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

**Week 10:** 22–28 June 2026

### Week 10 Objectives:

- Orchestrate serverless workflows with AWS Step Functions and grant application access via IAM Roles.
- Work in AWS Cloud9; deploy a monolith application to Elastic Beanstalk.
- Set up automated application release pipelines with CodeStar and CodeDeploy.

### Tasks for this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | - **AWS Step Functions:** coordinate workflows across AWS services <br> - **Hands-on:** create state machines with Task, Choice, and Parallel states <br> - Error handling, waitForTaskToken (pause/resume); debug in console and clean up | 22/06/2026 | 22/06/2026 | [https://000047.awsstudygroup.com/](https://000047.awsstudygroup.com/) |
| 3 | - **IAM Role for applications:** securely grant apps access to AWS services <br> - **Hands-on:** compare access keys vs IAM Roles (Role recommended) <br> - Attach IAM Role to EC2 for S3/RDS access; clean up | 23/06/2026 | 23/06/2026 | [https://000048.awsstudygroup.com/](https://000048.awsstudygroup.com/) |
| 4 | - **AWS Cloud9:** browser-based IDE with editor, debugger, and integrated terminal <br> - **Hands-on:** create Cloud9 environment, learn basic features <br> - Use AWS CLI in Cloud9; clean up resources | 24/06/2026 | 24/06/2026 | [https://000049.awsstudygroup.com/](https://000049.awsstudygroup.com/) |
| 5 | - **Transforming a Monolith app:** deploy TravelBuddy web app to AWS <br> - **Hands-on:** test locally with Eclipse IDE, deploy to **Elastic Beanstalk** <br> - Update application, query API via Eclipse; clean up | 25/06/2026 | 25/06/2026 | [https://000050.awsstudygroup.com/](https://000050.awsstudygroup.com/) |
| 6 | - **Automated application release:** CI/CD for TravelBuddy on Elastic Beanstalk <br> - **Hands-on:** configure automated release with **AWS CodeStar** <br> - Deploy Windows Service via CodeDeploy on EC2; monitor service and clean up | 26/06/2026 | 26/06/2026 | [https://000051.awsstudygroup.com/](https://000051.awsstudygroup.com/) |

### Week 10 Outcomes:

- Built Step Functions workflows with Lambda, branching, parallel execution, and error handling.
- Granted application access via IAM Roles on EC2 instead of hardcoded access keys.
- Used AWS Cloud9 as a development environment and ran AWS CLI in the cloud.
- Deployed the TravelBuddy monolith to Elastic Beanstalk and updated application versions.
- Set up automated CI/CD pipelines with CodeStar/CodeDeploy for Beanstalk and Windows Service.
