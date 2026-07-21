---
title: "WAF"
date: 2026-07-21
weight: 4
chapter: false
pre: " <b> 5.4 </b> "
---

#### Tổng quan

Trang này mô tả việc triển khai AWS WAF cho ứng dụng web sử dụng CloudFront, bao gồm tạo protection pack (web ACL), quản lý rule, và thiết lập giám sát.

#### Phạm vi

- Triển khai WAF Web ACL protection pack cho ứng dụng.
- Cấu hình rule AWS managed và custom để chặn lưu lượng đáng ngờ.
- Đính kèm protection pack vào CloudFront hoặc tài nguyên biên khác.
- Xem xét thứ tự rule, giám sát lưu lượng và đề xuất ghi log.

#### Tóm tắt

Protection pack WAF với tên `Nhom4-WebACL-Protection` đã được tạo thành công. Gói này bao gồm nhiều rule theo dõi và chặn, như IPv4/IPv6 allow/block, GeoRule, RateBasedRule cho GET/POST, và BodySizeRestrictionRule. Thiết lập này nâng cao mức độ bảo mật mà vẫn cho phép lưu lượng hợp lệ.

#### Kết quả chi tiết

- Tên protection pack: `Nhom4-WebACL-Protection`
- ARN và ID đã được tạo trong AWS WAF
- Rule bao gồm: `AWS-AWSManagedRulesAntiDDoSRuleSet`, `AWS-AWSManagedRulesAmazonIpReputationList`, `AWS-AWSManagedRulesCommonRuleSet` và các rule khác
- Trạng thái: `Running in Count mode` để đánh giá, đồng thời có thêm rule allow/block

#### Bước kế tiếp

1. Bật logging và sample request để kiểm tra sau.
2. Tinh chỉnh thứ tự rule và rule custom theo lưu lượng thực tế.
3. Cấu hình AI monetization và smart recommendations nếu cần.
4. Xác nhận protection pack đã gắn đúng trên CloudFront distribution.

![WAF protection pack overview](/images/waf1.jpg)
![WAF protection pack overview](/images/waf2.jpg)
