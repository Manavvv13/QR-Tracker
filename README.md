# 🔐 QR Tracker — Smart QR Code Generation & Scan Analytics

QR Tracker is a **full-stack QR management system** built using **React + Flask**.  
It allows users to **generate multiple QR codes**, track scan counts in **real-time**, and manage each QR individually.

---

## 🚀 Features

### 👨‍💼 Authentication
- Secure user registration & login
- Session-based authentication (cookies)

### 📦 QR Code Management
- Generate **multiple QR codes at once**
- Each QR contains a **unique redirect ID**
- Download QR images
- Delete QR codes

### 🪪 Personalization
- Rename your QR codes (saved to DB)
- Persistent names even after reload

### 🔄 Real-Time Scan Updates
- Live scan count updates using **WebSockets**
- No refresh needed to see scan changes

### 🎨 Modern UI + Dark Mode
- Interactive micro animations
- Dark & light theme toggle
- Clean dashboard cards & visual stats

---

## 🛠 Tech Stack

| Category | Tech |
|----------|------|
| Frontend | React (Vite), TypeScript, TailwindCSS, shadcn/ui, Socket.IO |
| Backend | Flask, Socket.IO, SQLAlchemy |
| Database | PostgreSQL / SQLite (local) |
| Auth | Secure Cookie + Sessions |
| Images | Python qrcode library |
