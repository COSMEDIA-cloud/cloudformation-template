# newRead

Template file to be loaded into AWS CloudFormation


## Description

By downloading the yaml file and using it as a CloudFormation startup template, you can automatically deploy AWS resources according to the template.


## Usage

<01_VPC_yaml>
A template for creating network-related resources such as VPCs in the AWS Tokyo region.
The following resources are created.
* VPC
* Public subnets (AZ-a and AZ-c)
* Private subnets (AZ-a and AZ-c)
* Route table
* Network ACL
* Internet gateway
