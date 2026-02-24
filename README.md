# 🌐 Virtual Marketplace for Freelancers & Service Providers

A full-stack **online virtual marketplace** where users can act as **Freelancers** or **Clients**. Clients can post jobs, freelancers can apply for jobs, manage services, and securely collaborate through a modern web platform.

This project is built as a real-world full-stack application using modern technologies and best practices.

---

## 🚀 Live Demo

🔗https://freelancer-bd.vercel.app/

---

## ✨ Key Features

### 👤 User Roles

* **Client**

  * Post jobs
  * View freelancer applications
  * Hire freelancers
* **Freelancer**

  * Browse available jobs
  * Apply for jobs
  * Manage applied jobs

### 🔐 Authentication

* Firebase Authentication
* Email & Password login
* Secure user session handling

### 💳 Payment Integration

* Secure online payment system
* Ensures safe transactions between client and freelancer

### 🗺️ Map Integration

* Interactive map integration
* Helps visualize service or user locations

### 📦 Job Management

* Job posting and application system
* Real-time data handling using MongoDB

---

## 🛠️ Tech Stack

### Frontend

* React (Vite)
* Tailwind CSS / DaisyUI
* Firebase Authentication
* Deployed on **Vercel**

### Backend

* Node.js
* Express.js
* MongoDB (NoSQL Database)
* RESTful API architecture

---

## 📁 Project Structure

```
root/
├── client/        # Frontend (React + Vite)
│   ├── src/
│   ├── package.json
│   └── vite.config.js
│
├── server/        # Backend (Node + Express)
│   ├── routes/
│   ├── index.js
│   └── package.json
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
```

### 2️⃣ Client Setup

```bash
cd client
npm install
npm run dev
```

### 3️⃣ Server Setup

```bash
cd server
npm install
npm run start
```

---

## 🔑 Environment Variables

Create a `.env` file in both **client** and **server** folders.

### Client (.env)

```
VITE_FIREBASE_API_KEY=your_key
VITE_FIREBASE_AUTH_DOMAIN=your_domain
```

### Server (.env)

```
MONGODB_URI=your_mongodb_connection
PORT=5000
```

---

## 🌍 Deployment

* **Frontend** deployed on **Vercel**
* **Backend** hosted using Node.js server
* MongoDB Atlas used for database hosting

---

## 🎯 Purpose of the Project

This project was developed to:

* Practice real-world **full-stack development**
* Implement **authentication & payment systems**
* Work with **maps, APIs, and databases**
* Build a scalable marketplace platform

---

## 👨‍💻 Author

**Hasib Al Mamun**
CSE Student | Full-Stack Developer

---

## 📜 License

This project is for **educational purposes** and personal portfolio use.

---

⭐ If you like this project, feel free to star the repository!
