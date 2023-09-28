### VPC

This module is going to create
* VPC
* Internet gateway
* 2 public subnets
* 2 private subnets
* 2 Database subnets

### Inputs
* cidr_block(Required) - User has to provide cidr block.
* enable_dns_hostnames(optional) - User can provide enable_dns_hostnames, ***default is true***
* enable_dns_support(optional) - User can provide enable_dns_support, ***default is true***
* common_tags(optional) -User can provide common tags for all resources, defualt is empty.
* VPC tags (optional) - User can provide vpc tags for all resources, defualt is empty.
* igw_tags(optional)- User can provide internet gateway tags for all resources, defualt is empty.
* public_subnet_cidr(Required)-user must provide a list of 2 public subnet CIDR.
* public_subnet_names(Required)-user must provide a list of 2 public subnet names.
* azs(Required)- User must provide 2 az.
* private_subnet_cidr(Required)-user must provide a list of 2 private subnet CIDR.
* private_subnet_names(Required)-user must provide a list of 2 private subnet names.
* database_subnet_cidr(Required)-user must provide a list of 2 database subnet CIDR.
* database_subnet_names(Required)-user must provide a list of 2 database subnet names.
