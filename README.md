# Install and Configure the AWS CLI

## Lab overview

The AWS Command Line Interface (AWS CLI) is a command line tool that provides an interface for interacting with products and services from Amazon Web Services (AWS).

You can install the AWS CLI on your local machine or a virtual machine such as an Amazon Elastic Compute Cloud (Amazon EC2) instance.

In this activity, you install and configure the AWS CLI on a Red Hat Linux instance because this instance type does not have the AWS CLI pre-installed. Some instance types, such as Amazon Linux, do come pre-installed with the AWS CLI.

During this activity, you establish a Secure Shell (SSH) connection to the instance. You configure the installation with an access key that can connect to an AWS account. Finally, you practice using the AWS CLI to interact with AWS Identity and Access Management (IAM).

When you finish the activity, it will reflect the following diagram:

![צילום מסך 2024-10-29 153125](https://github.com/user-attachments/assets/d1f76297-7aaf-45f6-92b2-55e5d1c370fc)


In the preceding diagram, you can access the AWS Cloud through an SSH connection. Within the AWS Cloud, a virtual private cloud (VPC) with a Red Hat EC2 instance is configured with the AWS CLI. IAM is configured, and you use the AWS CLI to interact with IAM.

Objectives

After completing this lab, you should be able to do the following:

Install and configure the AWS CLI.
Connect the AWS CLI to an AWS account.
Access IAM by using the AWS CLI.


More queries in Task 5:

query the details of your subnets.

#### aws ec2 describe-subnets

query the details of your route tables

#### aws ec2 describe-route-tables

query the details of your EC2's

#### aws ec2 describe-instance

query the details of your VPC's

#### aws ec2 describe-vpcs

query the details of your security group

#### aws ec2 describe-security-groups

query the details of user groups

#### aws iam list-groups

query the details of users

#### aws iam list-users

query the details of the policies

#### aws iam list-policies

query the details of the roles

#### aws iam list-roles


