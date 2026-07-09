---
title: "Worklog Tuần 11"
date: 2024-01-01
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

**Tuần 11:** 29/06–05/07/2026

### Mục tiêu tuần 11:

- Khởi động workshop **DACSWEBSK**: chuẩn bị IAM, dựng VPC và triển khai RDS SQL Server.
- Deploy ứng dụng ASP.NET Core lên EC2, tích hợp S3/SES và đưa traffic qua ALB + WAF.

### Các nhiệm vụ trong tuần:

| Thứ | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - **Workshop [5.1–5.2]:** đọc tổng quan kiến trúc DACSWEBSK trên AWS <br> - Tạo IAM user `dacswebsk-dev`, cấu hình AWS CLI; kiểm tra quyền truy cập | 29/06/2026 | 29/06/2026 | [5.1 Tổng quan](../../5-Workshop/5.1-Workshop-overview/) · [5.2 Chuẩn bị](../../5-Workshop/5.2-Prerequisite/) |
| 3 | - **Workshop [5.3]:** tạo VPC `dacswebsk-vpc`, subnet public/private (2 AZ) <br> - Cấu hình Internet Gateway, route table, Security Group cho EC2 và RDS | 30/06/2026 | 30/06/2026 | [5.3 VPC & mạng](../../5-Workshop/5.3-VPC-Networking/) |
| 4 | - **Workshop [5.4]:** tạo RDS SQL Server Express `dacswebsk-db` <br> - DB subnet group, SG inbound 1433; migrate schema và dữ liệu mẫu | 01/07/2026 | 01/07/2026 | [5.4 Amazon RDS](../../5-Workshop/5.4-RDS/) |
| 5 | - **Workshop [5.6 — EC2]:** launch EC2 `dacswebsk-app`, cài .NET 8 runtime <br> - Deploy DACSWEBSK, cấu hình connection string RDS; kiểm tra app chạy cổng 80 | 02/07/2026 | 02/07/2026 | [5.6 EC2, ALB & WAF](../../5-Workshop/5.6-EC2-ALB-WAF/) |
| 6 | - **Workshop [5.5]:** tạo S3 bucket (ảnh, video, chứng chỉ, upload) <br> - Cấu hình SES thay Gmail SMTP; test upload file và gửi email thông báo | 03/07/2026 | 03/07/2026 | [5.5 S3 & SES](../../5-Workshop/5.5-S3-SES/) |
| 7 | - **Workshop [5.6 — ALB & WAF]:** tạo ALB `dacswebsk-alb` + target group healthy <br> - Gắn AWS WAF protection pack; truy cập ứng dụng qua DNS ALB | 04/07/2026 | 04/07/2026 | [5.6 EC2, ALB & WAF](../../5-Workshop/5.6-EC2-ALB-WAF/) |

### Kết quả đạt được tuần 11:

- Hoàn thành nền tảng workshop: IAM, VPC, RDS và EC2 chạy ứng dụng DACSWEBSK kết nối database.
- File storage chuyển sang S3, email giao dịch qua SES hoạt động.
- Ứng dụng truy cập được qua ALB với WAF bảo vệ phía trước.
