---
title: "Worklog Tuần 10"
date: 2024-01-01
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

**Tuần 10:** 22–28/06/2026

### Mục tiêu tuần 10:

- Điều phối workflow serverless với AWS Step Functions và cấp quyền ứng dụng qua IAM Role.
- Làm việc trên AWS Cloud9; triển khai ứng dụng monolith lên Elastic Beanstalk.
- Thiết lập pipeline CI/CD tự động phát hành ứng dụng bằng CodeStar và CodeDeploy.

### Các nhiệm vụ trong tuần:

| Thứ | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - **AWS Step Functions:** điều phối workflow giữa các dịch vụ AWS <br> - **Thực hành:** tạo state machine với Task, Choice, Parallel state <br> - Xử lý lỗi, waitForTaskToken (pause/resume); debug trên console và dọn dẹp | 22/06/2026 | 22/06/2026 | [https://000047.awsstudygroup.com/](https://000047.awsstudygroup.com/) |
| 3 | - **IAM Role cho ứng dụng:** cấp quyền ứng dụng truy cập dịch vụ AWS an toàn <br> - **Thực hành:** so sánh access key vs IAM Role (khuyến nghị dùng Role) <br> - Gắn IAM Role lên EC2 để ứng dụng truy cập S3/RDS…; dọn dẹp | 23/06/2026 | 23/06/2026 | [https://000048.awsstudygroup.com/](https://000048.awsstudygroup.com/) |
| 4 | - **AWS Cloud9:** IDE trên trình duyệt với editor, debugger và terminal tích hợp <br> - **Thực hành:** tạo Cloud9 environment, làm quen tính năng cơ bản <br> - Sử dụng AWS CLI trong Cloud9; dọn dẹp tài nguyên | 24/06/2026 | 24/06/2026 | [https://000049.awsstudygroup.com/](https://000049.awsstudygroup.com/) |
| 5 | - **Chuyển đổi ứng dụng Monolith:** triển khai ứng dụng web TravelBuddy lên AWS <br> - **Thực hành:** test local bằng Eclipse IDE, deploy lên **Elastic Beanstalk** <br> - Cập nhật ứng dụng, truy vấn API qua Eclipse; dọn dẹp | 25/06/2026 | 25/06/2026 | [https://000050.awsstudygroup.com/](https://000050.awsstudygroup.com/) |
| 6 | - **Tự động phát hành ứng dụng:** CI/CD cho TravelBuddy trên Elastic Beanstalk <br> - **Thực hành:** cấu hình phát hành tự động với **AWS CodeStar** <br> - Triển khai Windows Service bằng CodeDeploy trên EC2; giám sát dịch vụ và dọn dẹp | 26/06/2026 | 26/06/2026 | [https://000051.awsstudygroup.com/](https://000051.awsstudygroup.com/) |

### Kết quả đạt được tuần 10:

- Xây dựng workflow Step Functions với Lambda, branching, parallel execution và xử lý lỗi.
- Cấp quyền ứng dụng qua IAM Role trên EC2 thay vì hardcode access key.
- Sử dụng AWS Cloud9 làm môi trường phát triển và thao tác AWS CLI trên cloud.
- Triển khai ứng dụng monolith TravelBuddy lên Elastic Beanstalk và cập nhật phiên bản.
- Thiết lập pipeline CI/CD tự động với CodeStar/CodeDeploy cho Beanstalk và Windows Service.
