---
title: "Worklog Tuần 8"
date: 2024-01-01
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

**Tuần 8:** 08–14/06/2026

### Mục tiêu tuần 8:

- Triển khai Infrastructure as Code với CloudFormation và AWS CDK.
- Làm sâu DynamoDB, phân tích dữ liệu bằng Glue/Athena và tích hợp định danh liên kết với Azure AD.
- Hoàn thiện kiến trúc Data Lake từ thu thập dữ liệu đến trực quan hóa.

### Các nhiệm vụ trong tuần:

| Thứ | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - **Data Lake on AWS:** tìm hiểu khái niệm Data Lake, đặc điểm collect-all / multi-user / flexible access <br> - **Thực hành:** thu thập & lưu trữ dữ liệu, tạo Data Catalog với AWS Glue <br> - Chuyển đổi dữ liệu; phân tích và trực quan hóa bằng QuickSight; dọn dẹp | 08/06/2026 | 08/06/2026 | [https://000036.awsstudygroup.com/](https://000036.awsstudygroup.com/) |
| 3 | - **AWS CloudFormation:** mô hình hóa hạ tầng bằng template YAML/JSON <br> - **Thực hành:** chuẩn bị môi trường (Cloud9), CloudFormation cơ bản và nâng cao <br> - Triển khai stack tự động, cập nhật và xóa stack; dọn dẹp tài nguyên | 09/06/2026 | 09/06/2026 | [https://000037.awsstudygroup.com/](https://000037.awsstudygroup.com/) |
| 4 | - **CDK cơ bản:** định nghĩa hạ tầng bằng TypeScript/Python thay vì YAML thuần <br> - **Thực hành:** tìm hiểu CDK trên nền CloudFormation, tạo CDK Template <br> - Cập nhật template, deploy kiến trúc cơ bản lên AWS; dọn dẹp | 10/06/2026 | 10/06/2026 | [https://000038.awsstudygroup.com/](https://000038.awsstudygroup.com/) |
| 5 | - **Amazon DynamoDB Immersion Day:** hands-on labs DynamoDB nâng cao <br> - **Thực hành:** LHOL cơ bản, design patterns (LADV), Change Data Capture (LCDC) <br> - Event-driven architecture (LEDA), global serverless apps (LMR), data modeling (LGME) | 11/06/2026 | 11/06/2026 | [https://000039.awsstudygroup.com/](https://000039.awsstudygroup.com/) |
| 6 | - **Phân tích chi phí & hiệu năng với Glue và Athena:** thiết lập nền tảng phân tích báo cáo hệ thống <br> - **Thực hành:** Glue Crawler quét dữ liệu S3, tạo Parquet Data Catalog <br> - Truy vấn SQL bằng Athena phân tích cost/performance; dọn dẹp | 12/06/2026 | 12/06/2026 | [https://000040.awsstudygroup.com/](https://000040.awsstudygroup.com/) |
| 7 | - **IAM Federation từ Azure AD:** tích hợp Microsoft Entra ID (Azure AD) với AWS qua SAML SSO <br> - **Thực hành:** tạo Enterprise Application, Identity Provider và IAM Role trên AWS <br> - Đồng bộ role, cấu hình Provisioning; federate user Azure AD truy cập AWS; dọn dẹp | 13/06/2026 | 13/06/2026 | [https://000041.awsstudygroup.com/](https://000041.awsstudygroup.com/) |

### Kết quả đạt được tuần 8:

- Xây dựng pipeline Data Lake hoàn chỉnh: ingest → Glue Catalog → transform → QuickSight visualization.
- Triển khai và quản lý hạ tầng AWS bằng CloudFormation template và AWS CDK.
- Nắm các design pattern DynamoDB nâng cao: CDC, event-driven, global tables và data modeling.
- Phân tích chi phí và hiệu năng hệ thống bằng AWS Glue Crawler và truy vấn Athena trên Parquet catalog.
- Thiết lập IAM Federation SAML giữa Azure AD và AWS, cho phép user đăng nhập SSO và assume role theo quyền.
