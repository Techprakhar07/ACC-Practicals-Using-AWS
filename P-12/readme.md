# Practical 12: Securely Access S3 Images Using Amazon CloudFront

## Objective
This practical covers setting up Amazon CloudFront to securely distribute images stored in an S3 bucket, ensuring low-latency access and enhanced security with signed URLs.

## Learning Outcomes
- Learn how to create and configure a CloudFront distribution.
- Configure access restrictions and signed URLs for secure access.
- Optimize data delivery from S3 using CloudFront.

## Key AWS Services Used
- **Amazon CloudFront**: Content delivery network (CDN) service.
- **Amazon S3**: Scalable object storage service.

## Prerequisites
- AWS account with permissions to create and manage CloudFront distributions and S3 buckets.
- Basic understanding of CDNs and caching.

## Practical Steps Overview
1. Create a CloudFront distribution with an S3 bucket as the origin.
2. Configure caching and security settings.
3. Set up signed URLs for restricted access to the images.
4. Verify the distribution and access images through CloudFront.

## References
- [Amazon CloudFront Documentation](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html)
- [Amazon S3 Documentation](https://docs.aws.amazon.com/s3/)
