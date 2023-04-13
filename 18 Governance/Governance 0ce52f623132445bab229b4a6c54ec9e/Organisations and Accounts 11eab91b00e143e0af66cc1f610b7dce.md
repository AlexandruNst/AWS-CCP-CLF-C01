# Organisations and Accounts

AWS Organisations allow the creation of new AWS accounts

Centrally manage billing, control access, security, compliance, resource etc

![Untitled](Organisations%20and%20Accounts%2011eab91b00e143e0af66cc1f610b7dce/Untitled.png)

![Untitled](Organisations%20and%20Accounts%2011eab91b00e143e0af66cc1f610b7dce/Untitled%201.png)

## Root Account User

![Untitled](Organisations%20and%20Accounts%2011eab91b00e143e0af66cc1f610b7dce/Untitled%202.png)

Single sign-in identity that has complete access

Each account has a Root Account User

(Account is the grey row)

## Organisation Units (OU)

![Untitled](Organisations%20and%20Accounts%2011eab91b00e143e0af66cc1f610b7dce/Untitled%203.png)

Group of AWS accounts that can have other OU in them, creating a hierarchy

## Service Control Policies (SCPs)

Central control over allowed permissions

Ensure accounts stay within your org’s guideline

---

Once turned on, orgs cannot be turned off

AWS Account is not the same as User Account

**Key Points:**

- In AWS you can have more than one account managed through a single account using Organizations
- Organizations allow you to setup consolidated billing where 1 account pays the AWS bill for all
- The payer account is the root level account in an Organization
- You can create isolated AWS accounts for different teams under the
payer account - and place them inside Organizational Units (OU)
- The separation of accounts into OUs allows you to set customized
permission boundaries on the accounts using Service Control Policies
(SCPs)