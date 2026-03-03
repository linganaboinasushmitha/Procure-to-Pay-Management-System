# 🌐 Developer Social Network (MERN Stack)

## 🚀 Project Overview

This is a full-stack Social Networking Web Application built using the MERN stack.  
The application allows developers to create profiles, authenticate securely, post content, and interact through discussion forums.

This project demonstrates authentication, protected routes, state management, and full-stack API integration.

---

## 🛠 Tech Stack

### Frontend
- React.js
- Redux (State Management)
- React Router v6
- Axios

### Backend
- Node.js
- Express.js
- JWT Authentication
- RESTful APIs

### Database
- MongoDB (Mongoose ODM)

---

## ✨ Key Features

- User Registration & Login (JWT Authentication)
- Secure Protected Routes
- Developer Profile Creation
- Add Education & Experience
- Create, Like & Comment on Posts
- GitHub Repository Integration
- Token Expiry Auto Logout
- Redux Store Subscription Handling
- API Error Handling

---

## 🔗 Frontend & Backend Integration

- Frontend communicates with backend using REST APIs.
- JWT token is stored securely and attached to API headers.
- Axios interceptor handles token expiration.
- Redux manages global application state.

---

## 🗄 Database Structure (MongoDB Collections)

### Users
- name
- email
- password (hashed)
- avatar
- date

### Profiles
- user (ObjectId reference)
- bio
- skills
- experience[]
- education[]
- social links

### Posts
- user
- text
- likes[]
- comments[]
- date

---

## 📦 Installation

### Install Dependencies
```
npm install
cd client
npm install
```

### Run Development Mode
```
npm run dev
```

---

## 🎯 Learning Outcomes

- Built full-stack MERN architecture
- Implemented JWT authentication
- Created protected routes
- Managed global state with Redux
- Integrated GitHub API
- Handled token expiration securely
- Structured scalable backend APIs

---

## 👩‍💻 Developed By

Sushmitha Linganaboina  
Full Stack Developer | React | Node.js | MongoDB | Open to Work

---

✨ Building scalable and secure web applications.
