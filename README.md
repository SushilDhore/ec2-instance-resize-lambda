# EC2 Instance Resize Lambda Function

This repository contains an AWS Lambda function for resizing EC2 instances. It stops the instance, modifies its instance type, and restarts it. The function is triggered by an event containing the instance ID.

## Features
- Stops the EC2 instance gracefully.
- Waits until the instance is completely stopped.
- Modifies the instance type.
- Restarts the instance after modification.
- Handles exceptions and timeouts effectively.

## Prerequisites
1. AWS account with permissions to manage EC2 instances.
2. Python 3.7 or higher.
3. Boto3 library installed (`pip install boto3`).

## Deployment
1. Clone this repository:
   ```bash
   git clone https://github.com/SushilDhore/ec2-instance-resize-lambda.git
