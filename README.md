# 🔐 Secure File Transfer System

🚀 A **production-ready, end-to-end encrypted file transfer platform** that ensures complete privacy using **RSA-4096 + AES-256-GCM hybrid encryption**.
Built with a modern full-stack architecture and zero-knowledge security principles.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Node](https://img.shields.io/badge/node-%3E%3D18.0.0-brightgreen.svg)
![React](https://img.shields.io/badge/react-18.2.0-blue.svg)

---

## 🌟 Why This Project?

Most file-sharing platforms can access your data.
👉 This system ensures:

* 🔐 **Only sender & receiver can read files**
* 🚫 **Server has ZERO access to data**
* ⚡ **Secure + scalable + real-time**

---

## ✨ Key Features

### 🔒 Security First

* End-to-End Encryption (Client-side)
* Hybrid Encryption (RSA + AES)
* Zero-Knowledge Architecture
* Private keys never stored anywhere
* Secure key generation via Web Crypto API

### 📁 File Transfer

* Encrypted uploads & downloads
* Auto-expiry (7 days)
* Real-time notifications (WebSockets)
* Supports all file types
* Transfer history tracking

### 👤 User System

* JWT Authentication
* User search & sharing
* Dashboard with stats
* Key management system

---

## 🧠 How It Works (Simple Flow)

1. File is encrypted in your browser using AES
2. AES key is encrypted using receiver’s RSA public key
3. Only encrypted data is sent to server
4. Receiver decrypts using private key

👉 Server **never sees actual data**

---

## 🏗️ Architecture Overview

* **Frontend** → React + Web Crypto API
* **Backend** → Node.js + Express
* **Database** → MongoDB
* **Realtime** → Socket.io

---

## 🛠️ Tech Stack

### Frontend

* React 18
* Tailwind CSS
* Axios
* Socket.io Client
* IndexedDB

### Backend

* Node.js + Express
* MongoDB + Mongoose
* JWT Authentication
* Multer (File Uploads)
* Security Middleware (Helmet, Rate-limit)

---

## ⚙️ Setup & Installation

```bash
# Clone your repo (UPDATED TO YOUR GITHUB)
git clone https://github.com/SomanaboinaNandish/secure-file-transfering.git
cd secure-file-transfering
```

### Install Dependencies

```bash
cd server && npm install
cd ../client && npm install
```

---

## ▶️ Run Project

### Start Backend

```bash
cd server
npm run dev
```

### Start Frontend

```bash
cd client
npm run dev
```

---

## 🔐 Security Highlights

* AES-256-GCM → File encryption
* RSA-4096 → Key encryption
* No plaintext ever leaves client
* Private keys handled securely

---

## 📸 Future Improvements

* 🔐 Two-Factor Authentication (2FA)
* 📱 Mobile App
* 📦 File Compression
* 👥 Multi-user sharing
* 🌙 Dark Mode

---

## 🧪 Real-World Challenges Faced

* Handling large encrypted file uploads
* Secure key exchange without leaks
* Preventing memory exposure of keys
* Web Crypto API limitations
* Managing real-time updates securely

---

## 🎯 Why This Project Matters (For Recruiters)

✔ Demonstrates **full-stack development**
✔ Shows **real-world security implementation**
✔ Covers **system design + encryption concepts**
✔ Uses **modern scalable architecture**

---

## 👨‍💻 Author

**Nandish Somanaboina**

* Aspiring SDE | Cybersecurity Enthusiast
* Passionate about building secure systems

---

## 📄 License

MIT License © 2025 Nandish
