#!/bin/bash

##############
# Author: Lovepreet Singh
# Date: 26 Jan
#
# Version: v1
#
# This script will report the AWS resource usage
##############

set -x # debug mode

# AWS S3
# AWS EC2
# AWS Lambda
# AWS IAM Users
 
# list s3 buckets
aws s3 ls > resources.txt

# list EC2 instances
aws ec2 describe-instances >> resources.txt

# list lambda functions
aws lambda list-functions >> resources.txt

# list IAM Users
aws iam list-users >> resources.txt


