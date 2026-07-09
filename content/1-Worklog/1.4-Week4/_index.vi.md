---
title: "Worklog Tuần 4"
date: 2024-01-01
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

**Tuần 4:** 11–17/05/2026

### Mục tiêu tuần 4:

- Làm quen và thành thạo thao tác AWS qua Command Line Interface (CLI).
- Nắm quản lý định danh tập trung với IAM Identity Center và các mô hình backup, migration.
- Thực hành container hóa ứng dụng với Docker, ECR và triển khai trên Amazon ECS.

### Các nhiệm vụ trong tuần:


| Thứ | Nhiệm vụ                                                                                                                                                                                                                                                                                          | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                                                         |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ---------------------------------------------------------------------- |
| 2   | - **Làm quen với AWS CLI:** giới thiệu, chuẩn bị môi trường và cài đặt CLI trên Windows - Kiểm tra tài nguyên qua CLI; thao tác với **Amazon S3**, **SNS**, **IAM** và **VPC** - **Thực hành:** tạo EC2 bằng CLI, xử lý lỗi thường gặp và dọn dẹp tài nguyên                                      | 11/05/2026   | 11/05/2026      | [https://000011.awsstudygroup.com/](https://000011.awsstudygroup.com/) |
| 3   | - **IAM Identity Center:** tìm hiểu mô hình quản lý định danh tập trung cho nhiều tài khoản AWS - Cấu hình truy cập AWS CLI qua Identity Center; thiết lập **Time-based access control** - **Thực hành:** Customer Managed Policies, Identity Store APIs và dọn dẹp                               | 12/05/2026   | 12/05/2026      | [https://000012.awsstudygroup.com/](https://000012.awsstudygroup.com/) |
| 4   | - **AWS Backup:** tìm hiểu tổng quan dịch vụ backup tập trung cho EBS, RDS, DynamoDB, EFS - **Thực hành:** tạo Backup plan, thiết lập thông báo khi backup thành công/thất bại - Kiểm tra hoạt động backup & restore; dọn dẹp tài nguyên                                                          | 13/05/2026   | 13/05/2026      | [https://000013.awsstudygroup.com/](https://000013.awsstudygroup.com/) |
| 5   | - **VM Import/Export:** tìm hiểu khái niệm import/export máy ảo giữa môi trường on-premises và EC2 - Chuẩn bị máy ảo (VMware Workstation, AWS CLI); import VM vào AWS qua S3 - **Thực hành:** export EC2 instance từ AWS, xem video tham khảo và dọn dẹp                                          | 14/05/2026   | 14/05/2026      | [https://000014.awsstudygroup.com/](https://000014.awsstudygroup.com/) |
| 6   | - **Docker trên AWS:** triển khai ứng dụng cục bộ bằng Docker; chuẩn bị môi trường AWS - Cấu hình **Amazon RDS** và **EC2**; triển khai bằng Docker image và **Docker Compose** - **Thực hành:** đẩy image lên **Amazon ECR**, cấu hình Security Group và dọn dẹp                                 | 15/05/2026   | 15/05/2026      | [https://000015.awsstudygroup.com/](https://000015.awsstudygroup.com/) |
| 7   | - **Amazon ECS:** tìm hiểu kiến trúc triển khai container với Fargate, ALB và Service Discovery - **Thực hành:** đăng ký namespace Cloud Map, tạo ECS Cluster, Task Definition và ECS Service - Cấu hình Application Load Balancer; kiểm tra kết quả triển khai frontend/backend + RDS và dọn dẹp | 16/05/2026   | 16/05/2026      | [https://000016.awsstudygroup.com/](https://000016.awsstudygroup.com/) |




### Kết quả đạt được tuần 4:

- Cài đặt và sử dụng AWS CLI để quản lý S3, SNS, IAM, VPC và tạo EC2 từ dòng lệnh, không phụ thuộc hoàn toàn vào Console.
- Hiểu cách triển khai IAM Identity Center với nguyên tắc least privilege, time-based access và Customer Managed Policies cho nhiều tài khoản.
- Tạo được Backup plan tập trung cho nhiều loại tài nguyên (EBS, RDS, DynamoDB, EFS), thiết lập thông báo và thực hiện kiểm tra restore.
- Nắm quy trình VM Import/Export để migrate workload on-premises lên EC2 và export ngược lại, sử dụng S3 làm trung gian lưu trữ.
- Container hóa ứng dụng với Docker trên EC2, triển khai bằng Docker Compose, đẩy image lên ECR và tuân thủ cấu hình bảo mật mạng.
- Triển khai ứng dụng đa tầng (frontend/backend) trên Amazon ECS Fargate với ALB, Cloud Map Service Discovery và kết nối RDS MySQL.

