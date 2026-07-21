---
title: "Test SNS Notification"
date: 2026-07-21
weight: 4
chapter: false
pre: " <b> 5.3.4 </b> "
---

#### Test SNS Notification

This page documents the final verification step for SNS notification delivery, confirming the end-to-end publishing flow from topic to recipient email.

#### Test procedure

- Published a test notification message to the SNS topic `Nhom4Notification`.
- The sample email content was: `This is a test notification from the local environment - attempt 2`.
- Recipient address: `nguyentri2307@gmail.com`.
- The received email included the unsubscribe link and subscription ARN information, confirming the message arrived through the registered notification channel.

#### Business purpose

This test validates that the SNS notification chain is fully functional and that alert messages can be delivered to an operational email inbox. It also proves that the setup is ready for production-style incident notification and monitoring.

#### Result

The test notification was successfully published and received. This confirms that the SNS topic, email subscription, and notification delivery path are all operating correctly.

![SNS test message](/images/sns4.jpg)

#### Assurance

The screenshot demonstrates the successful reception of the SNS test message, verifying that the SNS notification workflow is available for business monitoring and incident escalation.
