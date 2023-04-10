# CloudFormation (CFN)

AWS CFN allows you to write IaC as either JSON or YAML

![this is YAML](CloudFormation%20(CFN)%20d8235048499d4ab5aa915c001819cf6a/Untitled.png)

this is YAML

Simple.

But can lead to large files

Limited in creating dynamic or repeatable infra

CDK generates CFN so it’s still important to be able to read and understand CFN

Process is, you create a template (like above) (manually, or with the designer built in the Management Console) and then create a CFN stack with the template, that stack executes the template and creates the service defined in there.

You can do this in the Management Console.

Can also use CFN in the [CLI](AWS%20CLI%20ada60a318f454d91ba28688cf0fa075a.md)

![Untitled](CloudFormation%20(CFN)%20d8235048499d4ab5aa915c001819cf6a/Untitled%201.png)

![Untitled](CloudFormation%20(CFN)%20d8235048499d4ab5aa915c001819cf6a/Untitled%202.png)