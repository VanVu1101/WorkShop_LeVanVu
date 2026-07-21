---
title: "S3"
date: 2026-04-17
weight: 1
chapter: false
pre: " <b> 5.2. </b> "
---

#### Báo cáo cấu hình Amazon S3

Nội dung thực hiện:

- Tạo bucket S3 với tên `my-app-uploads-2026-tri`.
- Thiết lập cấu trúc dữ liệu trong bucket để hỗ trợ chức năng upload và quản lý file:
  - `student-profile/` chứa dữ liệu hồ sơ sinh viên.
  - `student-profile/2/` và `student-profile/3/` để phân nhóm hoặc version dữ liệu.
  - `weekly-report-templates/1/` chứa mẫu báo cáo tuần đầu tiên.

Các bước triển khai:

1. Mở AWS Management Console, truy cập dịch vụ **Amazon S3**.
2. Chọn **Create bucket**, nhập tên bucket `my-app-uploads-2026-tri`.
3. Chọn Region phù hợp và giữ nguyên cài đặt mặc định cho nội dung workshop.
4. Thiết lập chính sách **Block Public Access** theo tiêu chuẩn bảo mật nội bộ.
5. Sử dụng chức năng **Create folder** để tạo các thư mục `student-profile/`, `student-profile/2/`, `student-profile/3/` và `weekly-report-templates/1/`.

Mục tiêu nghiệp vụ:

- `student-profile/`:
  - Lưu trữ ảnh đại diện và tệp media liên quan đến hồ sơ sinh viên.
  - Cho phép phân loại dữ liệu theo từng nhóm hoặc phiên bản bằng thư mục con `2/` và `3/`.
- `weekly-report-templates/`:
  - Lưu trữ mẫu báo cáo tuần do ứng dụng cung cấp.
  - Hỗ trợ chức năng upload/tải mẫu báo cáo cho người dùng cuối.

Kết quả:

- Bucket `my-app-uploads-2026-tri` đã được tạo thành công.
- Cấu trúc thư mục đã được tổ chức rõ ràng, đáp ứng yêu cầu lưu trữ và mở rộng.
- Hệ thống đã sẵn sàng cho chức năng upload/download tài liệu và media của ứng dụng quản lý thực tập sinh.
- Dễ dàng mở rộng thêm tiền tố mới khi cần quản lý nhiều loại dữ liệu hơn trong tương lai.

#### Hình ảnh tham chiếu

- Sơ đồ tổng quan bucket S3.

![S3 bucket tổng quan](/images/s3.png)

- Thư mục `student-profile/` và các thư mục con `2/`, `3/`.

![S3 student-profile folder](/images/s3-1.jpg)

- Thư mục `weekly-report-templates/` và thư mục con `1/`.

![S3 weekly-report-templates folder](/images/s3-2.jpg)

- Cấu trúc thư mục tổng thể.

![S3 cấu trúc thư mục](/images/s3-3.jpg)

![S3 uploads hình ảnh file ... lên aws s3](/images/3-4s3.jpg)
