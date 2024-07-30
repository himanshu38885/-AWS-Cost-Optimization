# -AWS-Cost-Optimization / AWS EBS Snapshot Cleanup

create a Lambda function that identifies EBS snapshots that are no longer associated with any active EC2 instance and deletes them to save on storage costs.


A Lambda function to identify and delete unused EBS snapshots, optimizing storage costs. 

## Features
- Creates EC2 instance and snapshots
- Identifies unused snapshots
- Deletes unused snapshots automatically and save the cost
- Automates with CloudWatch

## Setup
1. Create an EC2 instance and a snapshot.
2. Deploying the Lambda function change the default execution time of the Lambda like 10sec .
3. Assign necessary IAM roles (create a policy for ec2 permissions such as: describe instances,describe volumes,describe snapshots and delete snapshots.
4. Test and automate with CloudWatch.
