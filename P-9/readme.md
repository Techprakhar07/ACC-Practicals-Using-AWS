# Practical 09: Export Amazon RDS DB Snapshot to S3

## Objective
This practical demonstrates how to export an RDS DB snapshot to an S3 bucket for data backup and archiving purposes.

## Learning Outcomes
- Understand how to export RDS snapshots to an S3 bucket.
- Learn to configure S3 bucket permissions for data export.
- Familiarize with the AWS CLI commands for exporting RDS snapshots.

## Key AWS Services Used
- **Amazon RDS**: Managed relational database service.
- **Amazon S3**: Scalable object storage service.
- **AWS IAM**: Identity and Access Management service.

## Prerequisites
- AWS account with permissions to create and manage RDS snapshots, S3 buckets, and IAM policies.
- An existing RDS instance with a snapshot created.

## Practical Steps Overview
1. Create an S3 bucket to store the exported snapshot data.
2. Grant necessary permissions for the RDS service to write to the S3 bucket.
3. Export the RDS snapshot to the S3 bucket.
4. Verify the exported data in the S3 bucket.

## References
- [Amazon RDS Documentation](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html)
- [Amazon S3 Documentation](https://docs.aws.amazon.com/s3/)
- [AWS CLI Documentation](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-welcome.html)
