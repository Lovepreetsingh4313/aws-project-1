AWS Resource Tracker is a simple shell script designed to report the usage of various AWS resources in our account.
The script utilizes the AWS CLI to list key AWS resources such as S3 buckets, EC2 instances, Lambda functions, and IAM users.
This project is useful for beginners learning shell scripting and AWS CLI or for quick visibility into resource usage.
AWS S3: Lists all the S3 buckets.
AWS EC2: Displays details of all EC2 instances.
AWS Lambda: Lists all the Lambda functions.
AWS IAM Users: Displays all IAM users in the account.
The script uses set -x to enable debug mode, which shows each command and its execution details.
