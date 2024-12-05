# Practical 06: Access S3 Bucket Through EC2 Using IAM Role

## Objective
This practical demonstrates how to configure an IAM role to securely grant EC2 instances access to an S3 bucket. This setup allows applications running on EC2 instances to interact with S3 without embedding access keys.

## Learning Outcomes
- Understand how to create and attach an IAM role to an EC2 instance.
- Learn to grant S3 bucket permissions using IAM policies.
- Access and interact with S3 buckets from an EC2 instance.

## Key AWS Services Used
- **AWS EC2**: Virtual server instances.
- **Amazon S3**: Scalable object storage service.
- **AWS IAM**: Identity and Access Management service.

## Prerequisites
- AWS account with permissions to create EC2 instances, IAM roles, and S3 buckets.
- Basic knowledge of EC2 instances, IAM policies, and S3.

## Practical Steps Overview
1. Create an S3 bucket and upload a sample file.
2. Create an IAM role with S3 access policy.
3. Attach the IAM role to an EC2 instance.
4. Verify access to the S3 bucket from the EC2 instance.

## References
- [AWS EC2 Documentation](https://docs.aws.amazon.com/ec2/)
- [Amazon S3 Documentation](https://docs.aws.amazon.com/s3/)
- [AWS IAM Documentation](https://docs.aws.amazon.com/IAM/)
