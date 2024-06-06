Cách triển khai trang web lên AWS:
    - Tạo 1 EC2 rồi connect tới EC2 thông qua key pair.
    - Kết nối tới root thông qua câu lệnh "sudo su -".
    - Sau đó tải git về máy chủ để clone code từ github bằng câu lệnh "sudo yum -y install git"
    - Ta tiếp tục tải httpd để có thể chạy file html.
    - Tiếp đến clone code từ  github về và lưu vào thư mục /var/www/html/
    -  Lúc này ta chỉ việc enable httpd và start là có thể truy cập trang Web từ public ip của EC2.
    
