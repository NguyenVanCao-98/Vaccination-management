# 💉 Vaccination Management System

> Ứng dụng quản lý tiêm chủng vắc xin cho Trung tâm Y tế Dự Phòng  
> Dự án giúp các trung tâm y tế quản lý hiệu quả quy trình tiêm chủng, nhân sự, kho vắc xin, tài chính và phản hồi người dân.


![Java](https://img.shields.io/badge/Java-17-blue?logo=openjdk)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.5.3-brightgreen?logo=springboot)
![MySQL](https://img.shields.io/badge/MySQL-8.x-orange?logo=mysql)
![Docker](https://img.shields.io/badge/Docker-Enabled-blue?logo=docker)
![License](https://img.shields.io/badge/License-Academic-lightgrey)

---

## 📖 Mục lục

1. [Giới thiệu](#1-giới-thiệu)  
2. [Tính năng chính](#2-tính-năng-chính)  
3. [Công nghệ sử dụng](#3-công-nghệ-sử-dụng)  
4. [Cấu trúc dự án](#4-cấu-trúc-dự-án)  
5. [Cấu hình hệ thống](#5-cấu-hình-hệ-thống)  
6. [Hướng dẫn chạy dự án](#6-hướng-dẫn-chạy-dự-án)  
   - [Chạy bằng Maven](#chạy-bằng-maven)  
   - [Chạy bằng Docker](#chạy-bằng-docker)  
7. [Tài khoản mẫu](#7-tài-khoản-mẫu)  
8. [Nhóm phát triển](#8-nhóm-phát-triển)  
9. [Giấy phép](#9-giấy-phép)  

---

## 1. 🎯 Giới thiệu

Hiện nay, công tác tiêm chủng tại các trung tâm y tế dự phòng là một phần quan trọng trong việc bảo vệ sức khỏe cộng đồng.  
Hệ thống **Vaccination Management System** được xây dựng nhằm:
- Tin học hóa quy trình quản lý tiêm chủng  
- Hạn chế sai sót thủ công  
- Cải thiện trải nghiệm người dân và nhân viên y tế  
- Tăng khả năng thống kê và phân tích dữ liệu phục vụ quản lý  

## 2. ⚙️ Tính năng chính

### 👨‍💼 Quản trị viên (Admin)
- Quản lý tài khoản, phân quyền truy cập  
- Thiết lập lịch tiêm và bác sĩ phụ trách  
- Theo dõi báo cáo tổng hợp từ các bộ phận  

### 💉 Nhân viên y tế
- Quản lý hồ sơ bệnh nhân  
- Cập nhật thông tin tiêm và phản ứng sau tiêm  
- Kê đơn thuốc và tạo phiếu tiêm  

### 🧰 Quản lý kho
- Nhập / xuất lô vắc xin  
- Theo dõi hạn sử dụng, số lượng, trạng thái  
- Quản lý thông tin nhà cung cấp  

### 💰 Nhân viên tài chính
- Quản lý giá vắc xin và doanh thu  
- Xuất hóa đơn, thống kê tài chính  
- Theo dõi giao dịch  

### 🧑‍💻 Nhân viên hỗ trợ
- Gửi email nhắc lịch tiêm  
- Giải đáp thắc mắc và phản hồi người dùng  

### 👨‍👩‍👧 Người dân (User)
- Đăng ký tiêm trực tuyến  
- Xem lịch tiêm, lịch sử tiêm  
- Gửi phản hồi và đánh giá dịch vụ  


3. 🧩 Công nghệ sử dụng

| Thành phần | Phiên bản | Mô tả |
|-------------|-----------|-------|
| Java | 17 | Ngôn ngữ lập trình chính |
| Spring Boot | 3.5.3 | Framework phát triển ứng dụng |
| Spring Security | - | Xác thực và phân quyền |
| Spring Data JPA | - | ORM làm việc với MySQL |
| Thymeleaf + Layout Dialect | - | Giao diện HTML động |
| Lombok | 1.18.36 | Tự động sinh getter/setter |
| MapStruct | 1.5.5.Final | Mapping DTO – Entity |
| ModelMapper | 3.1.1 | Chuyển đổi dữ liệu linh hoạt |
| Spring Mail | - | Gửi email tự động |
| MySQL | 8.x | Cơ sở dữ liệu |
| Docker | 27.x | Triển khai container |
| DevTools | - | Hỗ trợ reload nhanh khi phát triển |

---
