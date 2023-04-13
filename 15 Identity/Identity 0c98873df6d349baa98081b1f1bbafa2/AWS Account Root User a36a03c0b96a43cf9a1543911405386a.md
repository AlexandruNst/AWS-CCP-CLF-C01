# AWS Account Root User

![Untitled](AWS%20Account%20Root%20User%20a36a03c0b96a43cf9a1543911405386a/Untitled.png)

AWS Root User is created at the time of the AWS Account creation

- Email + password login
- Can’t be deleted
- Full permissions (except for Service Control Policies, those are org-wide)
- Only one
- For specific tasks that are rarely used
- Not for daily and common tasks
- Never use Root User Access Keys
- Always turn on MFA

## Tasks only Root User can perform

- **Change account settings**
    - **name, email, password, root user access keys**
    - **others like contact, payment details, regions do NOT require root user access**
- Restore IAM policies
- Activate IAM access to Billing console
- View tax invoices
- **Close AWS account**
- **Change or Cancel AWS Support plan**
- Register a seller in the RI marketplace
- Enable MFA Delete on S3 Buckets
- Edit or delete an Amazon S3 bucket policy that includes in invalid VPC ID
- Sign up for GovCloud
- Create the Organisation

→ yellow for exam