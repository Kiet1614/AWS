---
title: "Worklog Tuần 9"
date: 2024-01-01
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

**Tuần 9:** 15–21/06/2026

### Mục tiêu tuần 9:

- Tối ưu chi phí EC2/RDS bằng Savings Plans và Reserved Instances.
- Thực hành di dời cơ sở dữ liệu với Schema Conversion Tool và AWS DMS.
- Củng cố IAM Role với Condition; triển khai ứng dụng trên Amazon Lightsail và Lightsail Containers.

### Các nhiệm vụ trong tuần:

| Thứ | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - **Savings Plan, Reserved Instance & Reserved DB:** tìm hiểu mô hình cam kết sử dụng giảm chi phí EC2/RDS <br> - **Thực hành:** xem Savings Plans Recommendation, mua gói Savings Plan <br> - Tìm hiểu Reserved Instance và Reserved DB Instance cho Amazon RDS | 15/06/2026 | 15/06/2026 | [https://000042.awsstudygroup.com/](https://000042.awsstudygroup.com/) |
| 3 | - **Chuyển đổi lược đồ & di dời CSDL:** SCT chuyển schema heterogeneous; DMS migrate dữ liệu <br> - **Thực hành:** chọn source/target cho DMS, serverless replication <br> - Theo dõi migration, xử lý sự cố DMS và dọn dẹp môi trường | 16/06/2026 | 16/06/2026 | [https://000043.awsstudygroup.com/](https://000043.awsstudygroup.com/) |
| 4 | - **IAM Role & Condition:** áp dụng least privilege cho EC2 và RDS <br> - **Thực hành:** tạo IAM Group, IAM User với quyền theo dịch vụ <br> - Cấu hình Role Condition giới hạn theo IP và thời gian; dọn dẹp | 17/06/2026 | 17/06/2026 | [https://000044.awsstudygroup.com/](https://000044.awsstudygroup.com/) |
| 5 | - **Lightsail Workshop — Cost Optimization:** triển khai ứng dụng trên Lightsail với chi phí dự đoán được <br> - **Thực hành:** deploy Lightsail Database, WordPress, PrestaShop, Akaunting <br> - Bảo mật ứng dụng, tạo snapshot, scale instance, thiết lập cảnh báo và dọn dẹp | 18/06/2026 | 18/06/2026 | [https://000045.awsstudygroup.com/](https://000045.awsstudygroup.com/) |
| 6 | - **Lightsail Container:** chạy ứng dụng container trên Lightsail với trải nghiệm đơn giản <br> - **Thực hành:** chuẩn bị môi trường, tạo Container Service <br> - Triển khai public image và custom image từ DockerHub/local; dọn dẹp tài nguyên | 19/06/2026 | 19/06/2026 | [https://000046.awsstudygroup.com/](https://000046.awsstudygroup.com/) |

### Kết quả đạt được tuần 9:

- Hiểu và áp dụng Savings Plans, Reserved Instance và Reserved DB Instance để giảm chi phí EC2/RDS.
- Sử dụng AWS SCT chuyển đổi schema và DMS di dời dữ liệu với serverless replication, theo dõi và xử lý sự cố migration.
- Cấu hình IAM User/Group/Role với Condition theo IP và thời gian, tuân thủ nguyên tắc least privilege.
- Triển khai nhiều ứng dụng (WordPress, PrestaShop, Akaunting) trên Lightsail, backup snapshot và scale instance.
- Deploy ứng dụng container trên Amazon Lightsail Container Service từ public registry và custom Docker image.
