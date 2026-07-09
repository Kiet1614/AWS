---
title: "Worklog Tuần 7"
date: 2024-01-01
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

**Tuần 7:** 01–07/06/2026

### Mục tiêu tuần 7:

- Nâng cao kiến thức IAM với Permission Boundary và quản lý vận hành hạ tầng bằng AWS Systems Manager.
- Tối ưu EC2, mã hóa dữ liệu với KMS và theo dõi chi phí theo Well-Architected Framework.
- Xây dựng Data Lake trên AWS từ thu thập dữ liệu đến phân tích và trực quan hóa.

### Các nhiệm vụ trong tuần:

| Thứ | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - **IAM Permission Boundary:** tìm hiểu giới hạn quyền tối đa cho User/Group <br> - **Thực hành:** tạo Boundary Policy, tạo IAM User bị giới hạn <br> - Kiểm tra effective permissions (giao của identity policy và boundary); dọn dẹp | 01/06/2026 | 01/06/2026 | [https://000030.awsstudygroup.com/](https://000030.awsstudygroup.com/) |
| 3 | - **AWS Systems Manager:** quản lý tập trung và tự động hóa trên nhiều máy chủ <br> - **Thực hành:** chuẩn bị môi trường, sử dụng Patch Manager cập nhật bản vá <br> - Chạy lệnh đồng loạt với Run Command; dọn dẹp tài nguyên | 02/06/2026 | 02/06/2026 | [https://000031.awsstudygroup.com/](https://000031.awsstudygroup.com/) |
| 4 | - **Chọn kích cỡ EC2 chính xác:** thu thập metric memory qua CloudWatch Agent <br> - **Thực hành:** tạo IAM Role, gắn role cho EC2, cài CloudWatch Agent <br> - Cập nhật EC2 Resource Optimization; áp dụng đề xuất AWS Compute Optimizer | 03/06/2026 | 03/06/2026 | [https://000032.awsstudygroup.com/](https://000032.awsstudygroup.com/) |
| 5 | - **Mã hóa với AWS KMS:** mã hóa dữ liệu at-rest trên S3 bằng KMS key <br> - **Thực hành:** tạo KMS key, bucket S3 mã hóa, thiết lập CloudTrail và Athena <br> - Kiểm thử chia sẻ dữ liệu mã hóa; truy vấn log qua Athena và dọn dẹp | 04/06/2026 | 04/06/2026 | [https://000033.awsstudygroup.com/](https://000033.awsstudygroup.com/) |
| 6 | - **Trực quan hóa chi phí:** theo dõi cost & usage theo Well-Architected Framework <br> - **Thực hành:** xem chi phí theo dịch vụ/tài khoản, Savings Plan và Reserved Instance coverage <br> - Phân tích bằng Cost Explorer; tạo báo cáo EC2 tùy chỉnh, đánh giá data transfer out | 05/06/2026 | 05/06/2026 | [https://000034.awsstudygroup.com/](https://000034.awsstudygroup.com/) |
| 7 | - **Data Lake on AWS:** tìm hiểu khái niệm Data Lake và kiến trúc ingest–store–analyze <br> - **Thực hành:** thu thập & lưu trữ dữ liệu, tạo Data Catalog bằng AWS Glue <br> - Chuyển đổi dữ liệu; phân tích và trực quan hóa với QuickSight; dọn dẹp | 06/06/2026 | 06/06/2026 | [https://000035.awsstudygroup.com/](https://000035.awsstudygroup.com/) |

### Kết quả đạt được tuần 7:

- Áp dụng IAM Permission Boundary để giới hạn quyền tối đa của user, hiểu effective permissions.
- Sử dụng Systems Manager Patch Manager và Run Command để quản lý patch và thực thi lệnh trên nhiều EC2.
- Thu thập metric CloudWatch Agent, right-size EC2 với Resource Optimization và Compute Optimizer.
- Mã hóa dữ liệu S3 bằng KMS, ghi audit log CloudTrail và truy vấn log qua Athena.
- Phân tích và trực quan hóa chi phí AWS bằng Cost Explorer, theo dõi Savings Plan/RI coverage.
- Xây dựng pipeline Data Lake cơ bản: ingest → Glue Catalog → transform → phân tích với QuickSight.
