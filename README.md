<h1 align="center"> How to Install </h1> <br>

# AWS TTS service

## Compare AWS account root user and iam user

The root user is the account owner and is created when the AWS account is created. Other types of users, including IAM users, and AWS IAM Identity Center users are created by the root user or an administrator for the account. All AWS users have security credentials.

* ROOT

  The credentials of the account owner allow full access to all resources in the account. You can't use IAM policies to explicitly deny the root user access to resources. You can only use an AWS Organizations service control policy (SCP) to limit the permissions of the root user of a member account. Because of this, we recommend that you create an administrative user in IAM Identity Center to use for everyday AWS tasks. Then, safeguard the root user credentials and use them to perform only those few account and service management tasks that require you to sign in as the root user. For the list of those tasks, see Tasks that require root user credentials.

* IAM

  An IAM user is an entity you create in AWS that represents the person or service that uses the IAM user to interact with AWS resources. These users are identities within your AWS account that have specific custom permissions. For example, you can create IAM users and give them permissions to create a directory in IAM Identity Center. IAM users have long-term credentials that they can use to access AWS using the AWS Management Console, or programmatically using the AWS CLI or AWS APIs

## Steps to use AWS TTS service in Python

1. Make root user account: [AWS link](https://aws.amazon.com/ko/)

2. Setting Multi Factor Authentication(MFA)

![image](https://github.com/kmw4097/OCR/assets/98750892/5a766081-15d8-4464-9f51-7f14b057f6c2)

![image](https://github.com/kmw4097/OCR/assets/98750892/c9fd5859-9dc6-4900-a584-dc26c5dff476)

3. Make IAM account

![image](https://github.com/kmw4097/OCR/assets/98750892/e679bee9-1b78-4cf7-9abb-2208f6af79de)

![image](https://github.com/kmw4097/OCR/assets/98750892/e85d976d-99ea-4f4a-a2ba-d7d5eeafdce4)

![image](https://github.com/kmw4097/OCR/assets/98750892/e94bdb30-263d-41ee-a887-4b5ce881af20)

Authorize AdministratorAccess to IAM account

![image](https://github.com/kmw4097/OCR/assets/98750892/b14efd2c-c156-45d0-a946-e385734c5972)

Download csv file and check your iam account and password

![aws_2](https://github.com/kmw4097/OCR/assets/98750892/feeb40b2-8126-4364-834d-9ffc1b34adf8)

4. Make IAM account access key

![aws_3](https://github.com/kmw4097/OCR/assets/98750892/4b402c4a-7a0b-4d0d-9d51-203b51162ea6)

5. Install aws cli

   ```pip install awscli```
   


