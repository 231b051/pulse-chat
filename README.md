# 🚀 Pulse Chat – Real-Time MERN Chat Application

Pulse Chat is a full-stack real-time chat application built using the MERN stack and Socket.io.  
It enables authenticated users to communicate instantly with persistent message storage.

---

## 🌐 Live Demo

Frontend (Netlify):  
👉 [https://your-netlify-link.netlify.app  ](https://resonant-cranachan-1a4338.netlify.app/)

Backend (Render):  
👉 [https://your-render-link.onrender.co](https://coding-samurai-internship-task-e99h.onrender.com)  

---

## 🏗️ Tech Stack

### Frontend
- React (Vite)
- Axios
- Socket.io-client
- CSS / Tailwind (if used)

### Backend
- Node.js
- Express.js
- Socket.io
- MongoDB Atlas
- JWT Authentication
- bcrypt (Password Hashing)

---

## ✨ Features

- 🔐 User Registration & Login (JWT-based Authentication)
- 💬 Real-time messaging using WebSockets (Socket.io)
- 💾 Message persistence in MongoDB
- 🟢 Online user connection handling
- 🔄 Automatic reconnection support
- 🌍 Production deployment (Netlify + Render)

---

## 🧠 System Architecture
Frontend (Netlify)
|
| REST APIs + WebSocket
v
Backend (Render)
|
v
MongoDB Atlas


- Authentication handled via REST APIs.
- Real-time messaging handled via Socket.io.
- Messages stored and retrieved from MongoDB.

---

## 🛠️ Local Setup Instructions

### 1️⃣ Clone Repository
git clone https://github.com/231b051/pulse-chat.git
cd pulse-chat

2️⃣ Backend Setup
cd server
npm install

Create .env file inside /server:



Run backend:

npm start
3️⃣ Frontend Setup
cd client
npm install

Create .env file inside /client:

VITE_API_URL=http://localhost:10000

Run frontend:

npm run dev
🔐 Production Environment Variables
Backend (Render)

MONGO_URI

JWT_SECRET

CLIENT_URL

Frontend (Netlify)

VITE_API_URL=[https://your-backend-url.onrender.com](https://resonant-cranachan-1a4338.netlify.app/)

📸 Screenshots
Login Page:- <img width="1502" height="841" alt="image" src="https://github.com/user-attachments/assets/a82d9390-6041-4224-af34-8e571c2ed2e8" />

Chat Interface:-<img width="1879" height="916" alt="image" src="https://github.com/user-attachments/assets/ed180c18-5778-47dd-8e05-c585d3475879" />


📌 Future Improvements

Group chat support

Typing indicators

WebRTC support

👨‍💻 Author

Ankit
B.Tech CSE 
