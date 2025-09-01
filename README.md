# 🔐 Node.js Auth Starter – JWT + MongoDB + Express

A simple and modular **authentication starter** built with **Node.js**, **Express**, **MongoDB**, and **JWT**.  
Includes user registration, login, protected routes, and token-based access control — ready to plug into any project.

---

## 🚀 Tech Stack

- **Backend**: Node.js + Express
- **Database**: MongoDB (Mongoose)
- **Authentication**: JWT (access & refresh tokens)
- **Security**: Helmet, bcrypt, CORS
- **Environment**: dotenv

---

## 🧩 Features

✅ User registration (`/api/auth/register`)  
✅ Login with email & password (`/api/auth/login`)  
✅ Hashed passwords (bcrypt)  
✅ JWT token generation & verification  
✅ Refresh token pattern (optional setup)  
✅ Clean folder structure  
✅ CORS-ready API  

---

## ⚙️ Installation

```bash
git clone https://github.com/mussarri/node_auth_starter.git
cd node_auth_starter
npm install
```

## 🔧 .env Configuration
```bash
FRONT_END_URL
MONGO_URL
PORT
SECRET_ACCESS=your_access_secret_key
SECRET_REFRESH=your_refresh_secret_key
```

## ▶️ Run Locally
```bash
npm run dev
```

🔐 API Endpoints<br> 
POST /auth/register<br> 
POST /auth/login<br> 
GET  /auth/logout<br> 
GET  /auth/refresh







