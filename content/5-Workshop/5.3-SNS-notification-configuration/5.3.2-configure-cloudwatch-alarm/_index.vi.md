---
title: "Cấu hình CloudWatch Alarm"
date: 2026-07-21
weight: 2
chapter: false
pre: " <b> 5.3.2 </b> "
---

#### Cấu hình CloudWatch Alarm

Trang này mô tả cấu hình alarm CloudWatch để giám sát hoạt động publish trên topic SNS và kích hoạt thông báo email.

- Alarm name: `Nhom4-SNS-HighTraffic-Alarm`
- Namespace: `AWS/SNS`
- Metric: `NumberOfMessagesPublished`
- Điều kiện cảnh báo: `NumberOfMessagesPublished > 0 for 1 datapoints within 1 minute`
- Missing data treatment: mặc định / xử lý dữ liệu không đủ
- Trạng thái hiện tại: `In alarm`

#### Mục đích nghiệp vụ

Alarm được thiết kế để phát hiện ngay lập tức khi có tin nhắn SNS được publish. Mục tiêu là cảnh báo kịp thời cho bộ phận vận hành, giúp nhanh chóng kiểm tra nguyên nhân và tránh bỏ sót sự kiện quan trọng.

#### Các bước thực hiện

1. Truy cập AWS CloudWatch Console.
2. Vào menu **Alarms** và chọn **Create alarm**.
3. Chọn metric trong namespace `AWS/SNS` cho chỉ số `NumberOfMessagesPublished`.
4. Thiết lập điều kiện cảnh báo với ngưỡng 0 và khoảng thời gian 1 phút.
5. Liên kết hành động cảnh báo với topic SNS `Nhom4Notification`.

#### Kết quả

Alarm đã được bật và đang ở trạng thái `In alarm`, xác nhận rằng metric đã vượt ngưỡng cấu hình. Điều này chứng minh luồng CloudWatch → SNS đã được thiết lập và hoạt động đúng.

![CloudWatch alarm overview](/images/cloud2.jpg)

#### Đảm bảo

Ảnh chụp màn hình xác nhận alarm đang theo dõi metric đúng và được triển khai trong đúng tài khoản/region. Alarm này hiện là công cụ giám sát tin cậy cho hoạt động SNS.
