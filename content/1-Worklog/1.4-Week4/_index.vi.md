---
title: "Worklog Tuần 4"
date: 2026-05-11
weight: 4
chapter: false
pre: "<b>1.4.</b>"
---

{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}

### Mục tiêu tuần 4

* Triển khai Microsoft Windows Server và Amazon Linux trên Amazon EC2.
* Thực hành kết nối EC2 bằng Remote Desktop (RDP) và SSH.
* Tìm hiểu các chức năng quản trị nâng cao của Amazon EC2.
* Thực hành tạo Amazon EBS Snapshot và Custom AMI.
* Triển khai ứng dụng Web trên Linux và Windows.
* Cài đặt LAMP Stack, phpMyAdmin và Node.js.
* Tìm hiểu IAM Cost & Usage Governance.
* Thực hiện dọn dẹp tài nguyên AWS và tối ưu chi phí.

---

### Các công việc cần triển khai trong tuần

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Chuẩn bị môi trường mạng.<br>- Tạo Linux VPC và Windows VPC.<br>- Cấu hình Security Group cho các EC2 Instance. | 11/05/2026 | 11/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 3 | - Khởi tạo Microsoft Windows Server 2025 EC2.<br>- Kết nối Remote Desktop (RDP).<br>- Kiểm tra cấu hình máy chủ Windows. | 12/05/2026 | 12/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 4 | - Khởi tạo Amazon Linux 2023.<br>- Kết nối SSH.<br>- Thực hành quản lý EC2, Snapshot và Custom AMI. | 13/05/2026 | 13/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 5 | - Cài đặt Apache, MariaDB, PHP, phpMyAdmin.<br>- Cài đặt Node.js.<br>- Triển khai AWS User Management Application trên Amazon Linux. | 14/05/2026 | 14/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 6 | - Cài đặt XAMPP và Node.js trên Windows Server.<br>- Triển khai ứng dụng Node.js.<br>- Kiểm tra khả năng truy cập ứng dụng.<br>- Tìm hiểu IAM Cost & Usage Governance.<br>- Dọn dẹp tài nguyên AWS. | 15/05/2026 | 16/05/2026 | https://cloudjourney.awsstudygroup.com/ |

---

### Kết quả đạt được tuần 4

* Chuẩn bị thành công môi trường mạng phục vụ triển khai EC2:
  * Tạo Linux VPC.
  * Tạo Windows VPC.
  * Cấu hình Security Group.
  * Thiết lập các luật Inbound và Outbound.

* Triển khai thành công Microsoft Windows Server 2025 trên Amazon EC2:
  * Khởi tạo EC2 Instance.
  * Tạo Key Pair.
  * Kết nối bằng Remote Desktop (RDP).
  * Kiểm tra trạng thái hoạt động của máy chủ.

* Triển khai thành công Amazon Linux 2023:
  * Kết nối SSH.
  * Quản lý Start, Stop và Reboot Instance.
  * Thay đổi Instance Type.
  * Tạo Amazon EBS Snapshot.
  * Tạo Custom AMI.
  * Khởi tạo EC2 từ Custom AMI.

* Hoàn thành triển khai ứng dụng trên Amazon Linux:
  * Cài đặt Apache Web Server.
  * Cài đặt MariaDB.
  * Cài đặt PHP.
  * Cấu hình phpMyAdmin.
  * Cài đặt Node.js.
  * Triển khai AWS User Management Application.
  * Kiểm tra ứng dụng hoạt động thành công.

* Hoàn thành triển khai ứng dụng trên Windows Server:
  * Cài đặt XAMPP.
  * Cài đặt Node.js.
  * Cấu hình môi trường chạy ứng dụng.
  * Triển khai AWS User Management Application.
  * Kiểm tra khả năng truy cập ứng dụng.

* Tìm hiểu và thực hành IAM Cost & Usage Governance:
  * Giới hạn AWS Region.
  * Giới hạn EC2 Instance Family.
  * Giới hạn EC2 Instance Type.
  * Giới hạn loại Amazon EBS.
  * Thiết lập chính sách IAM kiểm soát chi phí.
  * Áp dụng các chính sách hạn chế truy cập và xóa tài nguyên.

* Thực hiện dọn dẹp tài nguyên AWS sau khi hoàn thành Lab:
  * Xóa EC2 Instance.
  * Xóa Amazon Machine Image (AMI).
  * Xóa Amazon EBS Volume.
  * Xóa Amazon EBS Snapshot.
  * Xóa Security Group.
  * Xóa IAM User và IAM Role.
  * Dọn dẹp toàn bộ tài nguyên tạm để tránh phát sinh chi phí.

* Nắm được quy trình triển khai và quản trị EC2 trên cả Windows và Linux.

* Hiểu cách tạo Snapshot và Custom AMI để sao lưu và tái sử dụng máy chủ.

* Biết triển khai môi trường LAMP Stack, phpMyAdmin và Node.js trên Amazon EC2.

* Hiểu vai trò của IAM Cost & Usage Governance trong việc quản lý quyền truy cập và tối ưu chi phí trên AWS.

* Có khả năng triển khai, quản lý và dọn dẹp tài nguyên AWS theo đúng quy trình thực hành.