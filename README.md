# 📸 QR Photo Game - Unity

## 🎮 Giới thiệu

**QR Photo Game** là một trò chơi tương tác cho phép người chơi chụp ảnh trong game và quét mã QR để tải về hình ảnh/kết quả.  
Dự án được xây dựng nhằm kết hợp trải nghiệm game với công nghệ QR Code, giúp người chơi dễ dàng lưu lại khoảnh khắc sau khi chơi.

## ✨ Tính năng chính

- 🎮 Game được phát triển bằng **Unity**
- 📷 Chụp ảnh trong quá trình chơi
- 🔳 Tạo và quét mã QR
- 📱 Người chơi có thể quét QR để tải ảnh/kết quả
- 🌐 Backend quản lý dữ liệu bằng **Java Spring Boot** link:https://github.com/haolenhat/BE-SpringBoot-ChupHinh-Omo
- 💾 Lưu trữ thông tin người chơi và dữ liệu game

---

# 🖼️ Demo Game

<p align="center">
  <img src="./images/1.png" width="700"/>
</p>

> Hình ảnh giao diện trong game

---

# 🛠️ Công nghệ sử dụng

## 🎮 Frontend / Game
- Unity Engine
- C#
- Unity UI System
- Animation System
- Camera System
- QR Code Integration

## 🌐 Backend
- Java Spring Boot
- REST API
- MySQL Database

## 🔧 Tools
- GitHub
- Visual Studio Code
- IntelliJ IDEA
- Unity Hub

---

# 🔄 Luồng hoạt động

```
Người chơi
     |
     v
Unity Game
     |
     | Chụp ảnh + tạo dữ liệu
     |
     v
Java Spring Boot API
     |
     v
Database
     |
     v
Tạo QR Code
     |
     v
Người chơi quét QR và tải ảnh
```

---

# 📂 Cấu trúc dự án

```
QR-Photo-Game
│
├── UnityProject
│   ├── Assets
│   ├── Scenes
│   └── Scripts
│
├── Backend
│   ├── SpringBoot
│   ├── Controller
│   ├── Service
│   └── Repository
│
└── README.md
```

---

# 🚀 Cách chạy project


# 📸 Một số hình ảnh trong game

<p align="center">
  <img src="./images/1.png" width="300"/>
  <img src="./images/screenshot2.png" width="300"/>
</p>

---

# 👨‍💻 Developer
**Hào Lê Nhật**
Project được phát triển với mục đích học tập và nghiên cứu về kết hợp Game Development + Backend System.
