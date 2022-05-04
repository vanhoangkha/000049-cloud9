+++
title = "Tạo Cloud9 instance"
weight = 1
chapter = false
pre = "<b>1. </b>"
+++

#### Tạo Cloud9 instance.

Trong bước này, chúng ta sẽ truy cập vào giao diện quản trị dịch vụ Cloud9 và tiến hành tạo 1 Cloud9 instance.

1. Đăng nhập vào AWS Management Console.

![Cloud9](/images/cloud9/001.png?width=90pc)

2. Click vào khung tìm kiếm , gõ **Cloud9**.
  + Click vào biểu tượng **Cloud9** để đi đến giao diện quản trị Cloud9.

![Cloud9](/images/cloud9/002.png?width=90pc)

3. Tại giao diện quản trị Cloud9.
  + Click **Create environment**.

![Cloud9](/images/cloud9/003.png?width=90pc)

4. Tại trang **Name environment**.
  + Đặt tên Cloud9 instance của bạn.
  + VD: **cloud9instance**.
  + Click **Next step**.


![Cloud9](/images/cloud9/004.png?width=90pc)

5. Tại trang **Configure settings**.
  + Mục **Environment settings**.
    + Environment type : Chọn **Create a new EC2 instance for environment (direct access)**.
    + Instance type : Chọn **t2.micro**.
    + Platform : Chọn **Amazon Linux2**.

    
![Cloud9](/images/cloud9/005.png?width=90pc)

6. Kéo màn hình xuống.
  + Cost-saving setting : chọn **After 30 minutes**. Cho phép tự động stop Cloud9 instance để tiết kiệm chi phí.
  + Click **Next step**.


![Cloud9](/images/cloud9/006.png?width=90pc)

7. Tại trang **Review**.
  + Kiểm tra cấu hình đã chọn.
  + Kéo xuống cuối trang, click **Create environment**.

8. Sẽ mất vài phút để Cloud9 Instance được khởi tạo.

![Cloud9](/images/cloud9/007.png?width=90pc)

9. Click biểu tượng close để đóng tab **Welcome** và **AWS Toolkit** nếu không cần sử dụng.

![Cloud9](/images/cloud9/008.png?width=90pc)

Chúc mừng bạn đã hoàn thành việc tạo Cloud9 instance, trong các bước tiếp theo chúng ta sẽ thử thực hiện 1 số thao tác cơ bản trên Cloud9.