---
title: "Worklog Tuần 6"
date: 2026-05-25
weight: 6
chapter: false
pre: "<b>1.6.</b>"
---

{{% notice info %}}
Worklog này tổng hợp các nội dung thực hành và kiến thức đã hoàn thành trong **Tuần 6** của chương trình **First Cloud AI Journey Bootcamp**. Nội dung trọng tâm bao gồm triển khai cơ sở dữ liệu trên Amazon RDS, kết nối Amazon EC2, triển khai ứng dụng Node.js, sử dụng AWS Lightsail để triển khai các ứng dụng phổ biến, cấu hình bảo mật, sao lưu và giám sát tài nguyên trên AWS.
{{% /notice %}}

# Mục tiêu tuần 6

Trong tuần này, các mục tiêu cần hoàn thành bao gồm:

- Hiểu kiến trúc và quy trình triển khai Amazon RDS.
- Cấu hình Amazon VPC, Subnet và Security Group.
- Kết nối Amazon EC2 với Amazon RDS.
- Cài đặt môi trường chạy ứng dụng trên Amazon Linux.
- Triển khai ứng dụng Node.js kết nối với cơ sở dữ liệu trên AWS.
- Làm quen với dịch vụ AWS Lightsail.
- Triển khai WordPress, PrestaShop và Akaunting trên Lightsail.
- Cấu hình bảo mật và phân quyền truy cập.
- Thực hiện sao lưu và phục hồi tài nguyên.
- Theo dõi hiệu năng và tối ưu tài nguyên Cloud.

---

# Các công việc cần triển khai trong tuần này

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
|------|-----------|--------------|-----------------|----------------|
| 2 | - Tạo Amazon VPC.<br>- Cấu hình Public Subnet và Private Subnet.<br>- Tạo Security Group.<br>- Cấu hình DB Subnet Group cho Amazon RDS. | 25/05/2026 | 25/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 3 | - Khởi tạo EC2 Amazon Linux.<br>- Cấu hình SSH.<br>- Cài đặt Git, Node.js và MySQL Client.<br>- Chuẩn bị môi trường triển khai ứng dụng. | 26/05/2026 | 26/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 4 | - Triển khai Amazon RDS.<br>- Cấu hình kết nối cơ sở dữ liệu.<br>- Tạo Database Schema và dữ liệu mẫu.<br>- Kết nối thành công EC2 với RDS. | 27/05/2026 | 27/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 5 | - Clone ứng dụng Node.js từ GitHub.<br>- Cấu hình biến môi trường (.env).<br>- Triển khai ứng dụng trên EC2.<br>- Kiểm tra kết nối tới Amazon RDS. | 28/05/2026 | 28/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 6 | - Tìm hiểu AWS Lightsail.<br>- Tạo Lightsail Instance.<br>- Cấu hình Static IP.<br>- Triển khai WordPress. | 29/05/2026 | 29/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 7 | - Triển khai PrestaShop.<br>- Triển khai Akaunting.<br>- Cấu hình môi trường và phân quyền truy cập ứng dụng. | 30/05/2026 | 30/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| CN | - Tạo Snapshot sao lưu.<br>- Cấu hình CloudWatch Monitoring.<br>- Kiểm tra hiệu năng tài nguyên.<br>- Dọn dẹp các tài nguyên không sử dụng. | 31/05/2026 | 31/05/2026 | https://cloudjourney.awsstudygroup.com/ |

---

# Kết quả đạt được tuần 6

## Triển khai Amazon RDS và Amazon EC2

Trong tuần này đã thực hiện thành công việc xây dựng môi trường cơ sở dữ liệu trên AWS.

Các nội dung đã hoàn thành:

- Hiểu kiến trúc của Amazon RDS gồm:

  - Database Instance
  - Availability Zone
  - DB Subnet Group
  - Security Group
  - Backup và Maintenance

- Thiết kế hệ thống mạng AWS gồm:

  - Amazon VPC
  - Public Subnet
  - Private Subnet
  - Route Table
  - Security Group

- Khởi tạo thành công Amazon RDS Database.

- Thiết lập kết nối bảo mật giữa:

  - Amazon EC2
  - Amazon RDS

- Cài đặt đầy đủ môi trường phát triển trên Amazon Linux:

  - Git
  - Node.js
  - MySQL Client

- Tạo Database Schema và dữ liệu mẫu bằng SQL Script.

- Triển khai thành công ứng dụng Node.js kết nối trực tiếp tới Amazon RDS.

---

# Triển khai ứng dụng bằng AWS Lightsail

Trong workshop AWS Lightsail đã thực hiện:

- Tìm hiểu kiến trúc AWS Lightsail.
- Tạo Lightsail Instance.
- Lựa chọn Blueprint phù hợp.
- Cấu hình Networking.
- Gán Static IP.
- Kết nối máy chủ bằng Browser-based SSH.
- Thiết lập môi trường chạy ứng dụng.

Qua đó hiểu được cách Lightsail đơn giản hóa quá trình triển khai ứng dụng trên Cloud.

---

# Triển khai các ứng dụng thực tế

## WordPress

Đã triển khai thành công WordPress trên AWS Lightsail.

Các bước thực hiện gồm:

- Khởi tạo Ubuntu Lightsail Instance.
- Cài đặt:

  - Apache Web Server
  - PHP
  - MySQL Client

- Cấu hình WordPress.
- Kết nối cơ sở dữ liệu.
- Gán Static IP.
- Đăng nhập thành công trang quản trị WordPress.

---

## PrestaShop

Đã triển khai hệ thống thương mại điện tử PrestaShop.

Hoàn thành các nội dung:

- Tạo PrestaShop Instance.
- Cấu hình Networking.
- Gán Static IP.
- Truy cập trang quản trị.
- Tìm hiểu các chức năng quản lý cửa hàng trực tuyến.

---

## Akaunting

Đã triển khai thành công ứng dụng quản lý kế toán Akaunting.

Các công việc gồm:

- Khởi tạo Cloud Instance.
- Cấu hình môi trường ứng dụng.
- Kiểm tra khả năng truy cập.
- Tìm hiểu quy trình triển khai ứng dụng doanh nghiệp trên Cloud.

---

# Cấu hình bảo mật

Thực hành các nội dung về bảo mật hạ tầng AWS:

- Quản lý Security Group.
- Kiểm soát Inbound Rules.
- Kiểm soát Outbound Rules.
- Bảo vệ truy cập cơ sở dữ liệu.
- Thiết lập quyền truy cập phù hợp.
- Áp dụng nguyên tắc Least Privilege.

---

# Sao lưu và giám sát

Đã thực hiện các công việc quản trị tài nguyên:

- Tạo Snapshot cho Amazon RDS.
- Tạo Snapshot cho Lightsail.
- Thực hành khôi phục dữ liệu từ bản sao lưu.
- Theo dõi CloudWatch Metrics.
- Thiết lập CloudWatch Alarm.
- Kiểm tra CPU, RAM, Network và dung lượng lưu trữ.

---

# Dọn dẹp tài nguyên

Sau khi hoàn thành Workshop đã tiến hành tối ưu chi phí AWS bằng cách:

- Xóa EC2 không còn sử dụng.
- Xóa Amazon RDS không cần thiết.
- Xóa Snapshot dư thừa.
- Thu hồi Elastic IP không sử dụng.
- Xóa Lightsail Instance không còn phục vụ thực hành.

Qua đó giúp giảm chi phí phát sinh trên tài khoản AWS.

---

# Kiến thức đạt được

Sau khi hoàn thành Tuần 6, đã tích lũy được nhiều kiến thức và kinh nghiệm thực tế như:

- Hiểu quy trình triển khai cơ sở dữ liệu bằng Amazon RDS.
- Thiết kế hệ thống mạng với Amazon VPC.
- Kết nối Amazon EC2 với Amazon RDS.
- Triển khai ứng dụng Node.js trên AWS.
- Sử dụng AWS Lightsail để triển khai nhanh các ứng dụng phổ biến.
- Triển khai WordPress, PrestaShop và Akaunting.
- Cấu hình Security Group và quản lý truy cập.
- Thực hiện sao lưu và khôi phục dữ liệu.
- Theo dõi tài nguyên bằng Amazon CloudWatch.
- Dọn dẹp tài nguyên nhằm tối ưu chi phí Cloud.
- Hiểu quy trình triển khai hoàn chỉnh một ứng dụng từ hạ tầng, cơ sở dữ liệu, máy chủ đến vận hành và giám sát trên nền tảng AWS.

Tuần 6 giúp củng cố kỹ năng triển khai hạ tầng Cloud, quản trị cơ sở dữ liệu, triển khai ứng dụng thực tế, cấu hình bảo mật, sao lưu và giám sát hệ thống. Đây là nền tảng quan trọng để tiếp tục các nội dung về Auto Scaling, Load Balancer và kiến trúc Cloud có tính sẵn sàng cao ở các tuần tiếp theo.