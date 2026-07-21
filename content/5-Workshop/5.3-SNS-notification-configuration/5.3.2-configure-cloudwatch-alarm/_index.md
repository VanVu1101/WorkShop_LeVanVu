---
title: "Configure the CloudWatch Alarm"
date: 2026-07-21
weight: 2
chapter: false
pre: " <b> 5.3.2 </b> "
---

#### Configure the CloudWatch Alarm

This page describes the CloudWatch alarm setup that monitors SNS publish activity and triggers email notifications.

- Alarm name: `Nhom4-SNS-HighTraffic-Alarm`
- Namespace: `AWS/SNS`
- Metric: `NumberOfMessagesPublished`
- Alarm condition: `NumberOfMessagesPublished > 0 for 1 datapoints within 1 minute`
- Missing data treatment: default / insufficient data handling
- Current state: `In alarm`

#### Business impact

The alarm is designed to detect any publish activity on the SNS topic and immediately escalate it through email. This ensures the team is aware of SNS traffic and can investigate any unexpected notification events promptly.

#### Configuration details

1. Opened the AWS CloudWatch console.
2. Chose **Alarms** and selected **Create alarm**.
3. Defined the metric under namespace `AWS/SNS` for `NumberOfMessagesPublished`.
4. Set a low threshold to capture the first publish event and used a 1-minute evaluation period.
5. Attached the alarm action to the SNS topic `Nhom4Notification`.

#### Result

The alarm is active and currently in `In alarm` state, confirming the metric has breached the configured threshold. This validates the end-to-end CloudWatch alarm and SNS notification workflow.

![CloudWatch alarm overview](/images/cloud2.jpg)

#### Assurance

The screenshot confirms the alarm is correctly tracking the SNS metric and has been deployed to the correct AWS account and region. This alarm is now a reliable monitor for SNS publish activity.
