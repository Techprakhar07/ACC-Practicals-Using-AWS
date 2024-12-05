# Practical 05: Creating an Application Load Balancer and Auto Scaling Group in AWS

## Objective
To configure an Application Load Balancer (ALB) and an Auto Scaling Group (ASG) in AWS to distribute traffic across multiple EC2 instances for scalability and high availability.

## Learning Outcomes
- Learn how to set up an Application Load Balancer for traffic distribution.
- Understand how to create and manage an Auto Scaling Group for automatic scaling of EC2 instances.
- Integrate the ALB with the ASG to distribute load.

## Key AWS Services Used
- **AWS EC2**: Virtual server instances.
- **Application Load Balancer (ALB)**: A load balancer that routes traffic based on content.
- **Auto Scaling Group (ASG)**: A service for automatically adjusting the number of EC2 instances.

## Prerequisites
- AWS account with permissions to create EC2 instances, ALBs, and ASGs.
- Basic knowledge of AWS networking and instance management.

## Practical Steps Overview
1. Create an ALB and configure listeners and target groups.
2. Launch EC2 instances and register them with the target group.
3. Create an ASG and attach it to the ALB.
4. Test the setup by scaling up and down.

## References
- [AWS ALB Documentation](https://docs.aws.amazon.com/elasticloadbalancing/latest/application/introduction.html)
- [AWS Auto Scaling Documentation](https://docs.aws.amazon.com/autoscaling/ec2/userguide/Welcome.html)
