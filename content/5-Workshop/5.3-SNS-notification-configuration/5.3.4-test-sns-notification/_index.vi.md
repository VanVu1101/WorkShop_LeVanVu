---
title: "Kiểm tra gửi thông báo SNS"
date: 2026-07-21
weight: 4
chapter: false
pre: " <b> 5.3.4 </b> "
---

#### Kiểm tra gửi thông báo SNS

Trang này mô tả chi tiết kết quả thử nghiệm gửi thông báo SNS, nhằm kiểm chứng vòng đời thông báo từ publish đến email.

- Đã publish một thông báo test tới topic `Nhom4Notification`.
- Email nhận về có nội dung mẫu: `This is a test notification from the local environment - attempt 2`.
- Địa chỉ nhận: `nguyentri2307@gmail.com`.
- Email chứa link unsubscribe và thông tin subscription ARN, xác nhận thông báo đến đúng địa chỉ đã đăng ký.

#### Mục tiêu kiểm tra

Xác nhận toàn bộ chuỗi SNS hoạt động, bao gồm:
- Topic nhận tin nhắn.
- Email subscription được kích hoạt.
- Thông báo test được gửi và nhận đúng.

#### Kết quả

Thông báo thử nghiệm đã gửi và nhận thành công. Điều này khẳng định SNS notification chain đã được triển khai chuẩn xác và sẵn sàng cho các cảnh báo vận hành thực tế.

![SNS test message](/images/sns4.jpg)

#### Đảm bảo

Ảnh chụp màn hình cho thấy thông báo test đã được nhận, từ đó xác nhận luồng SNS, email subscription và CloudWatch alerting có thể sử dụng cho mục đích giám sát doanh nghiệp.
