---
title: "Event 3"
date: 2026-06-13
weight: 3
chapter: false
pre: " <b> 4.3. </b> "
---


# Bài thu hoạch: “FCAJ Community Day”

### Mục tiêu của sự kiện

- Hiểu hơn về cách thiết kế một dịch vụ rút gọn URL có khả năng mở rộng trên AWS.
- Nắm được hành trình học tập và phát triển từ nền tảng AWS đến việc trở thành thành viên cộng đồng AWS.
- Tìm hiểu vai trò thực sự của kỹ sư DevOps trong các dự án thực tế.
- Khám phá công việc của Data Analytics Engineer trong các công ty đa quốc gia và các kỹ năng cần thiết để phát triển nghề nghiệp.

### Danh sách diễn giả

- **Đinh Trung Kiên**
- **Nguyễn Minh Thọ**
- **Danh Hoàng Hiếu Nghị**
- **Dat Pham**
- **Cường Nguyễn**

### Những điểm nổi bật

#### 1. Dịch vụ rút gọn URL có khả năng mở rộng trên AWS

Buổi đầu tiên giới thiệu về một dịch vụ rút gọn URL chạy trên AWS. Các diễn giả cho biết một hệ thống đơn giản như vậy có ưu điểm là dễ triển khai và chi phí thấp, nhưng cũng có thể gặp các vấn đề như lỗ hổng bảo mật, độ trễ khi đọc, điểm lỗi duy nhất và khó mở rộng. Kiến trúc đề xuất sử dụng Amazon CloudFront, Amazon WAF và Amazon Amplify ở tầng frontend, trong khi backend dựa trên Amazon ECS, Amazon ElastiCache và DynamoDB. Dịch vụ tạo khóa (KGS) sẽ pre-generate các mã ngắn và đẩy vào Redis bằng lệnh LPUSH; luồng tạo URL sẽ lấy mã ngắn bằng RPOP và lưu mapping vào DynamoDB; còn luồng chuyển tiếp thì ưu tiên kiểm tra Redis trước, chỉ truy vấn DynamoDB khi cache miss.

#### 2. Từ First Cloud AI Journey đến AWS Partner

Một buổi chia sẻ khác kể về hành trình phát triển từ sự tò mò ban đầu đến việc trở thành một người đóng góp cho cộng đồng AWS. Người trình bày mô tả một con đường phát triển gồm 8 giai đoạn: tò mò của học sinh, First Cloud Journey, tham gia workshop và cộng đồng, thực hành qua hands-on labs, ứng dụng vào các dự án ở trường, xây dựng portfolio, phát triển thành AWS partner và cuối cùng là chia sẻ lại cho thế hệ sau. Buổi nói cũng giới thiệu chương trình First Cloud AI Journey, AWS Student Builder Group, hệ thống sự kiện và huy hiệu, cũng như chương trình AWS Community Builder. Đây là một buổi chia sẻ rất truyền cảm hứng vì cho thấy việc học AWS không chỉ dừng ở kỹ thuật, mà còn liên quan đến mạng lưới, kinh nghiệm và đóng góp cộng đồng.

#### 3. DevOps Engineer thực sự làm gì?

Buổi chia sẻ về DevOps giải thích rằng DevOps không chỉ là viết CI/CD pipeline hay làm Docker/Kubernetes. Nó là một lĩnh vực bao gồm hợp tác, tự động hóa, quản trị hạ tầng, bảo mật, giám sát và xử lý sự cố. Buổi trình bày nhấn mạnh những kỳ vọng chung trong tuyển dụng, các hiểu lầm phổ biến về DevOps, và thực tế công việc hàng ngày như hỗ trợ developer, xử lý lỗi production, theo dõi alert, kiểm tra chi phí cloud và làm rõ trách nhiệm sở hữu hệ thống. Ngoài ra, người nói cũng nhấn mạnh rằng để làm tốt DevOps, bạn cần hiểu về Linux, mạng, lập trình, Git, CI/CD, container và cách ứng dụng được build, test, deploy và monitor.

#### 4. Data Analytics Engineer trong môi trường đa quốc gia

Buổi trình bày cuối cùng tập trung vào vai trò của Data Analytics Engineer trong các công ty đa quốc gia. Các diễn giả cho biết công việc của vị trí này thay đổi tùy thuộc vào ngành, mô hình kinh doanh và cấu trúc phòng ban. Tại Kamereo và Colgate-Palmolive, công việc có thể bao gồm xây dựng báo cáo hàng ngày, hàng tuần và hàng quý, thiết kế dashboard, phát hiện bất thường, phân tích hiệu suất hoạt động và hỗ trợ chuyển đổi số. Buổi này cũng nhấn mạnh các kỹ năng cần thiết như tư duy phản biện, giao tiếp, kể chuyện bằng dữ liệu và giải quyết vấn đề. Về phát triển sự nghiệp, các diễn giả giới thiệu một mô hình tiến triển từ người thực thi, người học chủ động, người giải quyết vấn đề, người tư duy hệ thống, cho đến người dẫn dắt và định hướng chiến lược.

### Những điều học được

- Một hệ thống tốt cần cân bằng giữa chức năng, hiệu năng, bảo mật và khả năng mở rộng.
- Kiến trúc cloud hiệu quả hơn khi luồng đọc và luồng ghi được tối ưu riêng biệt.
- Các chương trình cộng đồng AWS có thể mở ra cơ hội phát triển kỹ thuật và nghề nghiệp lâu dài.
- DevOps không chỉ là công cụ, mà còn là trách nhiệm, hợp tác và độ tin cậy.
- Công việc phân tích dữ liệu không chỉ là làm số liệu, mà còn là biến dữ liệu thành quyết định và hành động có giá trị.

### Ứng dụng vào công việc

- Áp dụng ý tưởng tách luồng đọc và luồng ghi khi thiết kế các hệ thống mới.
- Sử dụng cache và các dịch vụ ở rìa như CloudFront và WAF để nâng cao hiệu năng và bảo mật.
- Tiếp tục học AWS thông qua thực hành, dự án và các hoạt động cộng đồng.
- Xây dựng thói quen DevOps tốt hơn quanh việc tự động hóa, giám sát và xử lý sự cố.
- Cải thiện kỹ năng giao tiếp dữ liệu để các insight kỹ thuật có thể được hiểu và dùng hiệu quả bởi các bên liên quan.

### Trải nghiệm tham gia sự kiện

Sự kiện này đáng giá vì nó bao quát nhiều lĩnh vực quan trọng của phát triển phần mềm hiện đại trong cùng một không gian. Tôi không chỉ học được về kiến trúc hệ thống và dịch vụ AWS, mà còn hiểu thêm về con đường phát triển nghề nghiệp, văn hóa cộng đồng, DevOps và vai trò của dữ liệu trong doanh nghiệp. Sự kết hợp giữa chiều sâu kỹ thuật và trải nghiệm thực tế khiến buổi sự kiện này vừa truyền cảm hứng vừa rất hữu ích cho việc học tập trong tương lai.

#### Những bài học rút ra

- Kiến trúc tốt không chỉ là làm cho hệ thống chạy được, mà còn phải đảm bảo khả năng mở rộng và độ bền vững.
- Học tập liên tục và thực hành thực tế là chìa khóa để phát triển trong lĩnh vực cloud, DevOps và dữ liệu.
- Sự nghiệp thành công đòi hỏi cả kỹ năng chuyên môn lẫn kỹ năng mềm như giao tiếp, giải quyết vấn đề và làm việc nhóm.

#### Một số khoảnh khắc đáng nhớ

{{< figure src="/images/30-5.jpg" title="Hình 1. Khoảnh khắc đáng nhớ trong buổi chia sẻ kỹ thuật" width="80%" >}}