---
title: "Week 7 Worklog"
date: 2026-06-01
weight: 7
chapter: false
pre: "<b>1.7.</b>"
---

{{% notice info %}}
This worklog summarizes the hands-on laboratories and practical activities completed during the seventh week of the First Cloud AI Journey Bootcamp. The main focus of this week was implementing hybrid DNS architecture using Amazon Route 53, AWS CloudFormation, AWS Directory Service, and Route 53 Resolver to integrate AWS cloud infrastructure with a simulated on-premise DNS environment.
{{% /notice %}}

# Week 7 Objectives

The objectives for Week 7 were:

- Understand Amazon Route 53 DNS service architecture.
- Learn hybrid DNS concepts between AWS and on-premise environments.
- Understand AWS CloudFormation Infrastructure as Code (IaC).
- Deploy AWS networking infrastructure using CloudFormation templates.
- Configure VPC, Subnets, Security Groups and EC2 resources.
- Deploy AWS Managed Microsoft Active Directory.
- Configure Remote Desktop Gateway access.
- Implement Route 53 Resolver hybrid DNS architecture.
- Configure Outbound Resolver Endpoint.
- Configure Inbound Resolver Endpoint.
- Create Resolver Rules for DNS forwarding.
- Test DNS resolution between AWS and simulated on-premise environments.
- Practice AWS resource cleanup and management.


# Weekly Tasks

| Day | Tasks | Start Date | Completion Date | Reference Material |
|---|---|---|---|---|
| Day 1 | Study Amazon Route 53 architecture, DNS resolution process, and hybrid DNS concepts. | 01/06/2026 | 01/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| Day 2 | Create EC2 Key Pair, download CloudFormation template, and deploy AWS infrastructure. | 02/06/2026 | 02/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| Day 3 | Configure Security Groups, review VPC architecture, and connect Remote Desktop Gateway using RDP. | 03/06/2026 | 03/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| Day 4 | Deploy AWS Managed Microsoft Active Directory and configure domain environment. | 04/06/2026 | 04/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| Day 5 | Configure Route 53 Outbound Resolver Endpoint and DNS forwarding. | 05/06/2026 | 05/06/2026 |https://cloudjourney.awsstudygroup.com/ |
| Day 6 | Create Resolver Rules and configure Route 53 Inbound Resolver Endpoint. | 06/06/2026 | 06/06/2026 | https://cloudjourney.awsstudygroup.com/|
| Day 7 | Test DNS communication, verify hybrid DNS architecture, and clean up AWS resources. | 07/06/2026 | 07/06/2026 | https://cloudjourney.awsstudygroup.com/ |


# Week 7 Achievements

During Week 7, I successfully implemented a hybrid DNS architecture using AWS services.

The completed architecture included:

- Amazon VPC network infrastructure.
- Public and private subnets.
- EC2 Remote Desktop Gateway server.
- AWS Managed Microsoft Active Directory.
- Amazon Route 53 Resolver Endpoints.
- DNS forwarding rules.
- Hybrid cloud DNS communication.


# Amazon Route 53 Overview

Amazon Route 53 is a scalable and highly available Domain Name System (DNS) service provided by AWS.

During this workshop, I studied:

- Public DNS management.
- Private Hosted Zones.
- DNS name resolution.
- Hybrid DNS integration.
- Route 53 Resolver.

Route 53 Resolver enables communication between AWS DNS infrastructure and existing enterprise DNS systems.

The main components include:

## Outbound Resolver Endpoint

Outbound Resolver Endpoint allows AWS resources to send DNS queries to external DNS servers.

It is commonly used when applications running inside AWS need to resolve domain names from an on-premise environment.


## Inbound Resolver Endpoint

Inbound Resolver Endpoint allows external DNS systems to send DNS queries into AWS.

It enables on-premise DNS servers to resolve AWS private domain names.


## Resolver Rules

Resolver Rules define DNS forwarding behavior.

They control where DNS queries are forwarded depending on the requested domain name.


# AWS CloudFormation Infrastructure Deployment

AWS CloudFormation was used to automatically deploy the required infrastructure.

Completed tasks:

- Downloaded CloudFormation template.
- Created CloudFormation stack.
- Configured deployment parameters.
- Monitored stack creation process.
- Verified deployed resources.

The deployed infrastructure included:

- Amazon VPC.
- Public Subnets.
- Private Subnets.
- Internet Gateway.
- Security Groups.
- EC2 Remote Desktop Gateway instance.

Through CloudFormation, I learned Infrastructure as Code (IaC) concepts and how cloud infrastructure can be automated consistently.


# EC2 Key Pair Configuration

Created an EC2 Key Pair for secure Windows instance access.

Configuration:

Key Pair Name:

Key Type:

The key pair was used to decrypt Windows administrator credentials and securely connect to EC2 instances.


# Security Group Configuration

Security Groups were configured to control network access.

Completed activities:

- Reviewed inbound security rules.
- Restricted unnecessary ports.
- Allowed required RDP communication.
- Enabled ICMP testing.
- Applied least privilege security principles.

This configuration improved resource security and reduced unauthorized access risks.


# Remote Desktop Gateway Deployment

Successfully connected to the Remote Desktop Gateway server.

Completed steps:

- Retrieved EC2 Windows password.
- Used private key file to decrypt credentials.
- Downloaded Remote Desktop configuration.
- Connected successfully through RDP.

The Remote Desktop Gateway provided secure access to private AWS resources.


# AWS Managed Microsoft Active Directory Deployment

AWS Managed Microsoft Active Directory was deployed to simulate an enterprise on-premise DNS environment.

Configuration:

Domain Name:

Completed:

- Selected Hybrid DNS VPC.
- Configured security group.
- Selected private subnets.
- Created endpoint across multiple Availability Zones.

Purpose:

Allow AWS resources to forward DNS requests to external DNS servers.


## Creating Resolver Rules

Resolver Rules were configured to control DNS forwarding.

Completed:

- Created forwarding rules.
- Defined domain resolution behavior.
- Connected Route 53 Resolver with Active Directory DNS.

Resolver Rules ensure DNS requests are forwarded to the correct DNS environment.


## Creating Inbound Resolver Endpoint

Configured inbound DNS communication.

Completed:

- Created Route 53 Inbound Endpoint.
- Selected private subnets.
- Configured network interfaces.
- Verified endpoint status.

Purpose:

Allow external DNS systems to resolve AWS private resources.


# DNS Testing and Verification

After completing the configuration, DNS communication was tested.

Verified:

- AWS resources successfully communicated with DNS services.
- Resolver Rules forwarded DNS queries correctly.
- Active Directory DNS operated correctly.
- Hybrid DNS resolution worked successfully.

The hybrid DNS architecture was successfully completed.


# Cloud Architecture Understanding

The implemented architecture:



This architecture allows enterprises to integrate existing DNS infrastructure with AWS cloud environments.


# Resource Cleanup

After completing the workshop, unused AWS resources were removed.

Deleted resources:

- Route 53 Resolver Endpoints.
- Resolver Rules.
- CloudFormation Stack.
- AWS Managed Microsoft Active Directory.
- EC2 Instances.
- Security Groups.
- Unused networking resources.

Resource cleanup helped prevent unnecessary AWS costs.


# Knowledge Gained

After completing Week 7, I gained practical knowledge about:

- Amazon Route 53 DNS services.
- Hybrid cloud DNS architecture.
- AWS CloudFormation Infrastructure as Code.
- AWS Managed Microsoft Active Directory.
- Route 53 Resolver configuration.
- DNS forwarding mechanisms.
- VPC networking.
- Security Group management.
- Enterprise cloud integration.


# Conclusion

Week 7 provided practical experience in designing and implementing hybrid DNS infrastructure on AWS.

Through this workshop, I learned how Amazon Route 53, AWS CloudFormation, AWS Directory Service, and Route 53 Resolver can be combined to connect AWS cloud environments with simulated on-premise infrastructure.

The knowledge gained from this week is important for building scalable hybrid cloud architectures and managing enterprise-level AWS networking environments.