# DOP-C02 Certification Notes

Interactive study guides for the AWS DevOps Engineer Professional exam, organized by exam domain. Each AWS service has its own dedicated HTML page with focused notes, key concepts, and exam tips.

---

## Exam Domains

| # | Domain | Weight | Services |
|---|--------|--------|----------|
| 01 | SDLC Automation | 22% | Amplify, CodeArtifact, CodeBuild, CodeDeploy, CodeGuru, CodeStar, EC2 Image Builder — plus topic guides: Multi-Account & Cross-Region Pipelines, Pipeline Failures, Testing Strategies |
| 02 | Configuration Management & IaC | 17% | CloudFormation, Service Catalog, Elastic Beanstalk, SAM, CDK, SSM, AppConfig, Step Functions |
| 03 | Resilient Cloud Solutions | 15% | API Gateway, App Auto Scaling, ASG, Aurora, DMS, DynamoDB, ECR, ECS, EKS, ElastiCache, ELB, Kinesis Firehose, Apache Flink, Kinesis Data Streams, Lambda, NAT Gateway, RDS, Route 53, S3, Storage Gateway |
| 04 | Monitoring & Logging | 15% | CloudWatch, Athena |
| 05 | Incident & Event Response | 18% | EventBridge, Health Dashboard, Instance Status Check, CloudTrail, SQS, SNS, X-Ray |
| 06 | Security & Compliance | 13% | Config, Control Tower, Detective, Firewall Manager, GuardDuty, IAM Identity Center, Inspector, Organizations, Secrets Manager, Trusted Advisor, WAF |
| — | Extras | — | Glue, QuickSight, Tag Editor |

---

## Project Structure

```
aws-notes/
├── index.html          # Landing page with expandable domain index
├── favicon.svg
├── vercel.json
├── domain_one/         # SDLC Automation
├── domain_two/         # Configuration Management & IaC
├── domain_three/       # Resilient Cloud Solutions
├── domain_four/        # Monitoring & Logging
├── domain_five/        # Incident & Event Response
├── domain_six/         # Security & Compliance
└── domain_extras/      # Glue, QuickSight, Tag Editor
```

## Stack

- **Frontend:** HTML5, CSS (inline), vanilla JS — no build step, no dependencies
- **Fonts:** Space Grotesk, Fraunces, IBM Plex Mono via Google Fonts
- **Hosting:** Vercel (static)

## Running locally

```bash
# Any static server works
npx serve .

# Or just open index.html directly in the browser
```
