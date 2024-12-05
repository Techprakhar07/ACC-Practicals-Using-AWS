# Practical 07: IAM Role Custom Policy to Access S3

## Objective
This practical covers creating a custom IAM policy for granular S3 access control and assigning it to an IAM role for secure access.

## Learning Outcomes
- Learn to create custom IAM policies.
- Understand how to attach custom policies to IAM roles.
- Configure permissions for restricted access to an S3 bucket.

## Key AWS Services Used
- **AWS IAM**: Identity and Access Management service.
- **Amazon S3**: Scalable object storage service.

## Prerequisites
- AWS account with permissions to create IAM roles and policies.
- Basic understanding of IAM policy syntax.

## Practical Steps Overview
1. Create a custom IAM policy for S3 access.
2. Create an IAM role and attach the policy.
3. Assign the IAM role to an EC2 instance or Lambda function.
4. Test the access from the assigned instance.

## References
- [AWS IAM Policy Reference](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies.html)
- [Amazon S3 Documentation](https://docs.aws.amazon.com/s3/)
