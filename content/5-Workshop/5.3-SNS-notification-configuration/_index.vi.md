---
title: "Cấu hình thông báo SNS"
date: 2026-07-21
weight: 3
chapter: false
pre: " <b> 5.3 </b> "
---

# Cấu hình thông báo SNS

#### Mục tiêu

Phần này trình bày tổng quan về thiết lập SNS và CloudWatch để nhận thông báo qua email cho các sự kiện liên quan đến S3 và SNS.

#### Phạm vi báo cáo

- Tạo topic SNS phục vụ thông báo email.
- Cấu hình alarm CloudWatch giám sát hoạt động publish của SNS.
- Xác nhận khả năng nhận email từ SNS khi cảnh báo được kích hoạt.
- Thực hiện thử nghiệm gửi thông báo và đánh giá luồng vận hành.

#### Nội dung chi tiết

1. [**5.3.1** Tạo topic SNS](5.3.1-create-sns-topic/)
2. [**5.3.2** Cấu hình CloudWatch Alarm](5.3.2-configure-cloudwatch-alarm/)
3. [**5.3.3** Xác nhận email thông báo](5.3.3-verify-email-notification/)
4. [**5.3.4** Kiểm tra gửi thông báo SNS](5.3.4-test-sns-notification/)
