---
title: "Worklog Tuần 7"
date: 2026-06-01
weight: 7
chapter: false
pre: "<b>1.7.</b>"
---

{{% notice info %}}
Worklog này tổng hợp các nội dung thực hành và kiến thức đã hoàn thành trong **Tuần 7** của chương trình **First Cloud AI Journey Bootcamp**. Nội dung trọng tâm của tuần là xây dựng kiến trúc **Hybrid DNS** bằng Amazon Route 53, AWS CloudFormation, AWS Directory Service và Route 53 Resolver nhằm tích hợp hạ tầng AWS với môi trường DNS On-Premise mô phỏng.
{{% /notice %}}

# Mục tiêu tuần 7

Trong tuần này, các mục tiêu cần hoàn thành gồm:

- Hiểu kiến trúc dịch vụ DNS Amazon Route 53.
- Tìm hiểu mô hình Hybrid DNS giữa AWS và hệ thống On-Premise.
- Hiểu Infrastructure as Code (IaC) với AWS CloudFormation.
- Triển khai hạ tầng AWS bằng CloudFormation Template.
- Cấu hình Amazon VPC, Subnet, Security Group và EC2.
- Triển khai AWS Managed Microsoft Active Directory.
- Thiết lập kết nối Remote Desktop Gateway.
- Cấu hình Amazon Route 53 Resolver.
- Tạo Outbound Resolver Endpoint.
- Tạo Inbound Resolver Endpoint.
- Cấu hình Resolver Rules để chuyển tiếp truy vấn DNS.
- Kiểm thử quá trình phân giải DNS giữa AWS và môi trường On-Premise.
- Thực hành quản lý và dọn dẹp tài nguyên AWS.

---

# Các công việc cần triển khai trong tuần này

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
|------|-----------|--------------|-----------------|----------------|
| 2 | - Tìm hiểu kiến trúc Amazon Route 53.<br>- Nghiên cứu quy trình phân giải DNS.<br>- Tìm hiểu mô hình Hybrid DNS giữa AWS và On-Premise. | 01/06/2026 | 01/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| 3 | - Tạo EC2 Key Pair.<br>- Tải CloudFormation Template.<br>- Triển khai hạ tầng AWS bằng CloudFormation. | 02/06/2026 | 02/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| 4 | - Cấu hình Security Group.<br>- Kiểm tra kiến trúc VPC.<br>- Kết nối Remote Desktop Gateway bằng RDP. | 03/06/2026 | 03/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| 5 | - Triển khai AWS Managed Microsoft Active Directory.<br>- Cấu hình môi trường Domain. | 04/06/2026 | 04/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| 6 | - Cấu hình Route 53 Outbound Resolver Endpoint.<br>- Thiết lập DNS Forwarding. | 05/06/2026 | 05/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| 7 | - Tạo Resolver Rules.<br>- Cấu hình Route 53 Inbound Resolver Endpoint. | 06/06/2026 | 06/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| CN | - Kiểm thử Hybrid DNS.<br>- Xác minh kết quả phân giải DNS.<br>- Dọn dẹp tài nguyên AWS. | 07/06/2026 | 07/06/2026 | https://cloudjourney.awsstudygroup.com/ |

---

# Kết quả đạt được tuần 7

Trong tuần này đã triển khai thành công mô hình **Hybrid DNS** trên AWS.

Kiến trúc hoàn chỉnh bao gồm:

- Amazon VPC.
- Public Subnet.
- Private Subnet.
- EC2 Remote Desktop Gateway.
- AWS Managed Microsoft Active Directory.
- Amazon Route 53 Resolver Endpoints.
- Resolver Rules.
- Kết nối Hybrid DNS giữa AWS và môi trường On-Premise mô phỏng.

---

# Tìm hiểu Amazon Route 53

Amazon Route 53 là dịch vụ DNS có khả năng mở rộng cao và độ sẵn sàng cao của AWS.

Trong workshop đã tìm hiểu các nội dung:

- Public Hosted Zone.
- Private Hosted Zone.
- Quá trình phân giải tên miền.
- Hybrid DNS.
- Route 53 Resolver.

Route 53 Resolver cho phép kết nối hệ thống DNS trên AWS với hệ thống DNS của doanh nghiệp hoặc môi trường On-Premise.

Các thành phần quan trọng gồm:

## Outbound Resolver Endpoint

Outbound Resolver Endpoint cho phép tài nguyên trong AWS gửi truy vấn DNS đến các máy chủ DNS bên ngoài.

Ứng dụng khi:

- Máy chủ trên AWS cần truy cập tên miền nội bộ của doanh nghiệp.
- Chuyển tiếp truy vấn DNS sang hệ thống DNS On-Premise.

---

## Inbound Resolver Endpoint

Inbound Resolver Endpoint cho phép các DNS Server bên ngoài gửi truy vấn DNS vào AWS.

Chức năng:

- Phân giải các Private Domain trong AWS.
- Cho phép hệ thống On-Premise truy cập tài nguyên DNS nội bộ trên AWS.

---

## Resolver Rules

Resolver Rules xác định quy tắc chuyển tiếp DNS.

Bao gồm:

- Định nghĩa tên miền cần chuyển tiếp.
- Xác định DNS Server đích.
- Điều khiển luồng phân giải DNS giữa AWS và hệ thống bên ngoài.

---

# Triển khai hạ tầng bằng AWS CloudFormation

Đã sử dụng AWS CloudFormation để triển khai tự động toàn bộ hạ tầng.

Các công việc thực hiện:

- Tải CloudFormation Template.
- Tạo CloudFormation Stack.
- Cấu hình Deployment Parameters.
- Theo dõi tiến trình tạo Stack.
- Kiểm tra các tài nguyên sau khi triển khai.

Hạ tầng được tạo gồm:

- Amazon VPC.
- Public Subnets.
- Private Subnets.
- Internet Gateway.
- Security Groups.
- EC2 Remote Desktop Gateway.

Thông qua CloudFormation đã hiểu rõ khái niệm **Infrastructure as Code (IaC)** và cách tự động hóa việc triển khai hạ tầng trên AWS.

---

# Cấu hình EC2 Key Pair

Đã tạo EC2 Key Pair để truy cập an toàn vào Windows EC2 Instance.

Key Pair được sử dụng để:

- Giải mã mật khẩu Administrator.
- Kết nối Remote Desktop.
- Bảo vệ quá trình đăng nhập vào máy chủ EC2.

---

# Cấu hình Security Group

Đã cấu hình Security Group nhằm kiểm soát truy cập mạng.

Các nội dung thực hiện:

- Kiểm tra Inbound Rules.
- Giới hạn các cổng không cần thiết.
- Cho phép Remote Desktop (RDP).
- Cho phép ICMP phục vụ kiểm thử.
- Áp dụng nguyên tắc Least Privilege.

Việc cấu hình giúp tăng cường bảo mật và giảm nguy cơ truy cập trái phép.

---

# Triển khai Remote Desktop Gateway

Đã kết nối thành công tới máy chủ Remote Desktop Gateway.

Các bước thực hiện:

- Lấy mật khẩu Windows Administrator.
- Giải mã bằng Private Key.
- Tải file Remote Desktop.
- Kết nối RDP thành công.

Remote Desktop Gateway giúp truy cập an toàn tới các tài nguyên trong Private Network của AWS.

---

# Triển khai AWS Managed Microsoft Active Directory

Đã triển khai AWS Managed Microsoft Active Directory để mô phỏng môi trường doanh nghiệp.

Các bước thực hiện:

- Chọn Hybrid DNS VPC.
- Cấu hình Security Group.
- Chọn Private Subnets.
- Triển khai trên nhiều Availability Zones.

Mục tiêu:

- Xây dựng hệ thống DNS doanh nghiệp.
- Phục vụ mô hình Hybrid DNS giữa AWS và On-Premise.

---

# Cấu hình Route 53 Resolver

## Tạo Outbound Resolver Endpoint

Đã tạo Outbound Resolver Endpoint.

Các bước thực hiện:

- Chọn Private Subnets.
- Gán Security Group.
- Cấu hình địa chỉ IP.
- Kiểm tra trạng thái Endpoint.

Mục đích:

Cho phép AWS chuyển tiếp truy vấn DNS sang hệ thống DNS bên ngoài.

---

## Tạo Resolver Rules

Đã tạo Resolver Rules để điều khiển quá trình DNS Forwarding.

Các công việc gồm:

- Tạo Forwarding Rules.
- Xác định Domain cần chuyển tiếp.
- Kết nối Route 53 Resolver với Active Directory DNS.

Resolver Rules giúp chuyển tiếp truy vấn DNS đúng đến hệ thống cần xử lý.

---

## Tạo Inbound Resolver Endpoint

Đã cấu hình Inbound Resolver Endpoint.

Các bước thực hiện:

- Tạo Route 53 Inbound Endpoint.
- Chọn Private Subnets.
- Cấu hình Network Interface.
- Kiểm tra trạng thái Endpoint.

Mục đích:

Cho phép DNS Server bên ngoài truy cập và phân giải tài nguyên Private trên AWS.

---

# Kiểm thử Hybrid DNS

Sau khi hoàn thành cấu hình đã tiến hành kiểm thử.

Kết quả:

- AWS có thể gửi truy vấn DNS đến hệ thống DNS doanh nghiệp.
- Resolver Rules hoạt động đúng.
- Active Directory DNS phản hồi chính xác.
- Hybrid DNS giữa AWS và On-Premise hoạt động thành công.

---

# Kiến trúc hệ thống

Kiến trúc Hybrid DNS đã triển khai bao gồm:

- Amazon VPC.
- Route 53 Resolver.
- AWS Managed Microsoft Active Directory.
- EC2 Remote Desktop Gateway.
- DNS Forwarding.
- Hybrid DNS Communication.

Mô hình này cho phép doanh nghiệp tích hợp hệ thống DNS nội bộ với hạ tầng AWS một cách an toàn và hiệu quả.

---

# Dọn dẹp tài nguyên

Sau khi hoàn thành Workshop đã tiến hành dọn dẹp toàn bộ tài nguyên không còn sử dụng.

Đã xóa:

- Route 53 Resolver Endpoints.
- Resolver Rules.
- CloudFormation Stack.
- AWS Managed Microsoft Active Directory.
- EC2 Instances.
- Security Groups.
- Các tài nguyên mạng không còn sử dụng.

Việc dọn dẹp giúp tránh phát sinh chi phí không cần thiết trên AWS.

---

# Kiến thức đạt được

Sau khi hoàn thành Tuần 7 đã tích lũy được nhiều kiến thức và kinh nghiệm thực tế:

- Hiểu dịch vụ DNS Amazon Route 53.
- Hiểu mô hình Hybrid Cloud DNS.
- Sử dụng AWS CloudFormation để triển khai hạ tầng tự động.
- Triển khai AWS Managed Microsoft Active Directory.
- Cấu hình Route 53 Resolver.
- Thiết lập DNS Forwarding.
- Quản trị Amazon VPC.
- Cấu hình Security Group.
- Kết nối AWS với hệ thống DNS doanh nghiệp.
- Hiểu quy trình xây dựng kiến trúc Hybrid Cloud trong môi trường doanh nghiệp.

---

# Kết luận

Tuần 7 giúp xây dựng nền tảng về kiến trúc Hybrid DNS trên AWS thông qua việc kết hợp Amazon Route 53, AWS CloudFormation, AWS Directory Service và Route 53 Resolver.

Thông qua các bài thực hành, đã nắm được quy trình triển khai hạ tầng bằng Infrastructure as Code, cấu hình hệ thống DNS doanh nghiệp, thiết lập cơ chế chuyển tiếp DNS giữa AWS và môi trường On-Premise, cũng như quản lý, kiểm thử và tối ưu tài nguyên AWS.

Kiến thức và kinh nghiệm đạt được trong tuần này là nền tảng quan trọng để triển khai các hệ thống Hybrid Cloud quy mô doanh nghiệp và các kiến trúc mạng nâng cao trên nền tảng AWS.