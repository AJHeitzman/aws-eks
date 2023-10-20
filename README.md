![Pulumi](https://img.shields.io/badge/Pulumi-3.88.0-informational?logo=Pulumi&logoColor=purple)
![Python](https://img.shields.io/badge/Python-3.11.6-informational?logo=Python&logoColor=yellow)
![AWS-CLI](https://img.shields.io/badge/AWS_CLI-2.13.5-informational?logo=Amazon&logoColor=orange)
![Visual_Studio_Code](https://img.shields.io/badge/Visual_Studio_Code-1.83.0-informational?logo=VisualStudioCode)

# AWS EKS
This is a [Pulumi](www.pulumi.com) Python project is used to provision an AWS EKS cluster. This project will stack reference the AWS-Baseline project to provision resources in the correct locations.

## Multiple AWS Account Setup
This project will easily support a multiple AWS account deployment. Simply change aws profile in the stacks config to one that is configured to use the account you wish to deploy resources to.

```yaml
config:
  ...
  aws:profile: <aws_profile_name_here>
```

## Configuration