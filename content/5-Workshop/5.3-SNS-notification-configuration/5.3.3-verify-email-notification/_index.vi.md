---
title: "Xác nhận email thông báo"
date: 2026-07-21
weight: 3
chapter: false
pre: " <b> 5.3.3 </b> "
---

#### Xác nhận email thông báo

Trang này ghi lại kết quả và đánh giá việc nhận được email cảnh báo AWS do CloudWatch alarm kích hoạt.

- Email nhận từ: `AWS Notifications <no-reply@sns.amazonaws.com>`
- Subject: `ALARM: "Nhom4-SNS-HighTraffic-Alarm" in US East (N. Virginia)`
- Nội dung thông báo xác nhận alarm chuyển từ `OK` sang `ALARM` do `NumberOfMessagesPublished` vượt ngưỡng 0.
- Thời gian báo động: `21 July 2026, 04:21:30 UTC`

#### Ý nghĩa nghiệp vụ

Việc nhận đúng email giúp chứng minh thông báo đã đến được người quản trị. Điều này là bằng chứng quan trọng cho chuỗi cảnh báo từ CloudWatch đến SNS và sau đó đến email đầu cuối.

#### Kết quả

Email đã được gửi thành công tới `nguyentri2307@gmail.com`, xác nhận subscription SNS và cấu hình alarm CloudWatch hoạt động. Nội dung email bao gồm thông tin trạng thái, lý do báo động và thời gian xảy ra.

![SNS email notification](/images/sns3.jpg)
