# NiyaCare - Doctor Appointment Booking App

NiyaCare is a full-stack doctor appointment booking application built using React Native, Node.js, Express.js, TypeScript, and MongoDB.

The application provides separate experiences for patients and administrators. Patients can browse doctors, view available dates and time slots, and book appointments. Administrators can manage doctors, appointments, and dashboard statistics.

## 🚀 Features

### 👤 User / Patient

- User registration and login
- JWT-based authentication
- Forgot password functionality
- Email OTP verification
- Password reset
- Browse available doctors
- View doctor details
- View doctor availability
- Select appointment date
- Select available time slot
- Book appointments
- View personal appointments
- Appointment status tracking
- Logout

### 🛠️ Admin

- Separate admin authentication
- Admin dashboard
- View dashboard statistics
- Add doctors
- Edit doctor details
- Delete doctors
- Configure doctor availability
- Configure daily token count
- View all appointments
- Confirm pending appointments
- Cancel pending appointments
- Mark confirmed appointments as completed
- Admin logout

### 📅 Appointment Management

Appointment statuses:

```text
Pending
   ↓
Confirmed
   ↓
Completed
