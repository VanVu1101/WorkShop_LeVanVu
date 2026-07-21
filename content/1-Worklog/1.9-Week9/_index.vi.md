---
title: "Worklog Tuần 9"
date: 2026-06-29
weight: 9
chapter: false
pre: "<b>1.9.</b>"
---


## Mục tiêu tuần 9

- Phân tích yêu cầu và xác định phạm vi của hệ thống quản lý thực tập.
- Thiết kế kiến trúc tổng thể của hệ thống theo mô hình ba tầng.
- Phân chia các module chức năng và phân công nhiệm vụ cho từng thành viên.
- Thiết kế giao diện UI/UX cho các màn hình chính của hệ thống.
- Xây dựng cấu trúc dự án Frontend sử dụng ReactJS.
- Xây dựng các component dùng chung để phục vụ việc phát triển giao diện.
- Chuẩn bị tầng giao tiếp API để sẵn sàng tích hợp với Backend.

---

## Các công việc cần triển khai trong tuần này

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Kết quả |
|-----|-----------|--------------|-----------------|----------|
| 2 | Họp nhóm phân tích yêu cầu nghiệp vụ, xác định đối tượng sử dụng, phạm vi hệ thống và các chức năng chính của phần mềm. | 15/06/2026 | 15/06/2026 | Tài liệu phân tích yêu cầu |
| 3 | Thiết kế kiến trúc tổng thể của hệ thống, mô hình triển khai Frontend, Backend, Database và các dịch vụ AWS. | 16/06/2026 | 16/06/2026 | Sơ đồ kiến trúc hệ thống |
| 4 | Phân chia hệ thống thành các module chức năng và phân công nhiệm vụ cho từng thành viên trong nhóm. | 17/06/2026 | 17/06/2026 | Tài liệu phân công module |
| 5 | Thiết kế Wireframe và Mockup cho các giao diện như Login, Dashboard, Quản lý thực tập, Báo cáo tuần, Hồ sơ cá nhân và Quản lý tài liệu. | 18/06/2026 | 18/06/2026 | Bộ giao diện mẫu |
| 6 | Xây dựng tiêu chuẩn giao diện, màu sắc, typography, responsive layout, component dùng chung và cấu trúc thư mục dự án ReactJS. | 19/06/2026 | 19/06/2026 | UI Design Guidelines |
| 7 | Khởi tạo dự án ReactJS bằng Vite, cấu hình React Router, Layout, Navigation, Sidebar, Header và các component cơ bản. | 20/06/2026 | 20/06/2026 | Frontend Project Structure |
| CN | Xây dựng phiên bản đầu tiên của giao diện Frontend, kiểm tra tính đồng nhất giữa các component và chuẩn bị tích hợp API. | 21/06/2026 | 21/06/2026 | Frontend Prototype |

---

## Kết quả đạt được tuần 9

### Phân tích yêu cầu hệ thống

- Hoàn thành việc thu thập và phân tích yêu cầu của hệ thống quản lý thực tập.
- Xác định các nhóm người dùng:
  - Sinh viên
  - Giảng viên
  - Doanh nghiệp
  - Quản trị viên
- Xây dựng các yêu cầu chức năng và phi chức năng.
- Hoàn thiện sơ đồ luồng nghiệp vụ của hệ thống.

---

### Thiết kế kiến trúc hệ thống

Hoàn thiện kiến trúc hệ thống theo mô hình ba tầng gồm:

- Frontend:
  - ReactJS
  - Vite
  - JavaScript

- Backend:
  - Node.js
  - ExpressJS
  - RESTful API
  - JWT Authentication

- Database:
  - MySQL
  - Amazon RDS for MySQL

Kết hợp triển khai với các dịch vụ AWS:

- Amazon EC2
- Amazon RDS
- Amazon S3
- Amazon CloudFront
- Elastic Load Balancer (ELB)
- Amazon EC2 Auto Scaling
- AWS IAM
- Amazon VPC

Ngoài ra còn sử dụng:

- Git
- GitHub
- Visual Studio Code
- Postman
- Figma
- Draw.io

---

### Phân chia module chức năng

Hoàn thành việc chia nhỏ hệ thống thành các module độc lập:

- Authentication
- Dashboard
- Internship Management
- Weekly Worklog
- Task Management
- Notification
- User Profile
- CV & Document
- Administration

Các module được phân công cụ thể cho từng thành viên nhằm hỗ trợ phát triển song song và dễ dàng quản lý tiến độ.

---

### Thiết kế giao diện UI/UX

Thiết kế Wireframe và Mockup cho các màn hình:

- Login
- Dashboard
- Internship List
- Internship Detail
- Weekly Worklog
- Task List
- Task Detail
- User Profile
- CV Upload
- Document Management
- Settings

Giao diện được xây dựng theo các nguyên tắc:

- Thiết kế hiện đại
- Điều hướng trực quan
- Responsive trên nhiều thiết bị
- Component có khả năng tái sử dụng
- Trải nghiệm người dùng nhất quán

---

### Tổ chức dự án Frontend

Hoàn thiện cấu trúc thư mục của dự án ReactJS

Đồng thời chuẩn hóa quy tắc đặt tên, quản lý component và cấu trúc source code để đảm bảo khả năng mở rộng trong các giai đoạn tiếp theo.

---

### Phát triển giao diện Frontend

Hoàn thành phiên bản đầu tiên của giao diện người dùng bao gồm:

- Login Page
- Dashboard
- Sidebar
- Header
- Navigation
- Internship List
- Weekly Worklog
- User Profile

Các component dùng chung đã xây dựng:

- Button
- Input
- Modal
- Table
- Card
- Loading Spinner
- Pagination
- Search Box
- Status Badge

---

### Chuẩn bị tích hợp Backend

Hoàn thiện các thành phần phục vụ việc kết nối API:

- Cấu hình Axios
- Xây dựng API Service
- Định nghĩa Request/Response Model
- Quản lý JWT Token
- Chuẩn bị Authentication Flow
- Xây dựng cơ chế xử lý lỗi và thông báo

Việc chuẩn bị này giúp quá trình tích hợp Backend ở các tuần tiếp theo diễn ra nhanh chóng và thuận lợi.

---

## Kỹ năng đạt được

Trong tuần này đã nâng cao các kỹ năng:

- Phân tích yêu cầu phần mềm
- Thiết kế kiến trúc hệ thống
- Thiết kế UI/UX
- ReactJS
- Vite
- Node.js
- ExpressJS
- RESTful API
- MySQL
- AWS Cloud Architecture
- Responsive Web Design
- Component-Based Development
- Git & GitHub Workflow
- Làm việc nhóm
- Lập kế hoạch phát triển phần mềm

---

## Tổng kết tuần 9

Hoàn thành việc phân tích yêu cầu và xác định phạm vi của hệ thống quản lý thực tập.

Thiết kế hoàn chỉnh kiến trúc tổng thể sử dụng ReactJS, Node.js, MySQL kết hợp với các dịch vụ AWS như EC2, RDS, S3, CloudFront và Elastic Load Balancer.

Hoàn thiện thiết kế UI/UX, xây dựng cấu trúc dự án Frontend, phát triển các component dùng chung và phiên bản đầu tiên của giao diện người dùng.

Đồng thời chuẩn bị đầy đủ tầng giao tiếp API để sẵn sàng tích hợp với Backend trong các tuần phát triển tiếp theo.