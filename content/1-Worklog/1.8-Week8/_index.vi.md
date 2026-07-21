---
title: "Worklog Tuần 8"
date: 2026-06-08
weight: 8
chapter: false
pre: "<b>1.8.</b>"
---

{{% notice info %}}
Tuần 8 tập trung vào việc tổng hợp kiến thức từ các workshop AWS đã hoàn thành, lựa chọn đề tài cuối khóa, phân tích yêu cầu hệ thống, thiết kế kiến trúc Cloud trên AWS, xây dựng giao diện mẫu và lập kế hoạch phát triển dự án trước khi bước sang giai đoạn triển khai.
{{% /notice %}}

# Mục tiêu tuần 8

- Ôn tập toàn bộ các workshop AWS đã thực hiện trong những tuần trước.
- Củng cố kiến thức về các dịch vụ AWS phục vụ dự án cuối khóa.
- Lựa chọn đề tài phù hợp cho dự án.
- Phân tích yêu cầu và phạm vi hệ thống.
- Thiết kế kiến trúc Cloud trên AWS.
- Thiết kế sơ đồ kiến trúc hệ thống.
- Thiết kế giao diện mẫu (UI/Wireframe).
- Lập kế hoạch phát triển dự án.
- Phân chia công việc cho các thành viên trong nhóm.
- Chuẩn bị tài liệu trước khi bước vào giai đoạn lập trình.

---

# Các công việc cần triển khai trong tuần

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | Ôn tập các workshop AWS đã hoàn thành gồm EC2, VPC, IAM, RDS, Lightsail, Route 53 và CloudFormation. | 08/06/2026 | 08/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| 3 | Thảo luận ý tưởng, phân tích yêu cầu và lựa chọn đề tài dự án cuối khóa. | 09/06/2026 | 09/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| 4 | Thiết kế kiến trúc hệ thống trên AWS và xây dựng sơ đồ kiến trúc Cloud. | 10/06/2026 | 10/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| 5 | Phân tích chức năng hệ thống, thiết kế cơ sở dữ liệu, lựa chọn công nghệ và lập kế hoạch phát triển. | 11/06/2026 | 11/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| 6 | Thiết kế Wireframe và giao diện người dùng cho các màn hình chính của hệ thống. | 12/06/2026 | 12/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| 7 | Họp nhóm, phân chia module, thống nhất quy trình làm việc và lập kế hoạch triển khai. | 13/06/2026 | 13/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| CN | Hoàn thiện tài liệu thiết kế, rà soát kế hoạch và chuẩn bị bước sang giai đoạn phát triển hệ thống. | 14/06/2026 | 14/06/2026 | https://cloudjourney.awsstudygroup.com/ |

---

# Kết quả đạt được tuần 8

- Hoàn thành việc ôn tập toàn bộ kiến thức AWS đã học.
- Tổng hợp các dịch vụ AWS sẽ sử dụng trong dự án.
- Lựa chọn được đề tài cuối khóa.
- Phân tích đầy đủ yêu cầu chức năng và phi chức năng.
- Thiết kế sơ đồ kiến trúc hệ thống trên AWS.
- Hoàn thành bản thiết kế cơ sở dữ liệu ban đầu.
- Thiết kế giao diện mẫu cho hệ thống.
- Xây dựng kế hoạch phát triển dự án.
- Phân chia nhiệm vụ cho từng thành viên.
- Chuẩn bị đầy đủ tài liệu phục vụ giai đoạn triển khai.

---

# Ôn tập các Workshop AWS

Trong tuần này tiến hành tổng hợp toàn bộ kiến thức đã học từ các workshop trước nhằm chuẩn bị cho dự án cuối khóa.

Các dịch vụ đã được ôn tập gồm:

- Amazon EC2
- Amazon VPC
- IAM
- Amazon RDS
- AWS Lightsail
- Amazon Route 53
- AWS CloudFormation
- Security Groups
- CloudWatch
- Backup & Recovery

Qua quá trình ôn tập giúp hiểu rõ cách triển khai hạ tầng Cloud, cấu hình mạng, bảo mật và quản lý tài nguyên trên AWS.

---

# Lựa chọn đề tài dự án

Nhóm tiến hành thảo luận nhiều ý tưởng trước khi thống nhất lựa chọn đề tài.

Các nội dung thực hiện gồm:

- Phân tích nhu cầu thực tế.
- Xác định đối tượng người dùng.
- Xác định phạm vi hệ thống.
- Lựa chọn các dịch vụ AWS phù hợp.
- Đánh giá khả năng triển khai.
- Lập kế hoạch thực hiện dự án.

Sau quá trình trao đổi, nhóm lựa chọn xây dựng hệ thống Web Application triển khai trên nền tảng AWS Cloud.

---

# Thiết kế kiến trúc Cloud

Tiến hành thiết kế kiến trúc tổng thể của hệ thống theo mô hình nhiều tầng (Three-tier Architecture).

Kiến trúc bao gồm:

- Amazon VPC
- Public Subnet
- Private Subnet
- Internet Gateway
- Route Table
- Security Group
- Amazon EC2
- Amazon RDS
- Application Layer
- Database Layer

Kiến trúc được xây dựng theo hướng mở rộng dễ dàng, tăng khả năng bảo mật và đáp ứng triển khai thực tế trên AWS.

---

# Phân tích hệ thống

Thực hiện phân tích yêu cầu trước khi bắt đầu lập trình.

Các nội dung bao gồm:

- Functional Requirements.
- Non-functional Requirements.
- User Roles.
- Use Case.
- Database Design.
- API Planning.
- Module Planning.

Ngoài ra cũng xác định luồng xử lý chính của hệ thống nhằm hỗ trợ quá trình phát triển ở các tuần tiếp theo.

---

# Thiết kế giao diện

Tiến hành xây dựng phiên bản giao diện đầu tiên của hệ thống.

Các màn hình được thiết kế gồm:

- Homepage.
- Login.
- Dashboard.
- Navigation Menu.
- Responsive Layout.
- Wireframe Prototype.

Giao diện được xây dựng theo hướng đơn giản, trực quan và dễ sử dụng.

---

# Họp nhóm và lập kế hoạch

Nhóm tổ chức các buổi họp nhằm thống nhất kế hoạch triển khai.

Các nội dung được trao đổi:

- Tiến độ dự án.
- Roadmap phát triển.
- Công nghệ sử dụng.
- Phân chia module.
- Chuẩn hóa tài liệu.
- Git Workflow.
- Coding Convention.

Mỗi thành viên được giao nhiệm vụ cụ thể để chuẩn bị bước sang giai đoạn lập trình.

---

# Lập kế hoạch triển khai

Hoàn thiện các tài liệu phục vụ triển khai dự án gồm:

- Project Schedule.
- Module Breakdown.
- Database Design.
- AWS Resource Planning.
- Risk Assessment.
- Deployment Strategy.

Việc lập kế hoạch giúp nhóm có định hướng rõ ràng trong suốt quá trình phát triển hệ thống.

---

# Kiến thức đạt được

Sau khi hoàn thành tuần 8, đã tích lũy thêm được các kiến thức và kỹ năng:

- Ôn tập và hệ thống hóa kiến thức AWS.
- Thiết kế kiến trúc Cloud trên AWS.
- Phân tích yêu cầu hệ thống.
- Thiết kế cơ sở dữ liệu.
- Thiết kế giao diện UI/UX.
- Xây dựng sơ đồ kiến trúc hệ thống.
- Lập kế hoạch phát triển phần mềm.
- Làm việc nhóm và quản lý dự án.
- Chuẩn bị triển khai ứng dụng trên nền tảng AWS.

---

# Tổng kết

Tuần 8 là giai đoạn chuẩn bị quan trọng trước khi bước vào quá trình phát triển dự án.

Thông qua việc ôn tập các workshop AWS, lựa chọn đề tài, thiết kế kiến trúc Cloud, phân tích hệ thống, thiết kế giao diện, lập kế hoạch và phân chia công việc cho các thành viên, nhóm đã xây dựng được nền tảng vững chắc để triển khai dự án trong các tuần tiếp theo.

Các tài liệu và thiết kế được hoàn thiện trong tuần này sẽ là cơ sở cho quá trình lập trình, triển khai, kiểm thử và vận hành ứng dụng trên nền tảng AWS Cloud.