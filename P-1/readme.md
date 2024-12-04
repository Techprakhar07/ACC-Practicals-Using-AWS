# Practical 01: Configuring a CloudWatch Alarm for Lambda Invocation Errors with SNS Notifications

## Objective
The objective of this practical is to configure a system that monitors AWS Lambda function errors and sends notifications using Amazon Simple Notification Service (SNS). This setup ensures immediate awareness of potential issues during Lambda function execution, which is crucial for maintaining the reliability and uptime of cloud-based applications.

## Learning Outcomes
- Gain hands-on experience with AWS Lambda, CloudWatch, and SNS.
- Learn to create Lambda functions and simulate errors for testing.
- Understand how to set up and configure CloudWatch alarms.
- Configure SNS topics and subscriptions to receive notifications.

## Key AWS Services Used
- **AWS Lambda**: A serverless compute service that runs code in response to events.
- **Amazon CloudWatch**: A monitoring service for AWS cloud resources and applications.
- **Amazon SNS**: A notification service for sending messages to subscribed endpoints.

## Prerequisites
- An active AWS account with sufficient IAM permissions to create and manage Lambda functions, CloudWatch alarms, and SNS topics.
- Basic knowledge of AWS Lambda and cloud architecture.
- Access to an email account to verify SNS notifications.

## Practical Steps Overview
This practical involves creating and testing a Lambda function, setting up CloudWatch to monitor metrics, configuring an SNS topic, and setting up a CloudWatch alarm that sends notifications via SNS.

## References
- [AWS Lambda Documentation](https://docs.aws.amazon.com/lambda/)
- [Amazon CloudWatch Documentation](https://docs.aws.amazon.com/cloudwatch/)
- [Amazon SNS Documentation](https://docs.aws.amazon.com/sns/)
