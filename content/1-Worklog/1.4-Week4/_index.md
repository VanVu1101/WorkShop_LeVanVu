---
title: "Week 4 Worklog"
date: 2026-05-08
weight: 4
chapter: false
pre: "<b>1.4.</b>"
---


# Week 4 Objectives

The objectives for Week 4 were:

- Launch Microsoft Windows Server and Amazon Linux EC2 instances.
- Practice connecting to EC2 instances using RDP and SSH.
- Learn advanced Amazon EC2 management.
- Create EBS Snapshots and Custom AMIs.
- Deploy web applications on Amazon Linux and Windows Server.
- Install LAMP Stack, phpMyAdmin and Node.js.
- Understand IAM Cost & Usage Governance.
- Practice AWS resource cleanup and cost optimization.

---

# Weekly Tasks

| Day | Tasks | Start Date | Completion Date | Reference Material |
|------|-------|------------|-----------------|--------------------|
| 1 | - Prepare networking environment.<br>- Create Linux VPC and Windows VPC.<br>- Configure Security Groups for Linux and Windows instances. | 08/05/2026 | 08/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 2 | - Launch Microsoft Windows Server 2025 EC2 instance.<br>- Connect using Remote Desktop (RDP).<br>- Verify Windows instance configuration. | 09/05/2026 | 09/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 3 | - Launch Amazon Linux 2023 EC2 instance.<br>- Connect using SSH.<br>- Explore Amazon EC2 management features including Instance Types, EBS Snapshots and Custom AMIs. | 10/05/2026 | 10/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 4 | - Install Apache, MariaDB, PHP and phpMyAdmin.<br>- Install Node.js on Amazon Linux.<br>- Deploy the AWS User Management Application. | 11/05/2026 | 11/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 5 | - Install XAMPP and Node.js on Windows Server.<br>- Deploy Node.js application on Windows EC2.<br>- Test application accessibility. | 12/05/2026 | 12/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 6 | - Study IAM Cost & Usage Governance.<br>- Configure IAM policies for cost governance.<br>- Restrict EC2 deployment and AWS Regions.<br>- Clean up all AWS resources after completing the laboratories. | 13/05/2026 | 13/05/2026 | https://cloudjourney.awsstudygroup.com/ |

---

# Activities Performed

## 1. Preparing the EC2 Laboratory Environment

Prepared the networking environment before deploying EC2 instances.

Activities included:

- Creating a Linux VPC.
- Creating a Windows VPC.
- Configuring Security Groups.
- Configuring inbound and outbound rules.
- Preparing networking for EC2 deployment.

<p align="center">
<img src="/images/vpc.png" width="700">
</p>

<p align="center">
<i>Figure 8. Preparing the laboratory networking environment.</i>
</p>

---

## 2. Deploying Microsoft Windows Server 2025

Created a Microsoft Windows Server EC2 instance for application deployment.

Activities included:

- Launching Windows Server 2025.
- Selecting the appropriate Instance Type.
- Creating a Key Pair.
- Configuring Security Groups.
- Retrieving the Administrator Password.
- Connecting using Remote Desktop (RDP).
- Verifying server functionality.

<p align="center">
<img src="/images/vpc-ins.png" width="700">
</p>

<p align="center">
<i>Figure 9. Microsoft Windows Server 2025 running on Amazon EC2.</i>
</p>

---

## 3. Deploying Amazon Linux EC2

Practiced deploying Linux servers on AWS.

Activities included:

- Launching Amazon Linux 2023.
- Connecting using SSH.
- Managing EC2 instances.
- Starting, stopping and rebooting instances.

Advanced EC2 management included:

- Modifying Instance Types.
- Creating Amazon EBS Snapshots.
- Creating Custom AMIs.
- Launching new instances from Custom AMIs.
- Learning EC2 recovery procedures.

<p align="center">
<img src="/images/linux-is.png" width="700">
</p>

<p align="center">
<i>Figure 10. Amazon Linux EC2 instance.</i>
</p>

---

## 4. Deploying Applications on Amazon Linux

Built a complete web application environment on Amazon Linux.

Activities included:

- Installing Apache Web Server.
- Installing MariaDB.
- Installing PHP.
- Configuring phpMyAdmin.
- Installing Node.js.
- Deploying the AWS User Management Application.
- Testing application accessibility.

Through this laboratory, I gained practical experience in deploying full-stack applications on Amazon EC2.

<p align="center">
<img src="/images/lamp.png" width="700">
</p>

<p align="center">
<i>Figure 11. chạy lamp.</i>
</p>

---

## 5. Deploying Node.js on Windows Server

Practiced deploying applications on Windows Server.

Activities included:

- Installing XAMPP.
- Installing Node.js.
- Configuring runtime environment.
- Deploying the AWS User Management Application.
- Testing application execution.

This laboratory helped me compare application deployment between Linux and Windows environments.

---

## 6. IAM Cost & Usage Governance

Studied IAM policies for controlling AWS resource usage and managing cloud costs.

Activities included:

- Restricting AWS Regions.
- Limiting EC2 Instance Families.
- Restricting EC2 Instance Types.
- Controlling Amazon EBS storage types.
- Limiting resource deletion based on company IP addresses.
- Restricting deletion permissions during specific time periods.

These governance policies improve cloud security while preventing unnecessary costs.
---

## 7. Cleaning Up Resources

After completing all laboratories, cloud resources were removed to avoid unnecessary charges.

Resources deleted included:

- EC2 Instances.
- Custom AMIs.
- EBS Volumes.
- EBS Snapshots.
- Security Groups.
- IAM Users.
- IAM Roles.
- Temporary resources created during the laboratories.

---

# Knowledge Acquired

After completing Week 4, I was able to:

- Deploy Microsoft Windows Server and Amazon Linux on EC2.
- Connect using RDP and SSH.
- Manage EC2 Instances efficiently.
- Create Amazon EBS Snapshots.
- Build Custom AMIs.
- Deploy applications on Linux and Windows.
- Install LAMP Stack and Node.js.
- Configure phpMyAdmin.
- Apply IAM Cost & Usage Governance policies.
- Clean up AWS resources following best practices.

---

# Challenges Encountered

During Week 4, I encountered several challenges:

- Configuring Windows Remote Desktop.
- Deploying applications on two different operating systems.
- Creating and managing Custom AMIs.
- Configuring IAM Governance policies.
- Understanding AWS resource restrictions.

---

# Solutions

To overcome these challenges, I:

- Followed AWS official workshop documentation.
- Practiced deployment multiple times.
- Reviewed AWS Documentation.
- Compared Linux and Windows deployment workflows.
- Cleaned up unused resources immediately after each laboratory.
- Consulted mentors and Bootcamp members when encountering issues.

---

# Learning Outcomes

After completing Week 4, I successfully:

- Built complete EC2 laboratory environments.
- Managed Windows and Linux EC2 instances.
- Deployed web applications on Amazon EC2.
- Installed and configured Node.js and LAMP.
- Applied IAM governance policies.
- Improved practical cloud deployment skills.
- Strengthened understanding of AWS infrastructure management.

---

# Reflection

Week 4 focused on advanced Amazon EC2 administration and application deployment. Through hands-on laboratories involving Windows Server, Amazon Linux, LAMP Stack, Node.js and IAM Cost & Usage Governance, I gained valuable experience in deploying, managing and securing cloud infrastructure. These practical skills provide a strong foundation for developing scalable cloud-native applications and implementing production-ready AWS environments in the following weeks.