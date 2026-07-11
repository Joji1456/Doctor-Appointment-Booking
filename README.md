# 🩺 Doctor Appointment Booking App

A full-stack Doctor Appointment Booking System built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**. This application allows patients to book appointments online, doctors to manage schedules, and administrators to oversee the platform.

---

## 🚀 Features

### 👨‍⚕️ Patient
- User Registration & Login
- JWT Authentication
- Search Doctors by Specialization
- View Doctor Profiles
- Book Appointments
- View Appointment History
- Cancel Appointments
- Update Profile

### 👨‍⚕️ Doctor
- Secure Doctor Login
- Manage Profile
- Set Available Time Slots
- View Upcoming Appointments
- Accept or Reject Appointments
- Update Appointment Status

### 👨‍💼 Admin
- Admin Dashboard
- Manage Doctors
- Manage Patients
- View All Appointments
- Delete Users
- Platform Statistics

---

## 🛠️ Tech Stack

### Frontend
- React.js
- React Router DOM
- Axios
- Bootstrap / Tailwind CSS
- React Toastify

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- bcrypt.js
- Multer (Image Upload)
- dotenv

---

## 📂 Project Structure

```
doctor-appointment-booking/
│
├── client/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   ├── routes/
│   │   ├── services/
│   │   ├── App.js
│   │   └── index.js
│
├── server/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── uploads/
│   ├── utils/
│   ├── server.js
│   └── package.json
│
├── README.md
└── package.json
```

---

## 📦 Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/doctor-appointment-booking.git

cd doctor-appointment-booking
```

---

## Backend Setup

```bash
cd server

npm install
```

Create a **.env** file

```env
PORT=5000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key

CLIENT_URL=http://localhost:3000
```

Start Backend

```bash
npm run dev
```

---

## Frontend Setup

```bash
cd client

npm install

npm start
```

React Application runs on

```
http://localhost:3000
```

Backend API runs on

```
http://localhost:5000
```

---

## 🔐 Authentication

- JSON Web Token (JWT)
- Password Encryption using bcrypt.js
- Protected Routes
- Role-Based Access Control

---

## 📊 Database Collections

### Users

```
- _id
- name
- email
- password
- role
- phone
```

### Doctors

```
- _id
- doctorName
- specialization
- experience
- consultationFee
- hospital
- availableSlots
- image
```

### Appointments

```
- _id
- patientId
- doctorId
- appointmentDate
- appointmentTime
- status
```

---

## 📸 Screens

- Home Page
- Login
- Register
- Doctor List
- Doctor Details
- Book Appointment
- Patient Dashboard
- Doctor Dashboard
- Admin Dashboard

---

## API Endpoints

### Authentication

```
POST /api/auth/register

POST /api/auth/login
```

### Doctors

```
GET /api/doctors

GET /api/doctors/:id

POST /api/doctors

PUT /api/doctors/:id

DELETE /api/doctors/:id
```

### Appointments

```
POST /api/appointments

GET /api/appointments

PUT /api/appointments/:id

DELETE /api/appointments/:id
```

---

## Future Enhancements

- Online Payment Integration
- Video Consultation
- Email Notifications
- SMS Notifications
- Prescription Management
- Medical History
- AI Chatbot
- Rating & Reviews
- Multi-language Support
- Dark Mode

---

## Testing

Run Backend

```bash
npm run dev
```

Run Frontend

```bash
npm start
```

Open

```
http://localhost:3000
```

---

## Deployment

### Frontend

- Vercel
- Netlify

### Backend

- Render
- Railway

### Database

- MongoDB Atlas

---

## 📖 Learning Objectives

- React Hooks
- Context API
- Express REST APIs
- MongoDB CRUD
- Authentication
- JWT
- File Upload
- MVC Architecture
- Role-Based Authorization
- API Integration

---

## 👨‍💻 Author

**Talari Jojibabu**

GitHub: https://github.com/Joji1456

LinkedIn: https://www.linkedin.com/in/talari-joji-babu-112886247

---

## ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.

---

## 📜 License

This project is licensed under the MIT License.
