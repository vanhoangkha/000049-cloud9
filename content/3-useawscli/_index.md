+++
title = "Using AWS CLI"
weight = 3
chapter = false
pre = "<b>3. </b>"
+++

#### Using AWS CLI

AWS CLI by AWS is a tool for managing AWS services. You can control many AWS services with the command line and easily automate AWS services by creating script files (not multiple command lines). ).

AWS CLI is pre-installed and preconfigured on Cloud9 instance.

1. Run the AWS CLI command below to list the EC2 instances in our account.
```
aws ec2 describe-instances
```
![Cloud9](/images/cloud9/016.png?width=90pc)

Congratulations on completing the basic AWS Cloud 9 lab. Remember to perform the **Cleanup of Resources** step to avoid unexpected costs.