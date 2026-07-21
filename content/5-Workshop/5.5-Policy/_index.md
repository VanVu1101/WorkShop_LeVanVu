---
title : "VPC Endpoint Policies"
date : 2024-01-01
weight : 5
chapter : false
pre : " <b> 5.5. </b> "
---

When you create an interface or gateway endpoint, you can attach an endpoint policy to it that controls access to the service to which you are connecting. A VPC endpoint policy is an IAM resource policy that you attach to an endpoint. If you do not attach a policy when you create an endpoint, AWS attaches a default policy for you that allows full access to the service through the endpoint.

You can create a policy that restricts access to specific S3 buckets only. This is useful if you only want certain S3 Buckets to be accessible through the endpoint.

In this section, you will learn how to configure a VPC endpoint policy that restricts access to specific Amazon S3 resources through the VPC endpoint.


#### Configure EC2 environment for web application deployment

1. Create and configure an EC2 instance for hosting the web application.

2. Review the EC2 instance configuration including:
- Instance type
- VPC and subnet configuration
- Security Group settings
- IAM Role (if required)

![ec1](/images/ec2.2.jpg)
*Figure ec1. EC2 instance configuration and network settings.*

3. Configure the Security Group to allow required traffic for future application deployment:

- 22 - SSH access
- 80 - HTTP access
- 443 - HTTPS access

![ec2](/images/ec2.jpg)
*Figure ec2. EC2 security group inbound rules configuration.*

4. The EC2 instance environment has been prepared. The application deployment and web service configuration will be completed in the next stage.

#### Configure AWS Budgets for cost monitoring

To control AWS spending and avoid unexpected charges, AWS Budgets was configured to monitor resource usage and estimated costs.

The budget configuration includes:

- Creating a monthly cost budget.
- Setting a target spending limit.
- Configuring email notifications when actual or forecasted costs exceed the defined threshold.
- Monitoring AWS Free Tier usage and resource consumption.

![budget](/images/budget.jpg)

*Figure budget. AWS Budgets configuration for monitoring monthly AWS costs.*

After configuring AWS Budgets, the AWS account can automatically track spending and notify users before exceeding the planned cost limit.