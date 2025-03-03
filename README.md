# Prescripto - Full Stack Doctor Appointment Booking System

## Live Demo
[Prescripto](https://prescripto.vercel.app/)

## About the Project
Prescripto is a **full-stack doctor appointment booking system** designed to streamline the booking process for hospitals and medical professionals. It features a **three-tier authentication system** catering to **patients, doctors, and administrators**.

## Key Features
### 👩‍⚕️ Patients
- Sign up and log in securely.
- Book appointments with available doctors.
- Manage booked appointments.
- View and track appointment history.

### 🏥 Doctors
- Secure login for doctors.
- Manage and view scheduled appointments.
- Track earnings and update profiles from the dashboard.

### 🔧 Admin Dashboard
- Oversee and manage all appointments.
- Manage doctor profiles.
- Ensure a seamless booking experience for users.

## Upcoming Features
- **Online Payment Gateway**: Integration of a secure payment gateway to allow patients to pay their consultation fees online.
- **Advanced Notifications**: Email and SMS notifications for appointment confirmations and reminders.
- **User Analytics**: Insights into patient bookings and doctor performance.

## Technologies Used
- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose)
- **Authentication**: JWT
- **Deployment**: Vercel (Frontend), Render/Heroku (Backend)

## Installation Guide
### Prerequisites
Ensure you have the following installed:
- Node.js (v18+ recommended)
- MongoDB (local or Atlas)
- Git

### Setup Steps
1. **Clone the repository:**
   ```sh
   git clone https://github.com/olomumicheal/prescripto.git
   cd prescripto
   ```
2. **Install dependencies:**
   ```sh
   cd backend
   npm install
   cd ../frontend
   npm install
   ```
3. **Set up environment variables:**
   - Create a `.env` file in the `backend` directory and configure:
     ```env
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_secret_key
     ```
4. **Run the application:**
   ```sh
   cd backend
   npm start
   ```
   In another terminal:
   ```sh
   cd frontend
   npm start
   ```

## Contribution
Feel free to fork this project and submit a pull request with improvements!

## License
This project is licensed under the MIT License.

