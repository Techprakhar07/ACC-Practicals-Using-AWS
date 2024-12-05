# Practical 08: Encrypt an Unencrypted RDS DB Instance

## Objective
Learn how to encrypt an existing unencrypted Amazon RDS instance using the AWS Management Console or CLI, ensuring data security at rest.

## Learning Outcomes
- Understand how to enable encryption on an RDS instance.
- Learn to migrate data to an encrypted RDS instance.
- Familiarize with encryption keys and KMS.

## Key AWS Services Used
- **Amazon RDS**: Managed relational database service.
- **AWS KMS**: Key Management Service for managing encryption keys.

## Prerequisites
- AWS account with permissions to create and modify RDS instances and KMS keys.
- Basic understanding of RDS and encryption concepts.

## Practical Steps Overview
1. Create a snapshot of the existing unencrypted RDS instance.
2. Copy the snapshot and enable encryption.
3. Restore the encrypted snapshot to create a new RDS instance.
4. Verify the encryption settings.

## References
- [Amazon RDS Documentation](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html)
- [AWS KMS Documentation](https://docs.aws.amazon.com/kms/latest/developerguide/overview.html)
