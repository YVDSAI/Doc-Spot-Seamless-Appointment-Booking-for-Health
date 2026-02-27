# 🩺 DocSpot - Seamless Appointment Booking System

DocSpot is a full-stack healthcare platform built using the **MERN stack** (MongoDB, Express, React, Node.js). 
It provides a seamless experience for patients to discover trusted doctors, book appointments, and manage their health schedules while offering a robust management panel for doctors and administrators.

---

## 🚀 Features

### **For Patients**
- **Seamless Booking:** Browse and book appointments with top doctors in just a few clicks.
- **Specialization Filtering:** Find doctors by categories (General Physician, Gynecologist, Dermatologist, etc.).
- **User Dashboard:** View upcoming appointments, manage profile information, and track history.
- **Secure Authentication:** JWT-based login and registration.

### **For Doctors**
- **Appointment Management:** View and track patient bookings.
- **Profile Customization:** Manage availability and professional details.

### **For Admins**
- **Universal Control:** Add new doctors, verify credentials, and manage the overall user base.
- **Platform Analytics:** Overview of total appointments and active patients.

---

## 🛠️ Tech Stack

- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (with Mongoose)
- **Authentication:** JSON Web Tokens (JWT) & Bcrypt.js
- **State Management:** React Context API / Redux

---

## 📂 Project Structure
Doc-Spot-Seamless-Appointment-Booking/

├── Project_files/

 │   ├── admin/      # Admin Panel Frontend (React)

 │   ├── backend/    # Express Server & API Routes

 │   └── frontend/   # Patient/User Frontend (React)

---
## ⚙️ Installation & Setup
Prerequisites
Node.js installed

MongoDB Atlas account or local MongoDB instance

**Backend Setup:**

cd backend

npm install

-Server runs on http://localhost:5000

**Frontend Setup:**

cd ../frontend

npm install

npm start

-Client runs on http://localhost:5173
