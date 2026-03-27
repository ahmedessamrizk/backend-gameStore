# 🎮 GameStore Server

## 📌 Overview
GameStore is a full-featured backend server built with **Node.js**, **Express.js**, and **MongoDB**.  
It provides a scalable system for managing games, users, and roles with secure authentication and advanced services.

---

## 🌐 Live Demo
🔗 https://gamestore777.netlify.app/

---

## 💻 Frontend Repository
🔗 https://github.com/PeterSamehShafik/GameStore

---

## 🚀 Features

### 👤 User
- Browse games and view details  
- Add/remove items from cart & wishlist  
- Rate games and add comments 
- Follow other users  
- Receive notifications and activity updates  

### 🛠️ Admin
- Add and remove games  
- Manage genres ( categories )

### 👑 Super Admin
- Block / unblock users and admins  
- Delete users and comments  
- Assign or remove roles  

> ⚠️ Each role inherits permissions from lower roles.

---

## 🔐 Security & Services

### 🔒 Security
- Authentication & Authorization  
- JWT tokens with **Bearer key** and expiry  
- Password hashing using **bcrypt**  
- Email confirmation before login  
- Request validation  
- Role-based access control  

### ⚙️ Services
- Social login support  
- Upload **images & videos** for:
  - Games  
  - Genres  
  - User profile pictures  
  using **Multer + Cloudinary**  
- Global error handling
- Pagination for efficient data handling  

---

## 🗂️ ERD

![ERD](https://drive.google.com/uc?export=view&id=1zPJkHury204wK_52sqaMMvcGhQvwkkO3)

---

## 🛠️ Technologies Used

- **Node.js** → Runtime environment for building scalable server-side applications  
- **Express.js** → Web framework for handling routing and middleware  
- **MongoDB** → NoSQL database for storing users, games, and related data  
- **Multer** → Middleware for handling file uploads (images & videos)  
- **Cloudinary** → Cloud storage for managing uploaded media files
- **OAuth / Social Login** → Authentication using third-party providers (e.g., Google)  
- **JWT (JSON Web Token)** → Secure authentication using tokens with expiration  
- **bcrypt** → Password hashing for enhanced security  
- **Nodemailer** → Sending email verification and notifications  

---

## 🤝 Contributing

Pull requests are welcome.  
For major changes, please open an issue first to discuss what you would like to change.

