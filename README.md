# 📚 MediQueue - Tutor Booking Platform

MediQueue is a modern full-stack tutor booking platform that connects students with qualified tutors through a seamless and user-friendly experience. Students can explore available tutors, book tutorial sessions, and manage their bookings, while tutors can create, update, and manage their tutorial services from a dedicated dashboard.

---

# 🌐 Live Demo

* **Live Website:** https://mediqueue-client-ass9.vercel.app/
* **Client Repository:** https://github.com/Syedadnanalamin/Mediqueue-Client
* **Server Repository:** https://github.com/Syedadnanalamin/Mediqueue-Server

---

# 📸 Project Screenshot

> Add a screenshot of your homepage or dashboard here.

```text
README/assets/mediqueue-preview.png
```

```md
![MediQueue Screenshot](README/assets/mediqueue-preview.png)
```

---

# 📝 Project Overview

MediQueue simplifies the tutor booking process by providing a centralized platform where students can discover tutors, explore tutorial services, and reserve learning sessions. Tutors can efficiently manage their tutorials, monitor bookings, and update their profiles through an intuitive dashboard.

---

# 🛠️ Technologies Used

## Frontend

* React
* React Router
* Tailwind CSS
* DaisyUI
* Better Auth
* Axios
* React Hook Form
* React Hot Toast
* Framer Motion

## Backend

* Node.js
* Express.js
* MongoDB
* Better Auth
* CORS
* Dotenv

---

# ✨ Core Features

### 🔐 Authentication & Authorization

* Secure authentication using Better Auth
* Email and password sign in
* Persistent session management
* Protected private routes

### 👨‍🏫 Tutor Management

* Browse all available tutors
* View detailed tutor profiles
* Add new tutorial services
* Update existing tutorials
* Delete tutorials
* Manage tutorials from a personalized dashboard

### 📅 Session Booking

* Book tutorial sessions
* View booked tutorials
* Prevent duplicate bookings
* Manage booking history

### 👨‍🎓 Student Dashboard

* Explore tutors
* View booked sessions
* Manage personal bookings
* Access detailed tutor information

### 📊 Tutor Dashboard

* Create tutorial listings
* Edit tutorial information
* Remove tutorial services
* Track student bookings

### 📱 Responsive Design

* Mobile-friendly interface
* Tablet optimized
* Fully responsive desktop experience

---

# 📦 Main Dependencies

## Client

* react
* react-router-dom
* better-auth
* axios
* react-hook-form
* react-hot-toast
* framer-motion
* tailwindcss
* daisyui

## Server

* express
* mongodb
* better-auth
* cors
* dotenv
* nodemon

---

# ⚙️ Environment Variables

## Server (.env)

```env
PORT=5000

MONGO_URI=your_mongodb_connection_string

BETTER_AUTH_SECRET=your_better_auth_secret

BETTER_AUTH_URL=http://localhost:5173
```

## Client (.env)

```env
VITE_API_URL=http://localhost:5000
```

> Add any additional environment variables required by your project.

---

# 🚀 Run Locally

### 1. Clone the repositories

```bash
git clone https://github.com/Syedadnanalamin/Mediqueue-Client.git

git clone https://github.com/Syedadnanalamin/Mediqueue-Server.git
```

### 2. Install dependencies

#### Client

```bash
cd Mediqueue-Client
npm install
```

#### Server

```bash
cd Mediqueue-Server
npm install
```

### 3. Configure Environment Variables

Create:

* `.env` inside **Mediqueue-Server**
* `.env` (or `.env.local` if applicable) inside **Mediqueue-Client**

Then add the required environment variables shown above.

### 4. Start the backend

```bash
cd Mediqueue-Server
npm run dev
```

### 5. Start the frontend

```bash
cd Mediqueue-Client
npm run dev
```

### 6. Open the application

```
http://localhost:5173
```

---

# 📂 Project Structure

```
Mediqueue-Client/
Mediqueue-Server/
```

---

# 📌 Resources

* 🌐 Live Website
* 💻 Client Repository
* ⚙️ Server Repository
* 🍃 MongoDB Atlas
* 🔐 Better Auth Documentation

---

# 👨‍💻 Author

**Syed Adnan**

Full Stack Developer (MERN)
