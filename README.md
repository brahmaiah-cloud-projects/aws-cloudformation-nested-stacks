# AWS CloudFormation Nested Stack Project
 
This project deploys:
 
- VPC
- Public Subnets
- Internet Gateway
- Route Tables
- ALB
- Target Group
- Listener
- EC2 Instance
- SNS Topic
- CloudWatch Alarm
 
Architecture:
 
Internet
↓
ALB
↓
Listener
↓
Target Group
↓
EC2
 
Monitoring:
 
EC2
↓
CloudWatch Alarm
↓
SNS Topic
