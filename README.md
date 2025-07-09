# 🎓 AchievBookOIST - Digital Student Achievement Platform

AchievBookOIST is a MERN stack web application built for students of **Oriental Institute of Science and Technology (OIST)** to share and view peer 
achievements like certifications, hackathon wins, participation in events, etc. It works as a digital magazine for recognizing student excellence.

---

## 🧩 Features

- 🔐 User Authentication (Login & Signup)
- 📝 Post achievements with description and media
- 📸 Edit Profile with image upload support
- 🌐 Explore student network (connections)
- 🛎 Notifications for user activity
- 👥 Context-based User and Auth management (React Context API)
- 💬 Dynamic "Student of the Day" style achievement feed

---

## 🛠️ Tech Stack

### Frontend
- React.js (Vite)
- Tailwind CSS
- React Router DOM
- Context API

### Backend
- Node.js
- Express.js
- MongoDB (via Mongoose)
- JWT for authentication
- Multer & Cloudinary for image uploads

---

## 📁 Project Structure

### 📦 `backend/`
- `config/`: DB, token, and Cloudinary setup
- `controllers/`: Logic for users, posts, notifications, auth, etc.
- `middlewares/`: Auth protection & file upload
- `models/`: Mongoose schemas for users, posts, etc.
- `routes/`: All backend API route handlers

### 📦 `frontend/src/`
- `components/`: Reusable UI components like `Nav`, `Posts`, `EditProfile`
- `context/`: Global state management with `AuthContext` & `UserContext`
- `pages/`: App pages like `Home`, `Login`, `Signup`, `Profile`, `Network`, `Notification`
- `assets/`: Images or static resources

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/AchievBookOIST.git
cd AchievBookOIST
