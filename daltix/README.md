# Daltix
Cloud Formation templates

In this project I created a series of templates to attend the requeriments of the "Case 2"

Below is the description of each template and the order that they should be applied:

* case2_vpc - creates a 3 tier network segmentation (Public, Private, Data tiers), security groups, NAT Gateways, NACLs
* case2_iamrole - creates an IAM Role and IAM Instance Profile to be used by the EC2 instances
* case2_s3bucket - creates an S3 bucket
* case2_s3bucket_policy - creates an IAM policy allowing EC2 to access the bucket previously created and associate it wit the role created in step 2.
* case2_publicserver - launch an EC2 instance in the Public Subnet with an Elastic IP
* case2_privateserver - launch 2 EC2 instances in the Private Subnet
* case2_rds_instance - launch a MySQL database
