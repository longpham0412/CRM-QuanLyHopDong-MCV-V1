# CRM - Module Quản Lý Hợp Đồng
Đây là module Quản lý Hợp đồng (Hợp Đồng Service) nằm trong hệ thống CRM. Dự án cung cấp các API RESTful cơ bản để thực hiện các nghiệp vụ CRUD (Thêm, Xem, Sửa, Xóa) cho đối tượng Hợp Đồng.

## Các công nghệ sử dụng

*   **Ngôn ngữ:** Java
*   **Framework chính:** Spring Boot
*   **Cơ sở dữ liệu:** MySQL
*   **ORM:** Spring Data JPA (Hibernate)
*   **Thư viện hỗ trợ:** Lombok (giúp tối ưu code, tự tạo getter/setter/constructor)

##  Yêu cầu hệ thống

*   **JDK:** Phiên bản 17 trở lên.
*   **Database:** MySQL Server đang chạy ở cổng mặc định `3306`.
*   **Công cụ build:** Maven.
*   **IDE khuyến nghị:** IntelliJ IDEA, Eclipse, hoặc Visual Studio Code.

##  Hướng dẫn cài đặt

**Bước 1: Thiết lập Database**
Mở công cụ quản lý MySQL (như MySQL Workbench, phpMyAdmin, hoặc DBeaver) và chạy lệnh SQL sau để tạo database:

CREATE DATABASE crmonline_pro;

Bước 2: Clone dự án về máy Mở terminal và chạy lệnh:
Bash
git clone [https://github.com/longpham0412/CRM-Module-HopDong.git](https://github.com/longpham0412/CRM-Module-HopDong.git)
Bước 3: Cấu hình kết nối Điều hướng đến file src/main/resources/application.yaml để kiểm tra cấu hình kết nối database. Mặc định dự án đang sử dụng: 
•	Username: root
•	Password: (để trống)
Bước 4: Chạy ứng dụng Mở project bằng IDE và chạy file DemoApplication.java. Ứng dụng sẽ khởi chạy trên port 8080 với context-path là /crm-ver1. 

http://localhost:8080/crm-ver1/api/hopdong


