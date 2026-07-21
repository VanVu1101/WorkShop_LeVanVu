---
title: "Tạo topic SNS"
date: 2026-07-21
weight: 1
chapter: false
pre: " <b> 5.3.1 </b> "
---

#### Tạo topic SNS

Trang này trình bày báo cáo chi tiết việc tạo và xác nhận SNS topic dùng cho thông báo email của hệ thống.

- Topic name: `Nhom4Notification`
- Topic ARN: `arn:aws:sns:us-east-1:765959262030:Nhom4Notification`
- Topic owner: `765959262030`
- Topic type: `Standard`

#### Mục đích nghiệp vụ

Topic SNS được thiết lập để cung cấp cơ chế thông báo theo nhu cầu vận hành. Khi CloudWatch phát hiện sự kiện bất thường, hệ thống sẽ gửi cảnh báo tới email người quản trị, đảm bảo phản hồi nhanh và giảm thiểu rủi ro gián đoạn dịch vụ.

#### Các bước triển khai

1. Truy cập AWS SNS Console tại khu vực US East (N. Virginia).
2. Chọn **Create topic** và thiết lập loại topic là `Standard`.
3. Nhập tên topic `Nhom4Notification` và hoàn thành tạo topic.
4. Tạo subscription email với địa chỉ `nguyentri2307@gmail.com`.
5. Xác nhận subscription từ hộp thư nhận.

#### Kết quả

Topic SNS đã được cấu hình thành công, thuộc quyền sở hữu tài khoản AWS đúng và sẵn sàng nhận thông báo. Subscription email đã được xác nhận nên chuỗi thông báo có thể hoạt động ngay lập tức.

![SNS topic configuration](/images/sns1.jpg)

#### Đảm bảo

Ảnh chụp màn hình xác nhận topic đang hoạt động, cấu hình đúng tài khoản và chế độ Standard. Subscription cũng đã được xác nhận, giảm thiểu rủi ro báo động không đến được người nhận.
