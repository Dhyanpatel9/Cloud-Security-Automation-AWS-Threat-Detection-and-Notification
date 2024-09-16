# Cloud Security Automation AWS Threat Detection and Notification
## Table of Contents
- [Overview](#overview)
- [Architecture](#architecture)
- [Prerequisites](#prerequisites)
- [Deployment Steps](#deployment-steps)
- [Testing the Setup](#testing-the-setup)
- [Cleanup](#cleanup)
- [Cost Considerations](#cost-considerations)
- [Conclusion](#conclusion)
- [References](#references)
- [License](#license)
- [Contact](#contact)

## Overview
This project implements an **AWS-based Threat Detection** **and Alerting System** designed to automatically detect and notify security teams of high-severity threats in a cloud environment. Leveraging **AWS GuardDuty** for real-time threat detection, **EventBridge** for event-driven triggers, **AWS Lambda** for processing findings, and **AmazonSNS** for sending email notifications, this solution enhances cloud security by providing automated monitoring and alerts.

The infrastructure is provisioned and managed using **Terraform**, enabling easy and scalable deployment.

Key Features:
- **Real-Time Threat Detection**: AWS GuardDuty continuously monitors the environment for malicious activities and security threats.
- **Event-Driven Processing**: Amazon EventBridge captures high-severity findings from GuardDuty and triggers AWS Lambda functions for further processing.
- **Automated Alerts**: AWS Lambda formats the findings into human-readable notifications and publishes them to Amazon SNS, which sends alerts via email to the security team.
- **Monitoring and Logging**: AWS CloudWatch tracks the performance and logs of the Lambda function for audit and troubleshooting.
This project demonstrates how automation can improve cloud security by streamlining the process of detecting and responding to security incidents in real-time.
## Architecture
The architecture of the AWS-based Threat Detection and Alerting System is shown below:

![Architecture Diagram](./Images/Architecture1.png)

## Prerequisites
- AWS account
- Terraform installed
...

## Deployment Steps
1. Clone the repository
2. Run `terraform init`
3. Run `terraform apply`
...

## Testing the Setup
Explain how to test the deployment here...

## Cleanup
Instructions for cleaning up the resources...

## Cost Considerations
Details on costs...

## Conclusion
Summarize your findings here...

## References
Any references or links...

## License
Details about the license...

## Contact
Information for reaching you...


