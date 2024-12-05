# Practical 11: Encrypt an S3 Bucket Using AWS KMS

## Objective
Learn how to secure data stored in an S3 bucket by enabling encryption with AWS Key Management Service (KMS). This ensures that data at rest is encrypted and only accessible to authorized users.

## Learning Outcomes
- Understand how to enable encryption for an S3 bucket using AWS KMS.
- Learn to create and manage KMS keys.
- Verify data encryption in the S3 bucket.

## Key AWS Services Used
- **Amazon S3**: Scalable object storage service.
- **AWS KMS**: Key Management Service for managing encryption keys.

## Prerequisites
- AWS account with permissions to create and manage S3 buckets and KMS keys.
- Basic knowledge of data encryption and KMS.

## Practical Steps Overview
1. Create a KMS key for encryption.
2. Configure the S3 bucket to use the KMS key for encryption.
3. Upload data to the bucket and verify encryption.
4. Test access control by verifying who can decrypt the data.

## References
- [Amazon S3 Documentation](https://docs.aws.amazon.com/s3/)
- [AWS KMS Documentation](https://docs.aws.amazon.com/kms/latest/developerguide/overview.html)
