# Cách cài đặt và sử dụng
## Cài đặt
### CD vào thư mục MSSQL là gõ các lệnh sau:
1. docker compose ps: Danh sách các images
2. docker compose up -d: Khởi tạo image có tên sqlserver
3. docker compose down: Xóa image
### Sử dụng
1. docker exec -it sqlserver bash: Vào bash của sql server
2. opt/mssql-tools/bin/sqlcmd -S localhost -U SA -P Password@123: Đăng nhập vào sql server
### Cách sử dụng MSSQL Management Tool để kết nối
1. Server name: localhost,1533 hoặc 127.0.0.1,1533
2. Username: sa
3. Password: Password@123
## Video hướng dẫn
[Link](https://www.youtube.com/watch?v=RAE-VcZ3u2A&ab_channel=LogRocket)