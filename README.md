# Prescripto - Full Stack Doctor Appointment Booking System

## Live Demo
[Prescripto - Live Application](https://prescripto.vercel.app/)

## Figma Design Reference
[Prescripto - UI Design](https://www.figma.com/design/ZLkjwG5ehxNRrC4SUA2WG7/Prescripto---UI-Design)

## Project Overview
Prescripto is a full-stack doctor appointment booking system designed for hospitals and individual practitioners. It includes three levels of authentication, allowing patients, doctors, and administrators to manage appointments efficiently.

### Key Features
- **Patient Module:**
  - User authentication and role-based access control.
  - Appointment booking system.
  - Dashboard to manage booked appointments.
  - Profile management.
  
- **Doctor Module:**
  - Secure login with role-based access.
  - Appointment management and scheduling.
  - Earnings dashboard.
  - Profile update functionality.

- **Admin Module:**
  - Comprehensive dashboard to manage doctors and appointments.
  - User management and role assignment.
  - System analytics and reports.

- **Upcoming Features:**
  - Integration of an online payment gateway for appointment fees.
  - Enhanced user notifications and reminders.

## Tech Stack
- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (with Mongoose ODM)
- **Authentication:** JSON Web Token (JWT), bcrypt
- **Deployment:** Vercel (Frontend), vercel (Backend)

## Installation Guide
1. Clone the repository:
   ```bash
   git clone https://github.com/olomumicheal/prescripto.git
   ```
2. Navigate to the backend folder:
   ```bash
   cd backend
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Set up the environment variables in a `.env` file:
   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```
5. Start the backend server:
   ```bash
   npm run dev
   ```
6. Navigate to the frontend folder:
   ```bash
   cd frontend
   ```
7. Install frontend dependencies:
   ```bash
   npm install
   ```
8. Start the frontend application:
   ```bash
   npm run dev
   ```

## Advanced Feature Suggestions for HelpMum
To make this project more suitable for HelpMum and increase its impact, the following advanced features can be integrated:

- **AI-Powered Doctor Recommendations:**
  - Implement machine learning to suggest doctors based on user history and preferences.
  
- **Telemedicine and Video Consultations:**
  - Integrate WebRTC for secure video consultations.
  
- **Electronic Health Records (EHR) Management:**
  - Secure storage of patient medical history and reports.

- **Multi-Language and Accessibility Support:**
  - Localized language options for broader reach.

- **Automated Appointment Reminders:**
  - SMS and email notifications for upcoming appointments.

- **Maternal and Child Healthcare Features:**
  - Custom appointment scheduling for prenatal and postnatal care.
  - Vaccination tracking system.

## Conclusion
Prescripto is a scalable solution for hospitals and individual doctors looking to digitize their appointment management system. By integrating advanced features like AI-based recommendations and telemedicine, this platform can significantly contribute to improving healthcare accessibility, particularly in maternal and child health services, aligning well with HelpMum’s mission.

