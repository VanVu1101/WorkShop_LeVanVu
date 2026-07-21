---
title: "Create the SNS Topic"
date: 2026-07-21
weight: 1
chapter: false
pre: " <b> 5.3.1 </b> "
---

#### Create the SNS Topic

This page documents the SNS topic configuration used for enterprise-grade email notifications and operational alerting.

- Topic name: `Nhom4Notification`
- Topic ARN: `arn:aws:sns:us-east-1:765959262030:Nhom4Notification`
- Topic owner: `765959262030`
- Topic type: `Standard`
- Delivery protocol: `EMAIL`
- Subscription status: `Confirmed`

#### Business justification

The SNS topic was created to deliver timely incident alerts and operational notifications to the project owner. This ensures that S3 and CloudWatch events are escalated to email immediately and provides a practical notification channel for business stakeholders.

#### Implementation summary

1. Opened the AWS SNS console in the US East (N. Virginia) region.
2. Selected **Create topic** and chose the **Standard** topic type.
3. Entered the name `Nhom4Notification` and confirmed the topic details.
4. Created an email subscription for `nguyentri2307@gmail.com`.
5. Confirmed the subscription from the recipient inbox.

#### Result

The SNS topic is fully configured and ready to receive alarm notifications. It is now available for CloudWatch to use as an action target for alert delivery.

![SNS topic configuration](/images/sns1.jpg)

#### Assurance

The topic details screenshot confirms the topic is active, owned by the correct AWS account, and set to standard messaging. Email subscription has been verified, ensuring no additional approval steps are required before alarm notifications are sent.
