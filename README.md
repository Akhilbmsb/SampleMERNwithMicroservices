# orchestration project


## Prerequisites for project to kick start project

Before you start pls see you have these
- An AWS account.
- Python installed on your system.

## 1. Setting Up AWS CLI

### Installation of AWS CLI

1. Download AWS CLI: Visit the [AWS CLI installation page](https://aws.amazon.com/cli/) and download the appropriate version for your operating system.

2. Install AWS CLI: Follow the installation instructions provided on the download page for your OS.

### Configuration of AWS CLI

1. AWS Credentials: You'll need your AWS Access Key ID and Secret Access Key. You can find these in your AWS Management Console under IAM.

2. Configure AWS CLI:
   - Open your terminal.
   - Run the command `aws configure`.
   - Enter your AWS Access Key ID, Secret Access Key, default region name, and default output format when prompted in terminal.

## 2. Setting Up Boto3

### Installation of boto3

1. Install Boto3: Run the command `pip install boto3` in your terminal or command prompt.

### Configuration of boto3 for aws cli

Boto3 uses the credentials stored by AWS CLI. If AWS CLI is configured.
