# 🔐 OTP Login System (React + Node.js + Twilio/Nodemailer)

A full-stack OTP-based login system that allows users to authenticate via **SMS** (Twilio) or **Email** (Nodemailer). Built with **React.js**, **Tailwind CSS**, **Node.js**, and **JWT** for session management.

---

## 🌟 Features

- Login via **Phone (SMS)** or **Email**
- OTP is securely sent using:
  - 📲 **Twilio** for SMS
  - 📧 **Nodemailer** for Email
- Simple & clean UI using **Tailwind CSS**
- **JWT** token-based session with localStorage
- Protected **dashboard page**
- Modular backend with Express.js

---

## 🛠️ Tech Stack

### Frontend
- [React.js](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Axios](https://axios-http.com/)

### Backend
- [Node.js + Express](https://expressjs.com/)
- [Twilio](https://www.twilio.com/) (SMS)
- [Nodemailer](https://nodemailer.com/) (Email)
- [JWT](https://jwt.io/) (Authentication)

---

## 🚀 Getting Started

### 1 Clone the Repo or Frontend Setup (React)

```bash
git clone https://github.com/Jayy0906/OTP-login-with-react.git
cd OTP-login-with-react
npm i
npm run dev

### 2 Backend Setup (Node.js)

```bash
cd otp-backend
npm install
node server.js
Runs the server at http://localhost:5000

### Environment Variables

```bash

Create a .env file in otp-backend/ with the following:

PORT=5000

# JWT
JWT_SECRET=your_jwt_secret_key

# Twilio (for SMS OTP)
TWILIO_ACCOUNT_SID=your_account_sid
TWILIO_AUTH_TOKEN=your_auth_token
TWILIO_PHONE_NUMBER=your_twilio_number

# Nodemailer (for Email OTP)
EMAIL_USER=youremail@gmail.com
EMAIL_PASS=your_email_password_or_app_password
