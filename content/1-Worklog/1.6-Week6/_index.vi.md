---
title: "Worklog Tuần 6"
date: 2024-01-01
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

**Tuần 6:** 25–31/05/2026

### Mục tiêu tuần 6:

- Triển khai giải pháp lưu trữ file hybrid với AWS Storage Gateway và Amazon FSx for Windows.
- Bảo vệ ứng dụng web bằng AWS WAF và quản lý tài nguyên tập trung qua Tag, Resource Groups và IAM.
- Thiết lập giám sát hạ tầng AWS bằng Grafana trên EC2.

### Các nhiệm vụ trong tuần:

| Thứ | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - **File Storage Gateway:** tìm hiểu mô hình file sharing hybrid cloud–on-premises <br> - **Thực hành:** chuẩn bị môi trường, tạo Storage Gateway và File Share <br> - Kết nối file share tới máy on-premises; dọn dẹp tài nguyên | 25/05/2026 | 25/05/2026 | [https://000024.awsstudygroup.com/](https://000024.awsstudygroup.com/) |
| 3 | - **FSx trên Windows:** tìm hiểu kiến trúc FSx for Windows File Server (SMB, S3, VPC) <br> - **Thực hành:** chuẩn bị, tạo file share, kiểm tra và giám sát hiệu năng <br> - Bật deduplication, shadow copies, quota người dùng; mở rộng throughput | 26/05/2026 | 26/05/2026 | [https://000025.awsstudygroup.com/](https://000025.awsstudygroup.com/) |
| 4 | - **AWS WAF:** tìm hiểu Web Application Firewall và bảo vệ ứng dụng web <br> - **Thực hành:** chuẩn bị môi trường, cấu hình rule WAF (allow/block) <br> - Gắn WAF vào ALB hoặc CloudFront; kiểm tra chặn request độc hại và dọn dẹp | 27/05/2026 | 27/05/2026 | [https://000026.awsstudygroup.com/](https://000026.awsstudygroup.com/) |
| 5 | - **Tag và Resource Groups:** tìm hiểu Tag (Key/Value) để phân loại tài nguyên AWS <br> - **Thực hành:** gắn tag cho EC2, EBS và tài nguyên liên quan <br> - Tạo Resource Group theo tag; quản lý tập tài nguyên đồng loạt và dọn dẹp | 28/05/2026 | 28/05/2026 | [https://000027.awsstudygroup.com/](https://000027.awsstudygroup.com/) |
| 6 | - **IAM với EC2 Resource Tag:** quản lý truy cập EC2 theo tag qua IAM Policy và Role <br> - **Thực hành:** tạo IAM Policy giới hạn quyền theo Resource Tag <br> - Tạo IAM Role cho EC2 Administrator; kiểm tra policy hoạt động đúng và dọn dẹp | 29/05/2026 | 29/05/2026 | [https://000028.awsstudygroup.com/](https://000028.awsstudygroup.com/) |
| 7 | - **Grafana trên AWS:** tìm hiểu Grafana để trực quan hóa và giám sát tài nguyên AWS <br> - **Thực hành:** chuẩn bị EC2 Linux, cài đặt Grafana <br> - Kết nối nguồn dữ liệu CloudWatch; tạo dashboard theo dõi metric và dọn dẹp | 30/05/2026 | 30/05/2026 | [https://000029.awsstudygroup.com/](https://000029.awsstudygroup.com/) |

### Kết quả đạt được tuần 6:

- Triển khai AWS Storage Gateway và File Share, kết nối chia sẻ file giữa cloud và môi trường on-premises.
- Cấu hình Amazon FSx for Windows File Server với các tính năng quản lý file nâng cao (deduplication, shadow copies, quota, throughput).
- Thiết lập AWS WAF bảo vệ ứng dụng web trước các request độc hại.
- Sử dụng Tag và Resource Groups để phân loại và quản lý tập tài nguyên AWS có hệ thống.
- Áp dụng IAM Policy dựa trên Resource Tag để kiểm soát quyền truy cập EC2 theo nguyên tắc least privilege.
- Cài đặt Grafana trên EC2, kết nối CloudWatch và xây dựng dashboard giám sát hạ tầng AWS.
