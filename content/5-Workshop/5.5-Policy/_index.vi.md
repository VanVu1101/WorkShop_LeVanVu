---
title : "VPC Endpoint Policies"
date : 2024-01-01
weight : 5
chapter : false
pre : " <b> 5.5 </b> "
---

Khi bạn tạo một Interface Endpoint hoặc Gateway Endpoint, bạn có thể đính kèm một Endpoint Policy để kiểm soát quyền truy cập vào dịch vụ mà bạn đang kết nối. VPC Endpoint Policy là một chính sách tài nguyên IAM được gắn vào Endpoint. Nếu không chỉ định chính sách khi tạo Endpoint, AWS sẽ tự động áp dụng chính sách mặc định cho phép toàn quyền truy cập vào dịch vụ thông qua Endpoint.

Bạn có thể tạo một chính sách nhằm giới hạn quyền truy cập chỉ đến các S3 bucket cụ thể. Điều này hữu ích khi bạn muốn kiểm soát và chỉ cho phép một số tài nguyên S3 nhất định được truy cập thông qua VPC Endpoint.

Trong phần này, bạn sẽ tìm hiểu cách cấu hình VPC Endpoint Policy để giới hạn quyền truy cập đến các tài nguyên Amazon S3 được chỉ định thông qua VPC Endpoint.

![endpoint diagram](/images/5-Workshop/5.5-Policy/s3-bucket-policy.png)

#### Cấu hình môi trường EC2 cho việc triển khai ứng dụng web

1. Tạo và cấu hình một EC2 Instance để chuẩn bị môi trường triển khai ứng dụng web.

2. Kiểm tra các cấu hình cơ bản của EC2 Instance bao gồm:

- Loại Instance (Instance Type)
- Cấu hình VPC và Subnet
- Cấu hình Security Group
- IAM Role (nếu cần thiết)

![ec1](/images/ec2.2.jpg)

*Hình ec1. Cấu hình EC2 Instance và các thiết lập mạng.*

3. Cấu hình Security Group để cho phép các luồng truy cập cần thiết cho quá trình triển khai ứng dụng trong tương lai:

- 22: SSH access
- 80: HTTP access
- 443: HTTPS access

![ec2](/images/ec2.jpg)

*Hình ec2. Cấu hình inbound rule của Security Group cho EC2.*

4. Môi trường EC2 đã được chuẩn bị sẵn sàng. Việc triển khai ứng dụng web và cấu hình dịch vụ sẽ được thực hiện ở giai đoạn tiếp theo.

---

#### Cấu hình AWS Budgets để quản lý chi phí

Để kiểm soát chi phí AWS và tránh phát sinh chi phí ngoài dự kiến, AWS Budgets đã được cấu hình nhằm theo dõi mức sử dụng tài nguyên và chi phí ước tính của tài khoản AWS.

Các bước cấu hình AWS Budgets bao gồm:

- Tạo Monthly Cost Budget để theo dõi chi phí hàng tháng.
- Thiết lập giới hạn ngân sách mong muốn.
- Cấu hình thông báo qua email khi chi phí thực tế hoặc chi phí dự báo vượt quá mức giới hạn.
- Theo dõi mức sử dụng AWS Free Tier và các tài nguyên đang hoạt động.

![budget](/images/budget.jpg)

*Hình budget. Cấu hình AWS Budgets để giám sát chi phí sử dụng AWS hàng tháng.*

Sau khi hoàn tất cấu hình AWS Budgets, hệ thống có thể tự động theo dõi chi phí sử dụng AWS và gửi cảnh báo khi chi phí có nguy cơ vượt quá giới hạn đã thiết lập.

Việc kết hợp VPC Endpoint Policy và AWS Budgets giúp tăng cường khả năng quản lý bảo mật cũng như kiểm soát chi phí trong môi trường AWS.