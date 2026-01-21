<h2 align="center"> <a href="https://dainam.edu.vn/vi/khoa-cong-nghe-thong-tin"> 🎓 Khoa Công nghệ Thông tin (Đại học Đại Nam) </a> </h2> <h2 align="center"> Hệ thống Quản lý Văn bản - Khách hàng  </h2> <div align="center"> <p align="center"> <img src="docs/logo/aiotlab_logo.png" alt="AIoTLab Logo" width="170"/> <img src="docs/logo/fitdnu_logo.png" alt="FIT DNU Logo" width="180"/> <img src="docs/logo/dnu_logo.png" alt="DaiNam University Logo" width="200"/> </p>

</div>

📖 1. Giới thiệu
Hệ thống được xây dựng trên nền tảng Odoo ERP nhằm tối ưu hóa quy trình quản lý văn bản, thông tin khách hàng và điều phối nhân sự trong tổ chức. Thay vì sử dụng các phương pháp lưu trữ rời rạc, hệ thống cung cấp một giải pháp tập trung, tích hợp trí tuệ nhân tạo (AI) để hỗ trợ truy vấn và xử lý dữ liệu thông minh.

Các chức năng chính của hệ thống:

Dashboard tổng quan: Theo dõi số lượng văn bản, trạng thái hồ sơ và biểu đồ nhân sự theo thời gian thực.

Quản lý Văn bản: Phân loại tài liệu (Hợp đồng, Báo cáo), theo dõi luồng công văn đến/đi và trạng thái lưu trữ.

Quản lý Khách hàng (CRM): Lưu trữ thông tin đối tác, lịch sử giao dịch và các văn bản ký kết liên quan.

Quản lý Nhân sự: Điều phối nhân viên phụ trách từng đầu mục công việc và theo dõi tiến độ xử lý văn bản.

Trợ lý ảo AI: Tích hợp Chatbot Gemini hỗ trợ tìm kiếm văn bản nhanh và giải đáp nghiệp vụ.

🔧 2. Các công nghệ được sử dụng
<div align="center">
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![GitLab](https://img.shields.io/badge/gitlab-%23181717.svg?style=for-the-badge&logo=gitlab&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)

![Python](https://img.shields.io/badge/python-v3.8+-blue.svg)
[![security: bandit](https://img.shields.io/badge/security-bandit-yellow.svg)](https://github.com/PyCQA/bandit)
</div>

🚀 3. Hình ảnh các chức năng
Giao diện quản lý nhân sự
<img width="1902" height="931" alt="image" src="https://github.com/MinnKaa/TTDN-16-02-N7/tree/main/setup/anh1" />

Giao diện quản lý khách hàng
<img width="1902" height="931" alt="image" src="https://github.com/MinnKaa/TTDN-16-02-N7/tree/main/setup/anh2" />

Giao diện quản lý văn bản
<img width="1902" height="931" alt="image" src="https://github.com/MinnKaa/TTDN-16-02-N7/tree/main/setup/anh3" />

Giao diện chi tiết văn bản
<img width="1902" height="931" alt="image" src="https://github.com/MinnKaa/TTDN-16-02-N7/tree/main/setup/anh4" />

Giao diện thêm khách hàng
<img width="1902" height="931" alt="image" src="https://github.com/MinnKaa/TTDN-16-02-N7/tree/main/setup/anh5" />

Giao diện AI hỗ  trợ tìm kiếm
<img width="1902" height="931" alt="image" src="https://github.com/MinnKaa/TTDN-16-02-N7/tree/main/setup/anh6" />
⚙️ 4. Cài đặt
4.1. Cài đặt môi trường Docker
Cài đặt Docker Desktop.

4.2. Triển khai Module
Clone project vào thư mục trong Odoo:

cd ~/odoo-fitdnu/
git clone https://github.com/MinnKaa/TTDN-16-02-N7

4.3. Cấu hình Database & API
Khởi động hệ thống: docker restart odoo_odoo-base.

Truy cập vào Odoo (thường là localhost:8069).

Vào chế độ Developer Mode và nhấn Upgrade.

Cấu hình Gemini API Key trong phần cài đặt của trợ lý ảo.

DNU AIoTLab - Kết nối tri thức, Kiến tạo tương lai.
