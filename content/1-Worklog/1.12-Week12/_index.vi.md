---
title: "Worklog Tuần 12"
date: 2024-01-01
weight: 12
chapter: false
pre: " <b> 1.12. </b> "
---

**Tuần 12:** 06–12/07/2026

### Mục tiêu tuần 12:

- Hoàn thiện workshop DACSWEBSK: Lambda, EventBridge, chatbot, monitoring và kiểm thử end-to-end (đến 09/07).
- Dọn dẹp tài nguyên AWS, hoàn thiện báo cáo thực tập và kết thúc kỳ thực tập.

### Các nhiệm vụ trong tuần:


| Thứ | Nhiệm vụ                                                                                                                                                                 | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                                                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------ | --------------- | --------------------------------------------------------------------- |
| 2   | - **Workshop [5.7]:** tạo 3 Lambda jobs + EventBridge cron (status, certificate, notification) - Triển khai Lambda chatbot `dacsweb-chatbot` qua API Gateway → RDS       | 06/07/2026   | 06/07/2026      | [5.7 Lambda & EventBridge](../../5-Workshop/5.7-Lambda-EventBridge/)  |
| 3   | - **Workshop [5.7]:** test chatbot widget trên giao diện web; fix lỗi tích hợp - Kiểm tra các scheduled job chạy đúng lịch; ghi chú kết quả                              | 07/07/2026   | 07/07/2026      | [5.7 Lambda & EventBridge](../../5-Workshop/5.7-Lambda-EventBridge/)  |
| 4   | - **Workshop [5.8]:** Secrets Manager, CloudWatch alarms/dashboard, CloudTrail - AWS Backup plan cho RDS; rà soát bảo mật vận hành                                       | 08/07/2026   | 08/07/2026      | [5.8 Monitoring & bảo mật](../../5-Workshop/5.8-Monitoring-Security/) |
| 5   | - **Workshop — hoàn thiện:** kiểm thử end-to-end toàn hệ thống (ALB → app → RDS, S3, SES, Lambda) - Sửa lỗi còn lại; bổ sung screenshot Console vào tài liệu mục 5.1–5.8 | 09/07/2026   | 09/07/2026      | [Workshop DACSWEBSK](../../5-Workshop/)                               |
| 6   | - **Workshop [5.9]:** dọn dẹp EC2, RDS, ALB, Lambda, NAT…; giữ snapshot cần thiết - Rà soát billing; hoàn thiện self-evaluation, feedback và toàn bộ báo cáo Hugo        | 10/07/2026   | 10/07/2026      | [5.9 Dọn dẹp](../../5-Workshop/5.9-Cleanup/)                          |
| 7   | - Tổng kết kỳ thực tập với mentor/nhóm FCJ - Nộp báo cáo, kết thúc thực tập                                                                                              | 11/07/2026   | 12/07/2026      | —                                                                     |




### Kết quả đạt được tuần 12:

- Lambda chatbot, 3 background jobs và EventBridge hoạt động ổn định.
- Secrets Manager, CloudWatch, CloudTrail và AWS Backup được cấu hình đầy đủ.
- Hệ thống DACSWEBSK vận hành end-to-end trên AWS; tài liệu workshop hoàn chỉnh kèm screenshot.
- Tài nguyên AWS dọn dẹp đúng quy trình; báo cáo thực tập 12 tuần hoàn thiện và nộp đúng hạn.

