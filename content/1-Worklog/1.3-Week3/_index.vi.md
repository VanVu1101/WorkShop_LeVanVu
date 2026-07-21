---
title: "Worklog Tuần 3"
date: 2026-05-04
weight: 3
chapter: false
pre: "<b>1.3.</b>"
---

{{% notice info %}}
**Chủ đề:** Thực hành Amazon EC2, AWS IAM, Amazon VPC và bảo mật hạ tầng trên AWS.
{{% /notice %}}

# Mục tiêu tuần

Trong tuần thứ ba, em tập trung tìm hiểu và thực hành các dịch vụ cốt lõi của AWS liên quan đến điện toán, quản lý danh tính, mạng và bảo mật.

Các mục tiêu chính gồm:

- Tìm hiểu dịch vụ Amazon EC2.
- Nghiên cứu Amazon Machine Image (AMI), Instance Types và Amazon EBS.
- Tìm hiểu AWS Identity and Access Management (IAM).
- Làm quen với Amazon VPC và kiến trúc mạng trên AWS.
- Cấu hình Security Group và Network ACL.
- Triển khai và quản lý Amazon EC2 Instance.
- Thực hành kết nối SSH đến EC2.
- Hiểu các nguyên tắc bảo mật và quản trị hạ tầng trên AWS.

---

# Kế hoạch thực hiện

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
|------|-----------|--------------|-----------------|--------------------|
| 1 | - Tìm hiểu Amazon EC2.<br>- Nghiên cứu Instance Types, AMI, Key Pair và Amazon EBS.<br>- Hiểu quy trình triển khai EC2. | 04/05/2026 | 04/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 2 | - Tìm hiểu AWS Identity and Access Management (IAM).<br>- Tạo IAM User, IAM Group và IAM Policy.<br>- Thực hành IAM Role và các nguyên tắc bảo mật. | 05/05/2026 | 05/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 3 | - Tìm hiểu Amazon VPC.<br>- Thực hành VPC, Subnet, Route Table và Internet Gateway.<br>- Làm quen Security Group và Network ACL. | 06/05/2026 | 06/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 4 | - Khởi tạo Amazon EC2 Instance.<br>- Cấu hình Security Group.<br>- Tạo Key Pair và kết nối SSH.<br>- Kiểm tra trạng thái EC2 Instance. | 07/05/2026 | 07/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 5 | - Thực hành cấu hình mạng với Amazon VPC.<br>- Thiết lập Public Subnet và Private Subnet.<br>- Ôn tập kiến trúc mạng và bảo mật EC2. | 08/05/2026 | 08/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 6 | - Tổng hợp nội dung EC2, IAM và VPC.<br>- Ôn tập kiến thức về mạng và bảo mật.<br>- Chuẩn bị môi trường cho các Workshop tuần tiếp theo. | 09/05/2026 | 09/05/2026 | https://cloudjourney.awsstudygroup.com/ |

---

# Nội dung đã thực hiện

## 1. Tìm hiểu Amazon EC2

Trong tuần này, em nghiên cứu Amazon EC2 (Elastic Compute Cloud) – dịch vụ máy chủ ảo quan trọng của AWS.

Các nội dung đã tìm hiểu gồm:

- Tổng quan về Amazon EC2.
- Các loại Instance Types.
- Amazon Machine Image (AMI).
- Amazon Elastic Block Store (EBS).
- Key Pair.
- Elastic IP.
- Vòng đời của EC2 Instance.

Qua quá trình nghiên cứu, em hiểu được cách AWS cung cấp và quản lý các máy chủ ảo có khả năng mở rộng linh hoạt trên nền tảng điện toán đám mây.

<p align="center">
<img src="/images/ec2.png" width="700">
</p>

<p align="center">
<i>Hình 4. Tổng quan dịch vụ Amazon EC2.</i>
</p>

---

## 2. Quản lý danh tính và quyền truy cập AWS (IAM)

Trong tuần này, em tìm hiểu **AWS Identity and Access Management (IAM)** để hiểu cách AWS quản lý danh tính người dùng, xác thực và phân quyền truy cập tài nguyên.

Các nội dung đã thực hiện gồm:

- Tìm hiểu Authentication và Authorization.
- Phân biệt Root User và IAM User.
- Tạo IAM User.
- Tạo IAM Group.
- Tạo IAM Policy.
- Gán người dùng vào Group.
- Tạo IAM Role.
- Thực hành Assume Role.
- Cấu hình Password Policy.
- Tìm hiểu Multi-Factor Authentication (MFA).
- Áp dụng nguyên tắc Least Privilege.

Qua nội dung này, em hiểu được cơ chế quản lý danh tính và phân quyền trên AWS nhằm đảm bảo tính bảo mật cho hệ thống.

<p align="center">
<img src="/images/aws-iam.png" width="700">
</p>

<p align="center">
<i>Hình 5. Tổng quan AWS Identity and Access Management (IAM).</i>
</p>

Bên cạnh đó, em còn thực hành tạo nhóm quản trị và người dùng quản trị phục vụ cho các bài Lab.

Các nội dung thực hiện gồm:

- Tạo **AdminGroup**.
- Gán quyền **AdministratorAccess**.
- Tạo **AdminUser**.
- Thêm người dùng vào AdminGroup.
- Tải tệp thông tin đăng nhập (.csv).
- Đăng nhập bằng IAM User.
- Kiểm tra quyền quản trị trên các dịch vụ AWS.

<p align="center">
<img src="/images/aws-iamadmin.png" width="700">
</p>

<p align="center">
<i>Hình 6. Tạo nhóm quản trị và người dùng IAM.</i>
</p>

---

## 3. Tìm hiểu Amazon VPC và mạng trên AWS

Trong tuần này, em tiếp tục nghiên cứu dịch vụ Amazon VPC để hiểu cách xây dựng mạng riêng trên nền tảng AWS.

Các nội dung đã tìm hiểu gồm:

- Amazon VPC.
- CIDR Block.
- Public Subnet.
- Private Subnet.
- Route Table.
- Internet Gateway.
- NAT Gateway.
- VPC Resource Map.
- VPC Flow Logs.

Qua đó, em hiểu được cách AWS xây dựng và cô lập hệ thống mạng, đồng thời cho phép các tài nguyên giao tiếp an toàn với Internet.

---

## 4. Security Group và Network ACL

Để bảo vệ tài nguyên trên AWS, em tìm hiểu hai cơ chế bảo mật mạng chính.

Các nội dung đã thực hiện:

- Tạo Security Group.
- Cấu hình Inbound Rules.
- Cấu hình Outbound Rules.
- Mở các cổng 22, 80 và 443.
- Tìm hiểu Network ACL.
- So sánh Security Group và Network ACL.

Qua bài thực hành, em hiểu được mô hình bảo mật nhiều lớp mà AWS áp dụng trong hạ tầng điện toán đám mây.

---

## 5. Thực hành triển khai Amazon EC2

Em hoàn thành bài Lab triển khai Amazon EC2 với các bước:

- Tạo Key Pair.
- Khởi tạo EC2 Instance.
- Chọn Amazon Linux AMI.
- Chọn Instance Type.
- Cấu hình Security Group.
- Kết nối EC2 thông qua SSH.
- Kiểm tra trạng thái hoạt động.
- Dừng và xóa EC2 Instance sau khi hoàn thành bài Lab.

<p align="center">
<img src="/images/ec2-instance.png" width="700">
</p>

<p align="center">
<i>Hình 7. Triển khai Amazon EC2 Instance.</i>
</p>

---

# Kiến thức tiếp thu

Sau khi hoàn thành tuần thứ ba, em đã:

- Hiểu kiến trúc Amazon EC2.
- Triển khai và quản lý EC2 Instance.
- Phân biệt Instance Types và AMI.
- Cấu hình Amazon EBS.
- Quản lý IAM User, Group, Policy và Role.
- Hiểu Authentication và Authorization.
- Xây dựng mạng với Amazon VPC.
- Cấu hình Public Subnet và Private Subnet.
- Cấu hình Security Group và Network ACL.
- Kết nối EC2 thông qua SSH.

---

# Kết quả đạt được

- Hoàn thành Workshop Amazon EC2.
- Hoàn thành Workshop AWS IAM.
- Thực hành Amazon VPC.
- Cấu hình Security Group và Network ACL.
- Triển khai EC2 và kết nối SSH thành công.
- Áp dụng các nguyên tắc bảo mật IAM.
- Nâng cao kỹ năng triển khai hạ tầng AWS.

---

# Khó khăn gặp phải

Trong quá trình thực hành, em gặp một số khó khăn như:

- Khó hình dung kiến trúc mạng trên AWS.
- Dễ nhầm lẫn giữa Security Group và Network ACL.
- Việc cấu hình quyền trong IAM khá phức tạp.
- Gặp lỗi khi kết nối SSH đến EC2 ở lần đầu thực hiện.
- Cần thời gian để hiểu mối liên hệ giữa EC2, VPC và IAM.

---

# Cách giải quyết

Để khắc phục các khó khăn trên, em đã:

- Đọc tài liệu chính thức từ AWS Documentation.
- Thực hành nhiều lần các bài Lab EC2.
- Vẽ sơ đồ mạng để dễ hình dung kiến trúc VPC.
- Thử nghiệm nhiều mức phân quyền khác nhau trong IAM.
- Trao đổi với mentor và các thành viên trong Bootcamp.
- Ghi chú lại toàn bộ quy trình triển khai để thuận tiện cho các lần thực hành sau.

---

# Đánh giá tuần

Tuần thứ ba giúp em hiểu sâu hơn về hạ tầng điện toán đám mây trên AWS thông qua việc thực hành Amazon EC2, AWS IAM và Amazon VPC. Em đã nắm được quy trình triển khai máy chủ ảo, quản lý người dùng và phân quyền, xây dựng mạng riêng trên AWS cũng như áp dụng các cơ chế bảo mật như Security Group và Network ACL. Những kiến thức và kỹ năng này là nền tảng quan trọng để tiếp tục triển khai các kiến trúc AWS phức tạp hơn và phục vụ cho dự án thực tập trong các tuần tiếp theo.