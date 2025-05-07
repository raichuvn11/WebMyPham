# 💄 WebMyPham - Trang Web Bán Mỹ Phẩm

Dự án **WebMyPham** là một hệ thống quản lý bán hàng trực tuyến cho cửa hàng mỹ phẩm, được phát triển với mục tiêu cung cấp giao diện thân thiện, chức năng đặt hàng linh hoạt và khả năng mở rộng trong tương lai.

## 🛠️ Công nghệ sử dụng

- 💻 **Backend**: Java Spring Boot
- 🌐 **Frontend**: HTML, CSS, JavaScript
- 🔐 **Bảo mật**: Spring Security
- 🗄️ **Cơ sở dữ liệu**: SQL Server
- 🧩 **Quản lý nhiệm vụ**: Jira
- 🗃️ **Quản lý mã nguồn**: Git & GitHub

## 📌 Tính năng chính

- 🧍 Đăng ký / Đăng nhập người dùng
- 🔐 Xác thực và phân quyền với Spring Security
- 🛍️ Quản lý sản phẩm mỹ phẩm
- 🧾 Đặt hàng và theo dõi đơn hàng
- 💬 Liên hệ và phản hồi khách hàng
- 📊 Thống kê doanh thu (dự kiến)
- 👨‍💼 Giao diện quản trị (Admin Panel)

## 📁 Cấu trúc thư mục

```bash
WebMyPham/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/...
│   │   ├── resources/
│   │   │   ├── static/        # HTML, CSS, JS
│   │   │   ├── templates/     # Thymeleaf templates
│   │   │   └── application.properties
├── .gitignore
├── README.md
└── pom.xml
🔧 Cách cài đặt
Clone repository

bash
Sao chép
Chỉnh sửa
git clone https://github.com/raichuvn11/WebMyPham.git
cd WebMyPham
Cấu hình database trong application.properties

properties
Sao chép
Chỉnh sửa
spring.datasource.url=jdbc:sqlserver://localhost:1433;databaseName=WebMyPham
spring.datasource.username=your_username
spring.datasource.password=your_password
Chạy dự án

Sử dụng IDE như IntelliJ IDEA hoặc Eclipse để chạy class WebMyPhamApplication.java

Truy cập: http://localhost:8080

🔐 Tài khoản mẫu
text
Sao chép
Chỉnh sửa
Admin:
  Username: admin
  Password: 123

Khách hàng:
  Username: abc
  Password: 123

Shipper:
  Username: shipper
  Password: 123

Vendor:
  Username: vendor
  Password: 123

📋 Quản lý & phát triển
Công việc được quản lý bằng Jira

Mã nguồn được quản lý trên GitHub với các nhánh và commit rõ ràng

🤝 Đóng góp
Mọi đóng góp đều được hoan nghênh! Bạn có thể tạo issue hoặc gửi pull request để cải thiện dự án.

📄 Giấy phép
Dự án này hiện chưa công bố giấy phép cụ thể. Nếu cần sử dụng hoặc phân phối, vui lòng liên hệ trực tiếp với chủ sở hữu repo.

👩‍💻 Dự án thuộc về sinh viên công nghệ thông tin, được xây dựng với đam mê và sự học hỏi.
