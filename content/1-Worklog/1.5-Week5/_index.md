---
title: "Week 5 Worklog"
date: 2026-05-18
weight: 5
chapter: false
pre: "<b>1.5.</b>"
---

{{% notice info %}}
This worklog summarizes the hands-on laboratories and practical activities completed during the fifth week of the First Cloud AI Journey Bootcamp.
{{% /notice %}}

# Week 5 Objectives

The objectives for Week 5 were:

- Learn how to use AWS Cloud9 as a cloud-based development environment.
- Practice Linux command-line operations in AWS Cloud9.
- Learn and use AWS CLI to manage AWS resources.
- Deploy a static website using Amazon S3.
- Configure Amazon S3 Static Website Hosting.
- Accelerate website delivery with Amazon CloudFront.
- Learn Amazon S3 Bucket Versioning and object management.
- Explore Cross-Region Replication for high availability.
- Apply AWS storage security and resource cleanup best practices.

---

# Weekly Tasks

| Day | Tasks | Start Date | Completion Date | Reference Material |
|------|-------|------------|-----------------|--------------------|
| 1 | - Create an AWS Cloud9 environment.<br>- Explore the Cloud9 IDE.<br>- Practice basic Linux commands.<br>- Learn file management in Cloud9. | 18/05/2026 | 18/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 2 | - Practice AWS CLI commands in Cloud9.<br>- Manage EC2 resources using AWS CLI.<br>- Learn CLI configuration.<br>- Clean up Cloud9 resources. | 19/05/2026 | 19/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 3 | - Create an Amazon S3 Bucket.<br>- Enable Static Website Hosting.<br>- Configure Public Access settings.<br>- Upload website files to S3. | 20/05/2026 | 20/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 4 | - Test the S3 static website.<br>- Configure Amazon CloudFront.<br>- Verify website accessibility through CDN.<br>- Improve website performance. | 21/05/2026 | 21/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 5 | - Enable Bucket Versioning.<br>- Practice object version management.<br>- Learn Cross-Region Replication.<br>- Organize and manage S3 objects. | 22/05/2026 | 22/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 6 | - Review Cloud9, AWS CLI and Amazon S3 laboratories.<br>- Clean up AWS resources.<br>- Summarize cloud storage concepts.<br>- Prepare for Week 6 laboratories. | 23/05/2026 | 23/05/2026 | https://cloudjourney.awsstudygroup.com/ |

---

# Activities Performed

## 1. AWS Cloud9 Development Environment

During this week, I learned how to create and use an AWS Cloud9 development environment for cloud-based programming.

The activities completed included:

- Creating a Cloud9 environment.
- Launching the Cloud9 IDE.
- Creating a new terminal.
- Exploring the Cloud9 dashboard.
- Understanding the workspace structure.
- Managing files and folders.
- Editing text files inside Cloud9.

Using Cloud9 allowed me to develop applications directly in the AWS environment without installing development tools on my local computer.

---

## 2. Linux Command Line and AWS CLI

After creating the Cloud9 environment, I practiced Linux commands and AWS CLI.

The laboratory included:

- Using the Terminal interface.
- Running Linux commands:
  - pwd
  - ls
  - cd
  - mkdir
  - touch
  - rm
- Editing README.md.
- Creating new files.
- Saving project files.
- Returning to the AWS Management Console.

I also practiced AWS CLI commands, including:

- Checking AWS CLI configuration.
- Listing EC2 instances.
- Viewing AWS Regions.
- Retrieving account information.
- Managing AWS resources using command-line tools.

This workshop improved my understanding of Linux administration and AWS automation.

---

## 3. Amazon S3 Static Website Hosting

This week also focused on Amazon S3 as an object storage service.

The laboratory included:

- Creating an Amazon S3 Bucket.
- Uploading website files.
- Enabling Static Website Hosting.
- Configuring bucket permissions.
- Configuring Public Access Block.
- Allowing public object access.
- Testing the website endpoint.

Through this workshop, I understood how Amazon S3 can host static websites without requiring a traditional web server.

<p align="center">
<img src="/images/s3b.png" width="700">
</p>

<p align="center">
<i>Figure 10. Amazon S3 Static Website Hosting.</i>
</p>

---

## 4. Amazon CloudFront

To improve website performance, I configured Amazon CloudFront.

The activities included:

- Creating a CloudFront Distribution.
- Selecting the S3 bucket as the Origin.
- Configuring cache behavior.
- Testing website delivery through CloudFront.
- Comparing direct S3 access with CloudFront.

I learned how Content Delivery Networks (CDNs) improve website performance and reduce latency by distributing content through edge locations worldwide.

<p align="center">
<img src="/images/cloudfront.png" width="700">
</p>

<p align="center">
<i>Figure 11. Amazon CloudFront Distribution.</i>
</p>

---

## 5. Amazon S3 Versioning and Replication

To improve data durability and availability, I explored advanced Amazon S3 features.

The activities completed included:

- Enabling Bucket Versioning.
- Uploading multiple object versions.
- Restoring previous object versions.
- Moving objects between folders.
- Learning Cross-Region Replication (CRR).
- Understanding multi-region data protection.

These features help protect data against accidental deletion while improving disaster recovery capabilities.

---

## 6. Resource Cleanup

After completing all laboratories, I removed unused AWS resources to prevent unnecessary charges.

The cleanup process included:

- Deleting Cloud9 environments.
- Removing CloudFront distributions.
- Deleting S3 buckets and objects.
- Verifying no unnecessary resources remained.

This reinforced the importance of cloud cost optimization and resource management.

---

# Knowledge Acquired

After completing Week 5, I was able to:

- Create and manage AWS Cloud9 environments.
- Use Linux command-line tools in a cloud environment.
- Manage AWS resources using AWS CLI.
- Deploy static websites using Amazon S3.
- Configure Amazon S3 Static Website Hosting.
- Configure Public Access for S3 buckets.
- Accelerate websites using Amazon CloudFront.
- Enable Amazon S3 Bucket Versioning.
- Understand Cross-Region Replication.
- Apply cloud storage security and best practices.
- Perform AWS resource cleanup to optimize costs.

---

# Challenges Encountered

During Week 5, I encountered several challenges:

- Becoming familiar with the Cloud9 IDE.
- Learning Linux command-line operations.
- Configuring S3 bucket permissions correctly.
- Understanding Static Website Hosting settings.
- Waiting for CloudFront distributions to deploy.
- Understanding object version management in Amazon S3.

---

# Solutions

To overcome these challenges, I:

- Practiced Linux commands repeatedly.
- Followed AWS official workshop documentation.
- Reviewed Amazon S3 permission settings carefully.
- Tested website deployment several times.
- Waited for CloudFront deployment before testing.
- Removed unused cloud resources after each laboratory.
- Consulted mentors whenever configuration issues occurred.

---

# Learning Outcomes

After completing Week 5, I successfully:

- Created an AWS Cloud9 development environment.
- Used Linux commands and AWS CLI effectively.
- Deployed a static website on Amazon S3.
- Configured Static Website Hosting.
- Accelerated content delivery using Amazon CloudFront.
- Enabled Amazon S3 Bucket Versioning.
- Learned Cross-Region Replication concepts.
- Improved practical skills in cloud storage, website deployment and AWS development tools.

---

# Reflection

Week 5 focused on cloud development tools and object storage services. Through hands-on laboratories using AWS Cloud9, AWS CLI, Amazon S3, and Amazon CloudFront, I gained practical experience in developing cloud applications, deploying static websites, managing cloud storage, and optimizing content delivery. These activities strengthened my understanding of AWS development workflows and cloud storage architecture, providing a solid foundation for deploying more complex cloud applications in the following weeks.