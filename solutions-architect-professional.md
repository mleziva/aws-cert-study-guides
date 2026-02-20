# Overview

I passed the AWS Solutions Architect Professional Exam 10/2025. Topics may have changed since then, but I focused on the following areas when studying for the exam. 

Last updated date: 2/18/2026   


# AWS 

## Security 
### IAM
- Identity fundamentals: users, groups, roles, policies (managed vs inline), and resource-based policies.
- Policy structure & evaluation: statements, actions, resources, conditions, Effect/Principal, policy evaluation logic (allow/deny, explicit deny, implicit deny).
- Roles & trust: trust policies, `AssumeRole`, cross-account roles, role chaining, service-linked roles, instance profiles for EC2, roles for Lambda/ECS tasks.
- Temporary credentials & STS: `AssumeRole`, `AssumeRoleWithSAML`, `AssumeRoleWithWebIdentity`, `GetSessionToken`, session duration, and external ID usage.
- Federation & SSO: SAML and OIDC federation, IAM Identity Center (AWS SSO), identity providers and mapping assertions.
- Advanced controls: permissions boundaries, permissions policies vs resource policies, tag-based access control, attribute-based controls, and conditions (IP, time, aws:SourceIp, aws:PrincipalTag, ForAnyValue/ForAllValue).
- Organization-level controls: AWS Organizations and Service Control Policies (SCPs) — guardrails vs IAM permissions.
- Cross-account access patterns: resource policies (S3, KMS), role assumption, cross-account delegation, and secure patterns (external ID, least-privilege roles).
- Security best practices & governance: least privilege, MFA, key and credential rotation, avoid long-lived access keys, use roles where possible, IAM Access Analyzer, Access Advisor, and credential reports.
- Auditing & monitoring: CloudTrail for IAM events, CloudWatch Events/Logs, detecting privilege escalation and policy changes.
- Service integrations: IAM with KMS, S3 bucket policies, VPC endpoint policies, API Gateway authorizers, and service-linked roles.
- Troubleshooting: IAM Policy Simulator, common deny scenarios, understanding ARNs/principals, and interpreting policy evaluation.
- Exam tips: be prepared to design cross-account solutions, choose between resource-based vs identity-based policies, construct minimal policies, and explain AssumeRole flows.
### SCP

## migration strategies 
(AWS MGN, Database Migration Service)


## Networking
### Transit gateway
### VPN site to site
### Privatelink service access
### Direct connect and gateway
### AWS vpn client

## Data
### Data replication
### DMS
### Data backup
### File vs volume gateway
### Types of S3 file storage (ebs vs EFS vs windows)


## Other 
Service catalog
Aurora mysql available
optimizing for cost and reliability (Well-Architected Framework)
Disaster recovery