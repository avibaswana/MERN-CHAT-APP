# 📝 Chat App – MERN Stack

## 📌 Description

A real-time chat application built with the MERN stack (MongoDB, Express, React, Node.js) and Socket.IO for real-time communication.

---

## 🚀 Features

- 💬 Real-time messaging with Socket.IO
- 🔐 User authentication (login/register)
- 🧑‍🤝‍🧑 Private 1-on-1 chats
- 🌐 JWT-based session management
- 🎨 Tailwind CSS for styling
- 🛠️ Zustand for state management

---

## 🧰 Tech Stack

**Frontend:**
- React + Vite
- Zustand (state management)
- Tailwind CSS
- Axios

**Backend:**
- Node.js
- Express.js
- MongoDB + Mongoose
- Socket.IO
- JWT

---

## 📂 Project Structure

```
CHAT-APP/
├── backend/             # Express + MongoDB API
│   ├── src/
│   │   ├── controllers/
│   │   ├── lib/
│   │   ├── middleware/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── seeds/
│   │   └── index.js
│   ├── .env
│   ├── package.json
├── frontend/            # React app with Vite
│   ├── public/
│   ├── src/
│   ├── index.html
│   ├── vite.config.js
│   └── tailwind.config.js
├── .gitignore
├── README.md
```

---

## 🔧 Setup Instructions

### 📦 Prerequisites

- Node.js and npm
- MongoDB running locally or Atlas URI
- Git

---

### ⬇️ Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/chat-app.git
cd chat-app
```

---

### ⚙️ Setup Backend

```bash
cd backend
npm install
```

Create `.env` in `backend/` with:

```env
PORT=5001
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
CLIENT_URL=http://localhost:5173
```

Start server:

```bash
npm start
```

---

### 🎨 Setup Frontend

```bash
cd frontend
npm install
npm run dev
```

> Runs at: `http://localhost:5173`



