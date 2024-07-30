# -AWS-Cost-Optimization / AWS EBS Snapshot Cleanup

create a Lambda function that identifies EBS snapshots that are no longer associated with any active EC2 instance and deletes them to save on storage costs.


A Lambda function to identify and delete unused EBS snapshots, optimizing storage costs. 

## Features
- Creates EC2 instance and snapshots
- Identifies unused snapshots
- Deletes unused snapshots
- Automates with CloudWatch

## Setup
1. Create an EC2 instance and a snapshot.
2. Deploy the Lambda function.
3. Assign necessary IAM roles.
4. Test and automate with CloudWatch.
