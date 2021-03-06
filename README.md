# AWS Daily Tasks
**IAM Access Key Rotation**

Lists access keys older than 90 days and helps you to rotate them.

**EC2 Start / Stop instances**

Lists EC2 instances and helps you to start and stop them all at once.

usage: ec2_start_stop.py [-h] [--start] [--stop]

**Remove Unused EBS Volumes**

Lists unused Amazon EBS volumes and helps you to control AWS costs by deleting them.

**RDS Untagged Resources**

Lists untagged RDS resources and helps you to identify them.

**Public S3 Buckets**

Lists public S3 buckets by evaluating Bucket Policy, Access Control List and Block Public Access settings.

**Elastic IP Clean Up**

Lists unused Elastic IPs and helps you to stop the charges by releasing them.

**RDS Manual Snapshots**

Lists RDS instances and helps you to have manual snapshots all at once.

**Disable IAM Users Without MFA**

Lists all users without MFA enabled and helps you to terminate the user's ability to access AWS services.

**AWS Parameter Store Backup / Restore**

Lists all parameters and helps you to backup and restore sensitive data all at once.

usage: parameter_store_backup_restore.py [-h] [-b] [-r]

**Amazon Translate Large Text Documents**

Helps you to translate large text documents with Amazon Translate and Natural Language Toolkit for Python.

usage: translate_large_text_documents.py [-h] -l LANG

**AWS ECS Highlight Possible Bottlenecks**

Helps you to summarize CPU and memory usages across an ECS cluster over the last 24 hours.

**IAM Access Advisor Permissions Analysis**

Helps you to audit IAM roles by listing services not accessed for the last 180 days.