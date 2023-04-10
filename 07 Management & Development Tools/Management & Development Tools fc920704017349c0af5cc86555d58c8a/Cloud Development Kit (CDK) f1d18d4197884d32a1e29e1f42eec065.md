# Cloud Development Kit (CDK)

Allows you to use a programming language to write IaC

![Untitled](Cloud%20Development%20Kit%20(CDK)%20f1d18d4197884d32a1e29e1f42eec065/Untitled.png)

CDK is powered by CFN (it generates CFN templates)

CDK **has its own CLI** :)

CDK allows to make quick CI/CD pipelines (unlike CFN)

CDK has a testing framework for Unit and Integration Testing

<aside>
⚠️ AWS SDK looks similar, the key difference is that CDK ensures **Idempotence** of your infrastructure

</aside>

ok so some differences I found:

![Untitled](Cloud%20Development%20Kit%20(CDK)%20f1d18d4197884d32a1e29e1f42eec065/Untitled%201.png)

![Untitled](Cloud%20Development%20Kit%20(CDK)%20f1d18d4197884d32a1e29e1f42eec065/Untitled%202.png)

![Untitled](Cloud%20Development%20Kit%20(CDK)%20f1d18d4197884d32a1e29e1f42eec065/Untitled%203.png)

![Untitled](Cloud%20Development%20Kit%20(CDK)%20f1d18d4197884d32a1e29e1f42eec065/Untitled%204.png)

![Untitled](Cloud%20Development%20Kit%20(CDK)%20f1d18d4197884d32a1e29e1f42eec065/Untitled%205.png)

Basically, with CDK you write code to generate CFN. WIth SDK, you interact with the services in your code.

Also, **SDK has no state management**

To use the CDK CLI:

`npm i -g aws-cdk`

make a folder, cd

`cdk init sample-app --language=typescript`

write your project

![Untitled](Cloud%20Development%20Kit%20(CDK)%20f1d18d4197884d32a1e29e1f42eec065/Untitled%206.png)

`cdk deploy`

![Untitled](Cloud%20Development%20Kit%20(CDK)%20f1d18d4197884d32a1e29e1f42eec065/Untitled%207.png)

![Untitled](Cloud%20Development%20Kit%20(CDK)%20f1d18d4197884d32a1e29e1f42eec065/Untitled%208.png)

Then if you check CFN, it’s there. CDK just created CFN but with code

![Untitled](Cloud%20Development%20Kit%20(CDK)%20f1d18d4197884d32a1e29e1f42eec065/Untitled%209.png)

And the services (SQS, SNS) are created :)