<h2 align="center">
    <a href="https://dainam.edu.vn/vi/khoa-cong-nghe-thong-tin">
        🎓 Khoa Công nghệ Thông tin (Đại học Đại Nam)
    </a>
</h2>

<h2 align="center">
    HỆ THỐNG QUẢN LÝ VĂN BẢN – KHÁCH HÀNG 
</h2>

<div align="center">
    <p align="center">
        <img src="setup/aiotlab_logo.png" alt="AIoTLab Logo" width="170"/>
        <img src="setup/fitdnu_logo.png" alt="FIT DNU Logo" width="180"/>
        <img src="setup/dnu_logo.png" alt="DaiNam University Logo" width="200"/>
    </p>

[![AIoTLab](https://img.shields.io/badge/AIoTLab-green?style=for-the-badge)](https://www.facebook.com/DNUAIoTLab)
[![Faculty of Information Technology](https://img.shields.io/badge/Faculty%20of%20Information%20Technology-blue?style=for-the-badge)](https://dainam.edu.vn/vi/khoa-cong-nghe-thong-tin)
[![DaiNam University](https://img.shields.io/badge/DaiNam%20University-orange?style=for-the-badge)](https://dainam.edu.vn)

</div>

---

## 📖 1. Giới thiệu

Hệ thống Quản lý Văn bản – Khách hàng được xây dựng trên nền tảng Odoo ERP, nhằm tối ưu hóa công tác quản lý văn bản, thông tin khách hàng và điều phối nhân sự trong tổ chức.

Thay vì quản lý rời rạc bằng giấy tờ hoặc các file độc lập, hệ thống cung cấp một giải pháp tập trung, hỗ trợ:

Các chức năng chính của hệ thống:

 - Quản lý Văn bản: Phân loại tài liệu (Hợp đồng, Báo cáo), theo dõi luồng công văn đến/đi và trạng thái lưu trữ.

 - Quản lý Khách hàng (CRM): Lưu trữ thông tin đối tác, lịch sử giao dịch và các văn bản ký kết liên quan.

 - Quản lý Nhân sự: Điều phối nhân viên phụ trách từng đầu mục công việc và theo dõi tiến độ xử lý văn bản.

 - Trợ lý ảo AI: Tích hợp Chatbot Gemini hỗ trợ tìm kiếm văn bản nhanh và giải đáp nghiệp vụ.

---

## 🔧 2. Các công nghệ được sử dụng

<div align="center">

### Hệ điều hành
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)



### Công nghệ chính
![Odoo](https://img.shields.io/badge/Odoo-ERP-purple?style=for-the-badge&logo=odoo)
![Python](https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![XML](https://img.shields.io/badge/XML-FF6600?style=for-the-badge)



### Cơ sở dữ liệu
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

</div>

---

## 🧩 3. Các chức năng chính

### Giao diện quản lý nhân sự
<p align="center">
  <img src="setup/anh1.png">
</p>

### Giao diện quản lý khách hàng
<p align="center">
  <img src="setup/anh2.png">
</p>

### Giao diện quản lý văn bản
<p align="center">
  <img src="setup/anh3.png">
</p>

### Giao diện chi tiết văn bản
<p align="center">
  <img src="setup/anh4.png">
</p>

### Giao diện thêm khách hàng
<p align="center">
  <img src="setup/anh5.png">
</p>

### Giao diện AI hỗ trợ tìm kiếm
<p align="center">
  <img src="setup/anh6.png">
</p>

### Biểu đồ xếp hạng nhân viên
<p align="center">
  <img src="setup/anh8.png">
  <br>
  <img src="setup/anh9.png">
</p>


---

## 📰 4. Poster
<p align="center">
  <img src="setup/anh7.png" alt="System Architecture" width="800"/>
</p>

---

## ⚙️ 5. Cài đặt

5.1. Cài đặt môi trường Docker
- Cài đặt Docker Desktop
- Đảm bảo Docker đã chạy trước khi triển khai hệ thống

---

5.2. Triển khai Module

Clone project vào thư mục Odoo:

```bash
cd ~/odoo-fitdnu/
git clone https://github.com/MinnKaa/TTDN-16-02-N7.git
```

---

5.3. Cấu hình Database & API

Khởi động hệ thống: docker restart odoo_odoo-base.

Truy cập vào Odoo (thường là localhost:8069).

Vào chế độ Developer Mode và nhấn Upgrade.

Cấu hình Gemini API Key trong phần cài đặt của trợ lý ảo.

---

## 6. Thành viên nhóm

1. Vũ Đức Minh
2. Phùng Xuân Đức
3. Đỗ Quốc Việt

---

## 7. Nguồn tham khảo
[1] yukiharadev, **TTDN-15-05-N2**, GitHub.  
https://github.com/yukiharadev/TTDN-15-05-N2 

---

DNU AIoTLab - Kết nối tri thức, Kiến tạo tương lai.
