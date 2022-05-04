+++
title = "Sử dụng AWS CLI"
weight = 3
chapter = false
pre = "<b>3. </b>"
+++

#### Sử dụng AWS CLI

AWS CLI của AWS là công cụ để quản lý các dịch vụ AWS.Bạn có thể kiểm soát nhiều dịch vụ AWS bằng command line và dễ dàng tự động hóa các dịch vụ của AWS bằng cách tạo ra các file script ( chứ nhiều command line).

AWS CLI đã được cài đặt sẵn và cấu hình sẵn trên Cloud9 instance.

1. Chạy lệnh AWS CLI dưới đây để liệt kê danh sách EC2 instance trong tài khoản của chúng ta.
```
aws ec2 describe-instances
```
![Cloud9](/images/cloud9/016.png?width=90pc)

Chúc mừng bạn đã hoàn thành bài lab cơ bản về AWS Cloud 9. Hãy nhớ thực hiện bước **Dọn dẹp tài nguyên** để tránh phát sinh chi phí ngoài ý muốn nhé.