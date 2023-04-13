# Zero Trust on AWS

Zero Trust implemented via IAM

# AWS Identity and Access Management (IAM)

- IAM Policies - this user is allowed these services with these actions
- Permission Boundaries - this user should not have access to ML services. Permissions must fall within these boundaries
- Service Control Policies (SCPs) - org-wide. Don’t want anyone running anything in Canada region
- IAM Policy Conditions - more granular controls
    - aws:SourceIP - restrict IP
    - aws:RequestedRegion - Restrict on region
    - aws:MultiFactorAuthPresent - Restrict is MFA is turned off
    - aws:CurrentTime - restrict based on time of day

These can achieve Zero Trust-ish

AWS doesn’t have a Zero Trust ready-to-use identity control that is intelligent.

You can sorta achieve it, but it’s a lot of work and requires expert knowledge.

E.g. API calls go thorugh AWS CloudTrail

→ Amazon GuardDuty: detects sus activity based on logs 

→ Amazon Detective, analyze and identify security issues based on GuardDuty findings

You are kinda required to use third-parties if you want easy and intelligent Zero Trust