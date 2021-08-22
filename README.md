# SQL-based ETL with Spark on EKS

In this Jam challenge, we will leverage an open-source [Arc data framework](https://arc.tripl.ai/) to build a declarative ETL solution. We take considerations of the needs and expected skills from customers in data analytics, and accelerate their interaction with ETL practice in order to foster simplicity, while maximizing efficiency.

The sample provides two ways of running the solution shown in the architecture diagram:
1. Spark on EKS by Argo Workflows tool
2. [EMR on EKS](https://aws.amazon.com/emr/features/eks/) 

## Prerequisite
1. Python 3.6 or later. You can find information about downloading and installing Python [here](https://www.python.org/downloads/).
2. AWS CLI version 1.
  Windows: [MSI installer](https://docs.aws.amazon.com/cli/latest/userguide/install-windows.html#install-msi-on-windows)
  Linux, macOS or Unix: [Bundled installer](https://docs.aws.amazon.com/cli/latest/userguide/install-macos.html#install-macosos-bundled)
3. AWS CLI is configured to communicate with services in your deployment account. Otherwise, either set your profile by `export AWS_PROFILE=<your_aws_profile>` , or run the following configuration to setup your AWS account access.
```bash
aws configure
```  