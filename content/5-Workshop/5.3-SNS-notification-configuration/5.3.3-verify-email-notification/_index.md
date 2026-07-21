---
title: "Verify Email Notification"
date: 2026-07-21
weight: 3
chapter: false
pre: " <b> 5.3.3 </b> "
---

#### Verify Email Notification

This page records the results of receiving the AWS notification email triggered by the CloudWatch alarm.

- Email from: `AWS Notifications <no-reply@sns.amazonaws.com>`
- Subject: `ALARM: "Nhom4-SNS-HighTraffic-Alarm" in US East (N. Virginia)`
- Notification body confirms the alarm changed from `OK` to `ALARM` because `NumberOfMessagesPublished` exceeded the threshold of `0`.
- Alarm timestamp: `21 July 2026, 04:21:30 UTC`

#### Business impact

Receiving this email confirms the operational alerting chain is complete. The system can now notify stakeholders of SNS activity without manual supervision.

#### Outcome

The email was successfully delivered to `nguyentri2307@gmail.com`, proving the SNS subscription is confirmed and CloudWatch alarm notifications are active.

![SNS email notification](/images/sns3.jpg)
