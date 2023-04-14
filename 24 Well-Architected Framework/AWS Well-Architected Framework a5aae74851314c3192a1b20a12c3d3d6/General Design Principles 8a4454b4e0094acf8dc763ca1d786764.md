# General Design Principles

1. **Stop guessing your capacity needs**
    
    Cloud computing allows to change based on demand
    
2. **Test systems at production scale**
    
    Clone prod to testing environment, test, and tear down testing to save money
    
3. **Automate to make architectural experimentation easier**
    
    Using IaC, i.e. using CloudFormation etc
    
4. **Allow for evolutionary architectures**
    
    CI/CD, rapid (nightly) releases, Lambdas deprecate over-time so they force you to evolve
    
5. **Drive architectures using data**
    
    CloudWatch, CloudTrail
    
6. **Improve through game days**
    
    Simulate prod traffic
    
    Purposely killing EC2 instances to test recovery etc.