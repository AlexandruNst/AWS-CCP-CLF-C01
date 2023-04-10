# Access Keys

<aside>
⚠️ A **key and a secret** required to have programmatic access to AWS resources outside the AWS Management Console

</aside>

“**AWS Credentials**”

A used must be granted access to use Access Keys

![Untitled](Access%20Keys%2070dd0b52a8e04ef899008bbb3cbb64ee/Untitled.png)

Then they can generate a **Access Key and Secret**

![Untitled](Access%20Keys%2070dd0b52a8e04ef899008bbb3cbb64ee/Untitled%201.png)

You can have 2 active

You can deactivate

Same access as the user’s access

# NEVER SHARE

# NEVER COMMIT

To be stored in the `~/.aws/credentials` file

![Untitled](Access%20Keys%2070dd0b52a8e04ef899008bbb3cbb64ee/Untitled%202.png)

default for no specified profile, and can also set profiles and switch with `--profile <profile>`

Can use `aws configure` to set up the file

![Untitled](Access%20Keys%2070dd0b52a8e04ef899008bbb3cbb64ee/Untitled%203.png)

When using the SDK, the safest way is to use environment variables

AWS will read these automatically

![Untitled](Access%20Keys%2070dd0b52a8e04ef899008bbb3cbb64ee/Untitled%204.png)

Good idea is to generate both Access Keys, even if not used. So if a malicious user gets access to an account, they can’t create a key for their own use