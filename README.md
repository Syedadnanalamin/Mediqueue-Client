# 📚 MediQueue - Tutor Booking Platform

MediQueue is a modern tutor booking platform that connects students with experienced tutors through a simple and intuitive interface. Students can explore tutors, book learning sessions, and manage their bookings, while tutors can publish and manage their tutorial services from a personalized dashboard.

---

# 🌐 Live Demo

* **Live Website:** https://mediqueue-client-ass9.vercel.app/

* **Server Repository:** https://github.com/Syedadnanalamin/Mediqueue-Server.git

---


# 📝 Project Overview

MediQueue simplifies the process of finding and booking tutors online. Students can browse tutor profiles, view available tutorials, and reserve sessions, while tutors can efficiently manage their tutorial offerings, bookings, and personal profiles through a dedicated dashboard.

---

# 🛠️ Technologies Used

## Frontend

* React
* React Router
* Tailwind CSS
* DaisyUI
* Firebase Authentication
* Axios
* React Hook Form
* React Hot Toast
* Framer Motion

## Backend

* Node.js
* Express.js
* MongoDB
* Firebase Admin SDK
* JSON Web Token (JWT)
* CORS
* Dotenv

---

# ✨ Core Features

### 🔐 Authentication & Authorization

* Secure Email & Password authentication
* Google Sign-In
* JWT-secured private routes
* Persistent user sessions

### 👨‍🏫 Tutor Management

* Browse all available tutors
* View detailed tutor profiles
* Add, update, and delete tutorial services
* Manage tutor information from a personalized dashboard

### 📅 Session Booking

* Book tutor sessions with a single click
* View and manage booked sessions
* Prevent duplicate bookings
* Track booking history

### 👨‍🎓 Student Dashboard

* Browse tutors by category
* Manage booked tutors
* View booking details
* Update personal profile

### 📊 Tutor Dashboard

* Add new tutorials
* Edit existing tutorials
* Delete tutorial listings
* Monitor student bookings

### 📱 Responsive Design

* Optimized for Mobile
* Tablet-friendly layout
* Fully responsive desktop experience

---

# 📦 Main Dependencies

## Client

* react
* react-router-dom
* firebase
* axios
* react-hook-form
* react-hot-toast
* framer-motion
* tailwindcss
* daisyui

## Server

* express
* mongodb
* firebase-admin
* jsonwebtoken
* cors
* dotenv
* nodemon

---

# ⚙️ Environment Variables

## Server (.env)

```env
PORT=5000

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

FIREBASE_SERVICE_ACCOUNT=your_firebase_service_account
```

## Client (.env)

```env
VITE_API_URL=http://localhost:5000

VITE_FIREBASE_API_KEY=your_api_key

VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain

VITE_FIREBASE_PROJECT_ID=your_project_id

VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket

VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id

VITE_FIREBASE_APP_ID=your_app_id
```

---

# 🚀 Run Locally

### 1. Clone the repositories

```bash
git clone https://github.com/Syedadnanalamin/Mediqueue-Client.git

git clone https://github.com/Syedadnanalamin/Mediqueue-Server.git
```

---

### 2. Install dependencies

#### Client

```bash
cd MediQueue_Client
npm install
```

#### Server

```bash
cd MediQueue_Server
npm install
```

---

### 3. Configure Environment Variables

Create:

* `.env` inside **MediQueue_Server**
* `.env` inside **MediQueue_Client**

Add the required environment variables shown above.

---

### 4. Start the backend

```bash
cd MediQueue_Server
npm run dev
```

---

### 5. Start the frontend

```bash
cd MediQueue_Client
npm run dev
```

---

### 6. Open the application

```
http://localhost:5173
```

---

# 📂 Repository Structure

```
MediQueue_Client/
MediQueue_Server/
```

---

# 📌 Resources

* Live Website
* Client Repository
* Server Repository
* MongoDB Atlas
* Firebase Console

---

# 👨‍💻 Author

**Syed Adnan**

Full Stack Developer (MERN)
