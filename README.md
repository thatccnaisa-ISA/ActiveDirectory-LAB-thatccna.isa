# Active Directory LAB – thatccna.isa

## 🎯 Mục tiêu
Triển khai hệ thống Active Directory cho doanh nghiệp mô phỏng 50–100 user.

## 🧱 Mô hình hệ thống
- Domain Controller: Windows Server 2022
- Client: Windows 10
- Domain: thatccna.isa
- IP DC: 192.168.189.10

## ⚙️ Các bước triển khai
1. Cấu hình IP tĩnh cho DC
2. Cài Active Directory Domain Services
3. Promote Domain Controller (thatccna.isa)
4. Cài đặt DNS Server
5. Tạo OU, User, Group
6. Cấu hình IP tĩnh cho client
7. Join domain cho client
8. Login user domain vào client

## 1️⃣ Cấu hình IP tĩnh cho Domain Controller

![IP Config](images/DC-Ipconfig.png)

## 2️⃣ Cài đặt Active Directory Domain Services (AD DS)

![Install AD](images/DC-install.png)

## 3️⃣ Promote Domain Controller

### Cấu hình triển khai Domain
![Deployment Configuration](images/Deployment%20configuration.png)

### Domain sau khi promote
![Domain Created](images/DOMAIN.png)

## 4️⃣ Cài đặt và kiểm tra DNS

![DNS](images/DNS.png)

## 5️⃣ Tạo OU – User – Group

### Cấu trúc OU
![OU Structure](images/ou-structure.png)

### OU theo phòng ban
![OU NHANSU](images/ou-NHANSU.png)

![OU HR](images/ou-HR.png)

![OU Sales](images/ou-SALE.png)

## 6️⃣ Cấu hình IP tĩnh cho Client

![Client IP Config](images/CLIENT-ipv4.png)

## 7️⃣ Client join domain thatccna.isa

![Join Domain](images/join-domain.png)

## 8️⃣ Đăng nhập user domain trên Client

![Login Domain User](images/login%20user%20domain.png)

## ✅ Kết quả

Client đăng nhập domain **thatccna.isa** thành công.
