# Student Connect – Smart Academic & Event Management Platform

## 📌 Overview

Student Connect is a MERN Stack-based web application designed to centralize academic communication, event management, and learning resources for students and faculty.

The platform eliminates the need to track updates across multiple channels by providing a single dashboard for announcements, events, assignments, and study materials.

---

## 🚀 Features

### 🔐 Authentication & Authorization

* User Registration and Login
* JWT-Based Authentication
* Role-Based Access Control

  * Student
  * Faculty/Admin

### 📢 Announcement Management

* Faculty can create and publish announcements
* Students can view all academic updates in one place
* Centralized communication system

### 📅 Event Management

* Create and manage academic events
* Workshops, seminars, mock tests, and sessions
* Students can view upcoming events

### 📚 Study Resources

* Upload and manage learning materials
* Notes, PDFs, and useful links
* Easy access to educational resources

### 📝 Assignment Tracking

* Faculty can post assignments
* Students can view assignment deadlines
* Assignment status management

### 📊 Dashboard

* Personalized dashboard for users
* Quick access to announcements, events, and resources
* Role-specific functionalities

---

## 🛠️ Tech Stack

### Frontend

* React.js
* React Router
* Axios
* HTML5
* CSS3
* JavaScript (ES6+)

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### Authentication

* JWT (JSON Web Token)
* bcrypt.js

---

## 📂 Project Structure

```text
student-connect/
│
├── client/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── context/
│   │   ├── App.js
│   │   └── index.js
│   │
│   └── package.json
│
├── server/
│   ├── config/
│   ├── models/
│   ├── controllers/
│   ├── routes/
│   ├── middleware/
│   ├── utils/
│   ├── server.js
│   └── package.json
│
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/your-username/student-connect.git
cd student-connect
```

### Install Frontend Dependencies

```bash
cd client
npm install
```

### Install Backend Dependencies

```bash
cd ../server
npm install
```

---

## 🔧 Environment Variables

Create a `.env` file inside the `server` folder.

```env
PORT=5000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret_key
```

---

## ▶️ Running the Application

### Start Backend

```bash
cd server
npm start
```

### Start Frontend

```bash
cd client
npm start
```

Frontend:

```text
http://localhost:3000
```

Backend:

```text
http://localhost:5000
```

---

## 📸 Key Modules

* Authentication System
* Announcement Management
* Event Management
* Study Resource Sharing
* Assignment Tracking
* Role-Based Access Control
* Dashboard Analytics

---

## 🎯 Future Enhancements

* Event Registration System
* File Upload Support
* Email Notifications
* Search and Filter Functionality
* Dashboard Analytics
* Real-Time Notifications
* Attendance Tracking

---

## 👨‍💻 Author

Kunal Gundawar

---

## 📄 License

This project is developed for educational and learning purposes.
