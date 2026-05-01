# 🔐 Auth MERN — Full-Stack Authentication System

A production-ready, full-stack authentication system built with the **MERN** stack (MongoDB, Express, React, Node.js). Features complete user authentication with JWT tokens stored in HTTP-only cookies, OTP-based email verification, and a secure password reset flow — all wrapped in a polished React + Tailwind CSS UI.

---

## ✨ Features

| Feature                   | Description                                                          |
| ------------------------- | -------------------------------------------------------------------- |
| 📝 **Register**           | Sign up with name, email & password. Welcome email sent instantly.   |
| 🔑 **Login / Logout**     | Secure login with JWT stored in HTTP-only cookie                     |
| 📧 **Email Verification** | 6-digit OTP sent via email (valid 24 hours)                          |
| 🔒 **Password Reset**     | OTP-based reset flow (valid 15 minutes)                              |
| 🛡️ **Protected Routes**  | Middleware-guarded API endpoints                                     |
| 🍪 **Cookie Auth**        | HTTP-only, Secure, SameSite cookies — no localStorage token exposure |
| 🌐 **CORS Configured**    | Proper CORS setup for local development                              |

---

## 🗂️ Project Structure

```
Auth/
├── client/
├── server/
├── .gitignore
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

* Node.js v18+
* MongoDB Atlas (or local MongoDB)
* Brevo (Sendinblue) account for SMTP email

---

### 1. Clone the Repository

```bash
git clone https://github.com/MONJIT07/Auth.git
cd Auth
```

---

### 2. Backend Setup

```bash
cd server
npm install
cp .env.example .env
npm run server
```

---

### 3. Frontend Setup

```bash
cd ../client
npm install
cp .env.example .env
npm run dev
```

---

## 🔌 API Overview

* `/api/auth/*` → Authentication routes
* `/api/user/*` → User data routes

---

## 🧠 Tech Stack

**Backend:** Node.js, Express, MongoDB, JWT, bcrypt
**Frontend:** React, Vite, Tailwind CSS

---

## 🔐 Security

* Password hashing with bcrypt
* JWT stored in HTTP-only cookies
* OTP-based verification and reset

---

## 📄 License

MIT License

---

> Built with ❤️ by [MONJIT07](https://github.com/MONJIT07)
