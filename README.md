# 🏡 MERN Real Estate 

A **modern real estate platform** built from scratch using the **MERN stack** (MongoDB, Express.js, React, Node.js). This app features powerful functionality like JWT authentication, Redux Toolkit for state management, image uploads, and a beautifully designed UI for listing properties — a full-stack real-world project crafted with passion.

![MERN Stack](https://img.shields.io/badge/MERN-Stack-blue?style=flat-square)

![Built With Love](https://img.shields.io/badge/Built%20with-%E2%9D%A4-red)

---

## 🚀 Project Highlights

- 🔑 **Authentication**: JWT-based login/signup + Google OAuth integration
- 🏘️ **Listings Management**: Add, update, and delete property listings
- 🖼️ **Image Uploads**: Upload and preview images of properties
- 🧭 **Search Functionality**: Filter and search listings easily
- ⚙️ **Redux Toolkit**: Global state management made simple and efficient
- 🌐 **Responsive UI**: Built with Tailwind CSS for a modern, clean layout
- 📦 **Deployed-Ready**: Easily deployable to Render, Vercel, or other platforms

---

## 🛠️ Tech Stack

| Frontend | Backend | Auth | Deployment |
|---------|---------|------|-------------|
| React, Tailwind CSS | Node.js, Express.js | JWT, Google OAuth | Render / Vercel |
| Redux Toolkit       | MongoDB Atlas      | Firebase (optional) |               |

---



---

## 📦 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Saurabhjk15/RealEstate-mern-stack.git
cd RealEstate-mern-stack
```
2. Install Dependencies
```bash
# For frontend
cd client
npm install

# For backend
cd ../server
npm install
```
🛡️ Environment Variables
```bash
Create a .env file inside the /server directory and add the following:
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GOOGLE_CLIENT_ID=your_google_client_id
```

✅ Features
>Secure login and registration

>Protected routes

>Real-time listing search

>Google sign-in integration

>Image previews before upload

>Fully responsive for mobile/tablets

▶️ Run Locally
**Backend**
```bash
cd server
npm run dev
```
**Frontend**
```bash
cd client
npm start
```

