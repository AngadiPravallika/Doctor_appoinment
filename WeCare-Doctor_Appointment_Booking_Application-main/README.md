# Doctor_Appointment_Booking_Application

📺 **Click the image above or [watch the demo here](https://drive.google.com/file/d/1sAvTTrGPlbfzjCyN4ZQAwE8ncMNFI1z3/view?usp=sharing)**

---

## 🩺 Project Overview

A Doctor's Appointment Booking System that lets users:
- Register and login
- View doctors
- Book, update, delete appointments
- Video consultation via email invite

⚠️ **Note:** Backend is deployed using Render, so some delay may occur.

---

## 🧪 Test Credentials

### 👨‍⚕️ Doctor Login
- `doc1@gmail.com` / `doc1` (has appointments)
- `pococare@gmail.com` / `pococare`

### 🧍 Patient Login
- `user1@gmail.com` / `user1`
- `user2@gmail.com` / `user1`
- `patient11@gmail.com` / `patient11`

🔔 *To try Video Call, use a real email while registering a Doctor.*

---

## 🚀 Features

- JWT Authentication
- Register/Login: Doctors and Patients
- Logout using blacklist
- Book/Edit/Delete Appointments
- View Appointments
- Toggle Video Call availability
- Nodemailer: Send video call links via email
- WebRTC-based video call room

---

## 🧭 Application Flow

1. Register as Doctor or Patient
2. Login as Patient → View doctors
3. Book/Edit/Delete appointments
4. Video call if doctor is available → Email sent with link
5. Login as Doctor → Join via meet link → Start consultation
6. Mute/Unmute, Start/Stop Video
7. Logout

---

## 🛠️ Tech Stack

[![My Skills](https://skillicons.dev/icons?i=js,nodejs,express,mongodb,html,css)](https://skillicons.dev)

### 🧰 Tools Used

[![My Tools](https://skillicons.dev/icons?i=vercel,github)](https://skillicons.dev)  
<img alt="NPM" height=50 width=80 src="https://www.w3schools.com/whatis/img_npm.jpg" />

---

## 🔗 Live Links

- 🌐 Frontend: https://wecareyou.vercel.app/  
- 🔁 Backend (Render): https://pococare1.onrender.com/

---

## 🖼️ Screenshots

### 🏠 Home Page  
![Home](https://github.com/DhaanuI/Pococare_assignment/assets/112754832/fc64ac55-26d5-438f-ba2c-39c75b6e5aa8)

### 🔐 Login Page  
![Login](https://github.com/DhaanuI/Pococare_assignment/assets/112754832/791a559d-0908-40f4-aefd-90867e8383d5)

### 👨‍⚕️ Doctor Dashboard  
![Doctor](https://github.com/DhaanuI/Pococare_assignment/assets/112754832/52f852c3-191b-4473-8f3f-08f79d99e14c)

### 🧍 Patient Dashboard  
![Patient](https://github.com/DhaanuI/Pococare_assignment/assets/112754832/f30893d8-d55d-4e89-a487-1fa42342c0ef)

### 📆 Appointments  
![Appointments](https://github.com/DhaanuI/Pococare_assignment/assets/112754832/7ae53a8b-c630-4b98-b46f-d2253919d7de)

### 🎥 Video Consultation  
![Video](https://github.com/DhaanuI/Pococare_assignment/assets/112754832/b0efab74-d38d-4d54-8245-a108fa33588c)

---

## 💻 How to Run Locally

```bash
git clone https://github.com/AngadiPravallika/Doctor_appoinment.git
cd Doctor_appoinment
npm install
cd backend
npm run server
