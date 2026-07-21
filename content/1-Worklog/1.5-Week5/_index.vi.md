---
title: "Worklog Tuần 5"
date: 2026-05-18
weight: 5
chapter: false
pre: "<b>1.5.</b>"
---

{{% notice info %}}
**Chủ đề:** Thực hành AWS Cloud9, AWS CLI, Amazon S3, Amazon CloudFront và các tính năng quản lý dữ liệu trên Amazon S3.
{{% /notice %}}

# Mục tiêu tuần

Trong tuần thứ năm, em tiếp tục thực hành các dịch vụ AWS phục vụ cho việc phát triển và triển khai ứng dụng trên nền tảng điện toán đám mây.

Các mục tiêu chính gồm:

- Làm quen với môi trường phát triển AWS Cloud9.
- Thực hành các lệnh Linux và AWS CLI.
- Triển khai website tĩnh bằng Amazon S3.
- Cấu hình Static Website Hosting.
- Tăng tốc truy cập website bằng Amazon CloudFront.
- Tìm hiểu Amazon S3 Versioning.
- Tìm hiểu Cross-Region Replication.
- Thực hiện dọn dẹp tài nguyên và tối ưu chi phí trên AWS.

---

# Kế hoạch thực hiện

| Nội dung | Mô tả |
|-----------|------|
| AWS Cloud9 | Tạo môi trường phát triển Cloud9 và thực hành Linux. |
| AWS CLI | Sử dụng AWS CLI để quản lý tài nguyên AWS. |
| Amazon S3 | Tạo Bucket và triển khai Static Website Hosting. |
| Amazon CloudFront | Cấu hình CDN để tăng tốc website. |
| Amazon S3 Versioning | Quản lý nhiều phiên bản của đối tượng trong S3. |
| Cross-Region Replication | Tìm hiểu sao chép dữ liệu giữa các Region. |
| Resource Cleanup | Xóa tài nguyên sau khi hoàn thành Workshop. |

---

# Nội dung đã thực hiện

## 1. Thực hành AWS Cloud9

Trong tuần này, em tìm hiểu và thực hành sử dụng AWS Cloud9 - môi trường phát triển tích hợp (IDE) trên nền tảng AWS.

Các nội dung đã thực hiện gồm:

- Tạo môi trường Cloud9.
- Khởi chạy Cloud9 IDE.
- Tạo Terminal mới.
- Làm quen với giao diện Cloud9.
- Quản lý thư mục và tập tin.
- Chỉnh sửa tệp văn bản trực tiếp trên Cloud9.
- Thực hành lưu và quản lý mã nguồn.

Qua Workshop này, em hiểu cách sử dụng Cloud9 để phát triển ứng dụng trực tiếp trên môi trường AWS mà không cần cài đặt công cụ lập trình trên máy cá nhân.

<p align="center">
<img src="/images/cloud9-create.png" width="700">
</p>

<p align="center">
<i>Hình 13. Khởi tạo môi trường phát triển AWS Cloud9.</i>
</p>

---

## 2. Thực hành Linux Command và AWS CLI

Sau khi tạo Cloud9, em tiếp tục thực hành các lệnh Linux và AWS CLI.

Các nội dung đã thực hiện gồm:

- Sử dụng Terminal trên Cloud9.
- Thực hành các lệnh Linux cơ bản:
  - pwd
  - ls
  - cd
  - mkdir
  - touch
  - rm
- Chỉnh sửa tệp README.md.
- Tạo mới các tệp văn bản.
- Quay lại giao diện AWS Management Console.

Đồng thời em sử dụng AWS CLI để:

- Kiểm tra cấu hình AWS CLI.
- Liệt kê EC2 Instances.
- Kiểm tra các Region.
- Quản lý tài nguyên AWS thông qua dòng lệnh.

Thông qua Workshop này em hiểu cách quản lý dịch vụ AWS bằng AWS CLI cũng như làm quen với môi trường Linux.

<p align="center">
<img src="/images/cloud9-cli.png" width="700">
</p>

<p align="center">
<i>Hình 14. Thực hành Linux Command và AWS CLI trên Cloud9.</i>
</p>

---

## 3. Triển khai Static Website bằng Amazon S3

Trong Workshop tiếp theo, em thực hành triển khai website tĩnh bằng Amazon S3.

Các nội dung đã thực hiện:

- Tạo Amazon S3 Bucket.
- Upload mã nguồn website.
- Bật Static Website Hosting.
- Cấu hình Public Access.
- Thiết lập Bucket Policy.
- Kiểm tra website sau khi triển khai.

Qua bài thực hành này em hiểu cách Amazon S3 có thể hoạt động như một Web Server để lưu trữ và phân phối website tĩnh.

<p align="center">
<img src="/images/s3b.png" width="700">
</p>

<p align="center">
<i>Hình 15. Triển khai Static Website Hosting trên Amazon S3.</i>
</p>

---

## 4. Tăng tốc website với Amazon CloudFront

Sau khi triển khai website trên Amazon S3, em tiếp tục cấu hình Amazon CloudFront để tối ưu tốc độ truy cập.

Các nội dung đã thực hiện gồm:

- Tạo CloudFront Distribution.
- Cấu hình Origin từ Amazon S3.
- Thiết lập Cache Behavior.
- Kiểm tra website thông qua CloudFront.
- So sánh tốc độ truy cập giữa S3 và CloudFront.

Qua Workshop này em hiểu vai trò của Content Delivery Network (CDN) trong việc tăng tốc độ truy cập và giảm độ trễ khi người dùng truy cập website.

<p align="center">
<img src="/images/cloudfront.png" width="700">
</p>

<p align="center">
<i>Hình 16. Cấu hình Amazon CloudFront.</i>
</p>

---

## 5. Amazon S3 Versioning và Replication

Để nâng cao khả năng bảo vệ dữ liệu, em tiếp tục tìm hiểu các tính năng nâng cao của Amazon S3.

Các nội dung đã thực hiện gồm:

- Bật Bucket Versioning.
- Upload nhiều phiên bản của cùng một tệp.
- Khôi phục phiên bản cũ.
- Di chuyển đối tượng trong Bucket.
- Tìm hiểu Cross-Region Replication (CRR).
- Tìm hiểu cơ chế sao lưu dữ liệu giữa nhiều Region.

Qua Workshop này em hiểu cách Amazon S3 bảo vệ dữ liệu trước các thao tác ghi đè hoặc xóa nhầm, đồng thời nâng cao khả năng sẵn sàng của dữ liệu.

---

## 6. Dọn dẹp tài nguyên

Sau khi hoàn thành toàn bộ Workshop, em tiến hành xóa các tài nguyên để tránh phát sinh chi phí.

Các nội dung đã thực hiện gồm:

- Xóa môi trường Cloud9.
- Xóa CloudFront Distribution.
- Xóa Bucket và các Object trong S3.
- Kiểm tra lại toàn bộ tài nguyên AWS.

Qua đó em hiểu tầm quan trọng của việc quản lý và tối ưu chi phí khi sử dụng dịch vụ điện toán đám mây.

---

# Kiến thức tiếp thu

Sau khi hoàn thành tuần thứ năm, em đã:

- Hiểu cách sử dụng AWS Cloud9.
- Thực hành thành thạo các lệnh Linux cơ bản.
- Quản lý tài nguyên AWS bằng AWS CLI.
- Triển khai website tĩnh trên Amazon S3.
- Cấu hình Static Website Hosting.
- Cấu hình Amazon CloudFront.
- Hiểu cơ chế hoạt động của CDN.
- Quản lý phiên bản dữ liệu với Amazon S3 Versioning.
- Tìm hiểu Cross-Region Replication.
- Biết cách dọn dẹp tài nguyên nhằm tối ưu chi phí.

---

# Kết quả đạt được

- Hoàn thành Workshop AWS Cloud9.
- Thực hành Linux Command và AWS CLI.
- Triển khai thành công website tĩnh trên Amazon S3.
- Cấu hình Amazon CloudFront.
- Bật Bucket Versioning.
- Tìm hiểu Cross-Region Replication.
- Thực hiện dọn dẹp toàn bộ tài nguyên sau khi hoàn thành bài Lab.
- Nâng cao kỹ năng sử dụng dịch vụ lưu trữ và phân phối nội dung trên AWS.

---

# Khó khăn gặp phải

Trong quá trình thực hành, em gặp một số khó khăn:

- Chưa quen với giao diện AWS Cloud9.
- Cần thời gian để ghi nhớ các lệnh Linux.
- Việc cấu hình Bucket Policy và Public Access khá phức tạp.
- CloudFront cần thời gian để hoàn tất triển khai.
- Chưa quen với cơ chế Versioning và Replication của Amazon S3.

---

# Cách giải quyết

Để khắc phục các khó khăn trên, em đã:

- Thực hành nhiều lần trên Cloud9.
- Đọc tài liệu AWS Documentation.
- Làm theo hướng dẫn của Workshop.
- Kiểm tra kỹ các thiết lập Bucket Policy.
- Chờ CloudFront triển khai hoàn tất trước khi kiểm thử.
- Xóa toàn bộ tài nguyên sau khi hoàn thành bài Lab.
- Trao đổi với mentor khi gặp lỗi trong quá trình cấu hình.

---

# Đánh giá tuần

Tuần thứ năm giúp em làm quen với môi trường phát triển AWS Cloud9, sử dụng AWS CLI để quản lý tài nguyên và triển khai website tĩnh trên Amazon S3 kết hợp với Amazon CloudFront. Bên cạnh đó, em cũng hiểu rõ hơn về các tính năng nâng cao của Amazon S3 như Versioning và Cross-Region Replication nhằm đảm bảo tính an toàn và khả năng sẵn sàng của dữ liệu. Những kiến thức và kỹ năng này là nền tảng quan trọng để tiếp tục triển khai các ứng dụng web và hệ thống lưu trữ trên AWS trong các tuần tiếp theo.