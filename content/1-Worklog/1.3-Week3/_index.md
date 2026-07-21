---
title: "Week 3 Worklog"
date: 2026-05-04
weight: 3
chapter: false
pre: "<b>1.3.</b>"
---

{{% notice info %}}
This worklog summarizes the hands-on laboratories and practical activities completed during the third week of the First Cloud AI Journey Bootcamp.
{{% /notice %}}

# Week 3 Objectives

The objectives for Week 3 were:

- Study Amazon EC2 and its core components.
- Understand Amazon Machine Images (AMI), Instance Types and EBS.
- Learn AWS Identity and Access Management (IAM).
- Explore Amazon VPC networking concepts.
- Configure Security Groups and network security.
- Launch and manage EC2 instances.
- Connect to EC2 instances using SSH.
- Understand AWS networking architecture and security best practices.

---

# Weekly Tasks

| Day | Tasks | Start Date | Completion Date | Reference Material |
|------|-------|------------|-----------------|--------------------|
| 1 | - Study Amazon EC2 fundamentals.<br>- Learn Instance Types, AMI, Key Pair and Amazon EBS.<br>- Understand EC2 deployment workflow. | 01/05/2026 | 01/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 2 | - Study AWS Identity and Access Management (IAM).<br>- Create IAM Users, Groups and Policies.<br>- Configure IAM Roles and apply security best practices. | 02/05/2026 | 02/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 3 | - Learn Amazon VPC fundamentals.<br>- Configure VPC, Subnets, Route Tables and Internet Gateway.<br>- Explore Security Groups and Network ACLs. | 03/05/2026 | 03/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 4 | - Launch an Amazon EC2 Instance.<br>- Configure Security Groups.<br>- Create Key Pair and connect using SSH.<br>- Verify EC2 instance status. | 04/05/2026 | 04/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 5 | - Practice VPC networking.<br>- Configure Public and Private Subnets.<br>- Review EC2 networking architecture and resource security. | 05/05/2026 | 05/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 6 | - Review EC2, IAM and VPC laboratories.<br>- Summarize networking and security concepts.<br>- Prepare the AWS environment for Week 4. | 06/05/2026 | 06/05/2026 | https://cloudjourney.awsstudygroup.com/ |

---

# Activities Performed

## 1. Learning Amazon EC2

During this week, I studied Amazon EC2, the core compute service of AWS.

Topics covered included:

- Amazon EC2 overview
- Instance Types
- Amazon Machine Images (AMI)
- Amazon Elastic Block Store (EBS)
- Key Pair
- Elastic IP
- EC2 Instance Lifecycle

Through this study, I understood how AWS provides scalable virtual servers for cloud applications.

<p align="center">
<img src="/images/ec2.png" width="700">
</p>

<p align="center">
<i>Figure 4. Amazon EC2 Overview.</i>
</p>

---

## 2. AWS Identity and Access Management (IAM)

This week, I explored **AWS Identity and Access Management (IAM)** to understand how AWS manages identities, authentication, and authorization for cloud resources.

The activities completed included:

- Understanding Authentication and Authorization.
- Differentiating between Root User and IAM User.
- Creating IAM Users.
- Creating IAM Groups.
- Creating IAM Policies.
- Assigning users to groups.
- Creating IAM Roles.
- Testing Assume Role.
- Enabling password policies.
- Understanding Multi-Factor Authentication (MFA).
- Applying the Principle of Least Privilege.

Through these activities, I learned how AWS securely manages user identities and permissions while following security best practices.

<p align="center">
<img src="/images/aws-iam.png" width="700">
</p>

<p align="center">
<i>Figure 5. AWS IAM Dashboard and identity management.</i>
</p>

The laboratory also included creating an administrator group and configuring an IAM user with administrative privileges for laboratory activities.

The following tasks were completed:

- Creating an **AdminGroup**.
- Attaching the **AdministratorAccess** managed policy.
- Creating an **AdminUser**.
- Adding the user to the administrator group.
- Downloading the login credentials (.csv).
- Signing in using the IAM User account.
- Verifying administrative permissions by accessing AWS services.

<p align="center">
<img src="/images/aws-gr.png" width="700">
</p>

<p align="center">
<i>Figure 6. Creating an administrator group and IAM user.</i>
</p>
---

## 3. Amazon VPC and Networking

This week also focused on understanding AWS networking.

Topics studied included:

- Amazon VPC
- CIDR Blocks
- Public and Private Subnets
- Route Tables
- Internet Gateway
- NAT Gateway
- VPC Resource Map
- VPC Flow Logs

I learned how AWS isolates cloud resources within virtual networks while allowing secure communication.

---

## 4. Security Groups and Network ACLs

To secure cloud resources, I explored AWS network security services.

Activities included:

- Creating Security Groups
- Configuring Inbound Rules
- Configuring Outbound Rules
- Opening ports 22, 80 and 443
- Understanding Network ACLs
- Comparing Security Groups and Network ACLs

This laboratory helped me understand the layered security model used by AWS.

---

## 5. Launching an Amazon EC2 Instance

I completed the EC2 deployment laboratory by performing the following tasks:

- Creating a Key Pair
- Launching an EC2 Instance
- Selecting an Amazon Linux AMI
- Choosing the Instance Type
- Configuring Security Groups
- Connecting to the instance using SSH
- Monitoring instance status
- Stopping and terminating the instance

<p align="center">
<img src="/images/ec2-instance.png" width="700">
</p>

<p align="center">
<i>Figure 7. Amazon EC2 Instance Deployment.</i>
</p>

---

# Knowledge Acquired

After completing Week 3, I was able to:

- Understand Amazon EC2 architecture.
- Deploy and manage EC2 instances.
- Differentiate Instance Types and AMIs.
- Configure Amazon EBS storage.
- Create and manage IAM Users, Groups, Policies and Roles.
- Understand Authentication and Authorization.
- Configure Amazon VPC networking.
- Deploy Public and Private Subnets.
- Configure Security Groups and Network ACLs.
- Connect securely to EC2 instances using SSH.

---

# Challenges Encountered

During Week 3, I encountered several challenges:

- Understanding AWS networking architecture.
- Distinguishing Security Groups from Network ACLs.
- Configuring IAM permissions correctly.
- Connecting to EC2 instances through SSH.
- Understanding the relationship between EC2, VPC and IAM.

---

# Solutions

To overcome these challenges, I:

- Followed AWS official documentation.
- Repeated EC2 deployment laboratories several times.
- Reviewed networking diagrams.
- Practiced IAM configuration with different permission levels.
- Discussed technical issues with mentors and Bootcamp members.
- Documented the deployment process for future reference.

---

# Learning Outcomes

After completing Week 3, I successfully:

- Deployed Amazon EC2 instances.
- Configured IAM Users, Groups, Policies and Roles.
- Built a basic Amazon VPC network.
- Configured Security Groups and network security.
- Connected to EC2 instances via SSH.
- Applied AWS security best practices.
- Improved practical skills in AWS infrastructure deployment.

---

# Reflection

Week 3 focused on cloud infrastructure deployment, networking and security. Through hands-on laboratories involving Amazon EC2, IAM and Amazon VPC, I gained practical experience in deploying cloud resources, configuring secure access, and building virtual networks. These skills provide an essential foundation for more advanced AWS services and real-world cloud architecture in the following weeks.