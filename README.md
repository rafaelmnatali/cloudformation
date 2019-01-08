# cloudformation
Cloud Formation templates

In this project I'll upload the cloud formation templates that I'm currently working on. So, some of the files might be considered drafts or incomplete versions.

Look for the following repositories for final versions:

* codecommit - interactions with AWS CodeCommit
* openvpn - install and configure an EC2 instance with OpenVPN community edition.

Templates OK:

* dynamodb-table-ondemand.cform - create a DynamoDB table with On-Demand capacity instead of Provisioned capacity
* ddns.cform - to create a serverless solution to dynamically register EC2 instances in Route53. Based on https://github.com/awslabs/aws-lambda-ddns-function
* ec2_latestAMI - to create an EC2 instance with latest Amazon Linux 2 AMI available in the region
