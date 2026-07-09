---
title: "Worklog Tuần 5"
date: 2024-01-01
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

**Tuần 5:** 18–24/05/2026

### Mục tiêu tuần 5:

- Thiết lập pipeline CI/CD cho container trên ECS và triển khai ứng dụng Node.js lên EC2 bằng bộ dịch vụ Code*.
- Tăng cường bảo mật với AWS Security Hub và tối ưu chi phí EC2 bằng Lambda tự động hóa.
- Kết nối mạng đa VPC qua VPC Peering và AWS Transit Gateway.

### Các nhiệm vụ trong tuần:

| Thứ | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - **CI/CD với ECS Container:** tìm hiểu CI/CD, chuẩn bị môi trường <br> - **Thực hành:** triển khai pipeline với GitLab, GitHub Actions và CodeBuild <br> - Giám sát bằng Container Insights (CloudWatch); định tuyến logs với Firelens và dọn dẹp | 18/05/2026 | 18/05/2026 | [https://000017.awsstudygroup.com/](https://000017.awsstudygroup.com/) |
| 3 | - **AWS Security Hub:** tìm hiểu tổng quan, tập hợp cảnh báo từ GuardDuty, Inspector, Macie <br> - **Thực hành:** kích hoạt Security Hub, xem điểm từng bộ tiêu chuẩn bảo mật (CIS, PCI…) <br> - Theo dõi compliance trên dashboard; dọn dẹp tài nguyên | 19/05/2026 | 19/05/2026 | [https://000018.awsstudygroup.com/](https://000018.awsstudygroup.com/) |
| 4 | - **VPC Peering:** tìm hiểu kết nối giữa hai VPC không qua internet công cộng <br> - **Thực hành:** chuẩn bị VPC, cập nhật Network ACL, tạo Peering connection <br> - Kích hoạt Cross-Peer DNS; kiểm tra kết nối giữa các subnet và dọn dẹp | 20/05/2026 | 20/05/2026 | [https://000019.awsstudygroup.com/](https://000019.awsstudygroup.com/) |
| 5 | - **AWS Transit Gateway:** tìm hiểu mô hình hub-and-spoke kết nối nhiều VPC <br> - **Thực hành:** tạo Transit Gateway, attachments cho 4 VPC, Transit Gateway Route Tables <br> - Thêm route vào VPC Route Tables; kiểm tra kết nối giữa các EC2 host và dọn dẹp | 21/05/2026 | 21/05/2026 | [https://000020.awsstudygroup.com/](https://000020.awsstudygroup.com/) |
| 6 | - **Tối ưu chi phí EC2 với Lambda:** tự động start/stop instance theo lịch để tiết kiệm chi phí <br> - **Thực hành:** gắn Tag cho instance, tạo IAM Role và Lambda Function <br> - Thiết lập CloudWatch Rule (EventBridge) kích hoạt Lambda; gửi thông báo Slack và dọn dẹp | 22/05/2026 | 22/05/2026 | [https://000022.awsstudygroup.com/](https://000022.awsstudygroup.com/) |
| 7 | - **CI/CD lên EC2 với CodePipeline:** tìm hiểu DevOps và văn hóa CI/CD trên AWS <br> - **Thực hành:** cài CodeDeploy Agent, thiết lập CodeCommit, CodeBuild, CodeDeploy <br> - Tạo CodePipeline build & deploy ứng dụng Node.js lên EC2; xử lý lỗi và dọn dẹp | 23/05/2026 | 23/05/2026 | [https://000023.awsstudygroup.com/](https://000023.awsstudygroup.com/) |

### Kết quả đạt được tuần 5:

- Triển khai pipeline CI/CD cho ECS container qua GitLab, GitHub Actions và CodeBuild; giám sát bằng Container Insights và định tuyến log với Firelens.
- Kích hoạt AWS Security Hub, theo dõi điểm compliance và tập hợp cảnh báo bảo mật từ nhiều dịch vụ AWS trên một dashboard.
- Thiết lập VPC Peering giữa hai VPC, cấu hình NACL, Cross-Peer DNS và kiểm tra kết nối nội bộ an toàn.
- Kết nối 4 VPC qua AWS Transit Gateway với attachments, route tables và routing phù hợp.
- Tự động hóa start/stop EC2 bằng Lambda và EventBridge để tối ưu chi phí, kèm thông báo trạng thái.
- Xây dựng pipeline CI/CD đầy đủ (CodeCommit → CodeBuild → CodeDeploy → CodePipeline) triển khai ứng dụng Node.js lên EC2.
