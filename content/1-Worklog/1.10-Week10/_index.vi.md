---
title: "Worklog Tuần 10"
date: 2026-06-21
weight: 10
chapter: false
pre: "<b>1.10.</b>"
---

## Mục tiêu tuần 10

- Tiếp tục phát triển Hệ thống Quản lý Thực tập.
- Hoàn thiện các giao diện Frontend bằng ReactJS.
- Tích hợp Frontend với Backend thông qua RESTful API.
- Hoàn thiện chức năng xác thực người dùng bằng JWT và phân quyền theo vai trò.
- Phát triển các chức năng nghiệp vụ chính của hệ thống.
- Cải thiện giao diện người dùng và khả năng hiển thị trên nhiều thiết bị.
- Kiểm thử các chức năng đã hoàn thành và khắc phục lỗi.
- Chuẩn bị hệ thống cho quá trình triển khai lên môi trường Cloud.

---

## Các công việc cần triển khai trong tuần này

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Kết quả |
|-----|-----------|--------------|-----------------|----------|
| 2 | Tiếp tục phát triển giao diện Frontend và tích hợp chức năng Đăng nhập, Đăng ký với API xác thực người dùng. | 22/06/2026 | 22/06/2026 | Module Authentication |
| 3 | Phát triển Dashboard, Quản lý thực tập, Hồ sơ cá nhân và tích hợp API tương ứng. | 23/06/2026 | 23/06/2026 | Dashboard & Profile |
| 4 | Hoàn thiện chức năng quản lý báo cáo thực tập theo tuần gồm Thêm, Sửa, Xóa và Xem chi tiết. | 24/06/2026 | 24/06/2026 | Module Weekly Worklog |
| 5 | Xây dựng chức năng Check-in/Check-out, lịch sử điểm danh và theo dõi tiến độ thực tập. | 25/06/2026 | 25/06/2026 | Module Attendance |
| 6 | Hoàn thiện các chức năng Quản lý nhiệm vụ, Thông báo và Quản lý tài liệu. | 26/06/2026 | 26/06/2026 | Các Module Quản lý |
| 7 | Kiểm thử tích hợp, tối ưu giao diện, sửa lỗi API và cải thiện hiệu năng ứng dụng. | 27/06/2026 | 27/06/2026 | Báo cáo kiểm thử |
| CN | Họp với người hướng dẫn, cập nhật tài liệu dự án và chuẩn bị kế hoạch triển khai hệ thống. | 28/06/2026 | 28/06/2026 | Tài liệu dự án |

---

## Kết quả đạt được tuần 10

### Phát triển giao diện Frontend

Tiếp tục xây dựng các giao diện của hệ thống dựa trên thiết kế UI/UX đã hoàn thành ở tuần trước.

Các màn hình đã hoàn thiện gồm:

- Đăng nhập
- Đăng ký
- Dashboard
- Quản lý thực tập
- Báo cáo thực tập theo tuần
- Quản lý nhiệm vụ
- Hồ sơ cá nhân
- Thông báo
- Cài đặt
- Quản lý tài liệu

Đồng thời hoàn thiện các component dùng chung:

- Button
- Input
- Modal
- Table
- Card
- Loading Spinner
- Search Box
- Pagination
- Status Badge
- Confirmation Dialog

---

### Tích hợp Backend API

Hoàn thành việc kết nối giữa Frontend ReactJS và Backend Node.js thông qua RESTful API.

Các API đã được tích hợp gồm:

- Đăng nhập
- Đăng ký
- Refresh Token
- Hồ sơ người dùng
- Báo cáo tuần
- Quản lý thực tập
- Quản lý nhiệm vụ
- Thông báo
- Điểm danh thực tập

Đồng thời cấu hình Axios Interceptor để tự động xử lý JWT Token và các lỗi phản hồi từ hệ thống.

---

### Xác thực và phân quyền

Hoàn thiện chức năng xác thực người dùng.

Các chức năng bao gồm:

- Đăng nhập
- Đăng ký
- Quên mật khẩu
- Đăng xuất
- JWT Authentication
- Protected Route
- Phân quyền theo vai trò
- Lưu phiên đăng nhập

React Context API được sử dụng để quản lý trạng thái đăng nhập trên toàn bộ ứng dụng.

---

### Quản lý thực tập

Hoàn thiện module Quản lý thực tập.

Các chức năng gồm:

- Thông tin thực tập
- Trạng thái thực tập
- Thông tin doanh nghiệp
- Thông tin người hướng dẫn
- Theo dõi tiến độ thực tập
- Quản lý thời gian thực tập

Người dùng có thể dễ dàng theo dõi toàn bộ quá trình thực tập trên hệ thống.

---

### Quản lý báo cáo tuần

Hoàn thiện chức năng quản lý báo cáo thực tập theo tuần.

Bao gồm:

- Xem danh sách báo cáo
- Tạo báo cáo
- Chỉnh sửa báo cáo
- Xóa báo cáo
- Xem chi tiết báo cáo
- Quản lý trạng thái báo cáo

Bổ sung kiểm tra dữ liệu đầu vào nhằm đảm bảo tính chính xác trước khi lưu.

---

### Quản lý điểm danh

Phát triển chức năng điểm danh thực tập.

Các chức năng gồm:

- Check-in
- Check-out
- Lịch sử điểm danh
- Tính thời gian làm việc
- Trạng thái điểm danh

Dữ liệu được đồng bộ trực tiếp với Backend thông qua API.

---

### Quản lý nhiệm vụ và thông báo

Tiếp tục phát triển các module hỗ trợ.

Hoàn thiện:

- Danh sách nhiệm vụ
- Chi tiết nhiệm vụ
- Cập nhật trạng thái nhiệm vụ
- Trung tâm thông báo
- Lịch sử thông báo
- Giao diện tải lên tài liệu

Các module giúp hỗ trợ quá trình theo dõi và quản lý công việc trong thời gian thực tập.

---

### Cải thiện giao diện

Tiếp tục tối ưu trải nghiệm người dùng.

Các cải tiến gồm:

- Responsive Layout
- Điều hướng trực quan
- Loading Indicator
- Kiểm tra dữ liệu biểu mẫu
- Toast Notification
- Empty State
- Error Page
- Giao diện đồng nhất

Hệ thống hoạt động ổn định trên nhiều kích thước màn hình khác nhau.

---

### Kiểm thử và sửa lỗi

Tiến hành kiểm thử toàn bộ các chức năng đã phát triển.

Bao gồm:

- Kiểm thử xác thực
- Kiểm thử CRUD
- Kiểm thử API
- Kiểm thử Responsive
- Kiểm thử phân quyền
- Kiểm thử xử lý lỗi

Khắc phục các lỗi liên quan đến giao diện, kết nối API và kiểm tra dữ liệu.

---

### Chuẩn bị triển khai

Chuẩn bị hệ thống cho giai đoạn triển khai.

Hoàn thành:

- Cấu hình môi trường Production
- Quản lý biến môi trường
- Cấu hình API Endpoint
- Chuẩn bị cấu hình triển khai
- Kiểm tra kết nối cơ sở dữ liệu
- Chuẩn bị lưu trữ tài liệu
- Cấu hình Reverse Proxy

---

## Kỹ năng đạt được

Trong tuần này đã nâng cao các kỹ năng:

- ReactJS
- Node.js
- ExpressJS
- RESTful API
- JWT Authentication
- React Context API
- Responsive Web Design
- CRUD Operations
- Frontend Testing
- UI Optimization
- Git Workflow
- Làm việc nhóm

---

## Tổng kết tuần 10

Hoàn thành phần lớn giao diện Frontend của Hệ thống Quản lý Thực tập và tích hợp thành công với Backend thông qua RESTful API.

Xây dựng đầy đủ các chức năng quan trọng như xác thực người dùng, quản lý thực tập, báo cáo tuần, điểm danh, quản lý nhiệm vụ và thông báo.

Tiến hành kiểm thử, sửa lỗi, tối ưu giao diện và chuẩn bị hệ thống cho giai đoạn triển khai, tạo nền tảng cho việc hoàn thiện sản phẩm ở các tuần tiếp theo.