# FriendSpace 👥🌐  
A full-stack social media platform built using the MERN stack (MongoDB, Express.js, React.js, Node.js) with JWT authentication, Redux state management, and Material UI theming.

---

## 🧩 Features

- 🔐 User Authentication (JWT, bcrypt)
- 🗣️ Post creation, deletion, and viewing
- 👤 User profile with posts
- 🌓 Light/Dark Mode toggle (MUI)
- 🧠 Redux Toolkit for global state
- 📱 Fully responsive UI (Material UI)
- 🔁 Persistent Login with Redux Persist

---

## 🧱 Tech Stack

| Frontend | Backend | Database | Tools |
|----------|---------|----------|-------|
| React.js, Redux Toolkit, MUI | Node.js, Express.js | MongoDB, Mongoose | JWT, Bcrypt, Axios, Formik, Yup |

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/chaituthumbeti/FriendSpace.git
cd FriendSpace
```
### 2. Backend setup

```bash
cd server
npm install
touch .env
```
Add your environment variables in .env:
PORT=5000
MONGO_URL=mongodb+srv://<your_mongo_url>
JWT_SECRET=your_jwt_secret

```bash
npm run dev
```

### 3. Frontend setup

```bash
cd client
npm install
npm start
```
