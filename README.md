🌐 Job Finding Website (Recruitment Platform)

Tác giả: A Phiên (Software Engineer)

🚀 Tổng quan (Overview)

Job Finding Website là nền tảng tuyển dụng trực tuyến được xây dựng để kết nối Nhà tuyển dụng và Ứng viên trong lĩnh vực CNTT. Hệ thống cung cấp giải pháp toàn diện cho việc đăng tin, quản lý hồ sơ và tìm kiếm việc làm thông qua giao diện web thân thiện và hiệu quả.

Dự án được phát triển dựa trên mô hình MVC (Model-View-Controller) chuẩn mực của Laravel Framework, đảm bảo tính bảo mật và khả năng mở rộng.

🛠 Tech Stack

Hệ thống sử dụng các công nghệ Web phổ biến và mạnh mẽ:

Category

Technology

Mô tả

Backend Framework

Laravel (PHP)

Framework PHP mạnh mẽ, xử lý logic, routing và bảo mật (CSRF protection).

Database

MySQL

Hệ quản trị cơ sở dữ liệu quan hệ, lưu trữ thông tin người dùng và bài đăng.

Frontend

Blade Template, Bootstrap

Xây dựng giao diện Responsive, tương thích nhiều thiết bị.

Server Environment

XAMPP / Docker

Môi trường chạy Localhost (Apache/Nginx, MySQL).

✨ Tính năng chính (Key Features)

Hệ thống phân quyền chi tiết cho 3 nhóm đối tượng:

🧑‍💻 Dành cho Ứng viên (Candidate/User)

Advanced Search: Tìm kiếm việc làm theo từ khóa, ngôn ngữ (PHP, Java...), địa điểm (Đà Nẵng, Hà Nội...), và loại hình công việc.

Job Application: Nộp đơn ứng tuyển trực tuyến và quản lý lịch sử ứng tuyển.

Profile Management: Cập nhật thông tin cá nhân, kỹ năng, và tải lên CV.

Bookmark Jobs: Lưu lại các công việc yêu thích ("Save Job").

🏢 Dành cho Nhà tuyển dụng (Company)

Recruitment Management: Đăng tin tuyển dụng mới với đầy đủ thông tin (Mức lương, Yêu cầu, Mô tả).

Candidate Tracking: Xem danh sách ứng viên đã nộp đơn vào bài đăng.

Company Profile: Quản lý thông tin thương hiệu, website và địa chỉ công ty.

🛡️ Dành cho Quản trị viên (Admin)

User Control: Quản lý (Xem/Sửa/Xóa) tài khoản người dùng và công ty.

Job Moderation: Kiểm duyệt bài đăng tuyển dụng, xóa hoặc khóa các bài đăng vi phạm ("Block/Active").

System Management: Quản lý danh mục nghề nghiệp (Category) và cấu hình hệ thống.

📸 Giao diện Website (Screenshots)

Trang chủ
<img width="565" height="291" alt="image" src="https://github.com/user-attachments/assets/2682b922-45cb-46d6-a738-7eac8ad8eafc" />
<img width="883" height="595" alt="image" src="https://github.com/user-attachments/assets/aa18df12-326f-4e97-946c-c76a21167786" />
<img width="883" height="592" alt="image" src="https://github.com/user-attachments/assets/d0a1aeb2-a285-4454-99e3-23c711cdec8b" />


Chi tiết công việc
<img width="744" height="511" alt="image" src="https://github.com/user-attachments/assets/d5b620c0-5f90-45df-9aa0-bdc6897408ea" />
<img width="744" height="600" alt="image" src="https://github.com/user-attachments/assets/50ca0d26-1c50-46c8-80b0-24feadaffeef" />


Giao diện tìm kiếm việc làm
<img width="855" height="566" alt="image" src="https://github.com/user-attachments/assets/3d1bce9a-c015-4611-b266-9b786510c189" />

Thông tin chi tiết và Ứng tuyển
<img width="855" height="444" alt="image" src="https://github.com/user-attachments/assets/c834d2b0-1c5e-44ae-b97a-1476786fdf13" />
<img width="855" height="456" alt="image" src="https://github.com/user-attachments/assets/82e8e54c-3492-4b39-a7db-0febb01975ae" />

Dashboard Công ty
<img width="855" height="335" alt="image" src="https://github.com/user-attachments/assets/8484c39a-ead7-48dd-8327-42433fa8a789" />
<img width="858" height="480" alt="image" src="https://github.com/user-attachments/assets/ba2d7f30-1dfa-4345-bffe-3ad523bf4e80" />
<img width="855" height="763" alt="image" src="https://github.com/user-attachments/assets/0e61c990-c991-4da2-9a4c-790d7e09b3b4" />
<img width="855" height="522" alt="image" src="https://github.com/user-attachments/assets/a6969ec7-781c-4d45-a442-cfbefa7997ba" />

Quản lý Admin

<img width="855" height="350" alt="image" src="https://github.com/user-attachments/assets/0439bb49-d051-4551-b7b6-06f75b065a9a" />

<img width="855" height="434" alt="image" src="https://github.com/user-attachments/assets/510c963d-da4d-4fbb-835e-d58bdb9b73af" />
<img width="855" height="528" alt="image" src="https://github.com/user-attachments/assets/bfba0d20-ae93-41e2-b093-e82856068a91" />

Trang quản trị hệ thống

⚙️ Cài đặt & Chạy dự án (Installation)

Yêu cầu: Đã cài đặt PHP, Composer và MySQL (qua XAMPP hoặc Docker).

Clone Repository:

git clone https://github.com/aphiendaidai/JobQuest.git
cd job-finding-web


Cài đặt Dependencies:

composer install
npm install && npm run dev


Cấu hình môi trường (.env):

Copy file .env.example thành .env:

cp .env.example .env


Mở file .env và cấu hình thông tin Database (DB_DATABASE, DB_USERNAME, DB_PASSWORD).

Generate Key & Migrate:

php artisan key:generate
php artisan migrate --seed


(Thêm --seed nếu có dữ liệu mẫu)

Chạy Server:

php artisan serve


Truy cập tại: http://localhost:8000

🛣️ Roadmap & Hướng phát triển

Dự án hiện tại đã đáp ứng các chức năng cơ bản. Kế hoạch nâng cấp trong tương lai:

[ ] Đa ngôn ngữ: Bổ sung hỗ trợ tiếng Anh để mở rộng thị trường.

[ ] Advanced Analytics: Thêm biểu đồ thống kê chuyên sâu cho Nhà tuyển dụng và Admin.

[ ] Notification System: Thông báo email tự động khi có ứng viên mới hoặc trạng thái hồ sơ thay đổi.

[ ] Security: Tăng cường bảo mật phân quyền và mã hóa dữ liệu người dùng.

📬 Liên hệ (Contact)

Nếu bạn quan tâm đến dự án, vui lòng liên hệ:

A Phiên - Software Engineer

Email: aphien629@gmail.com

Phone: 0986712687

© 2024 A Phiên. Built with ❤️ and Laravel.
