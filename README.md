Smart University Appointment Management System - Backend

Install
npm install
Run
npm run dev
Database
SQLite database will be created automatically.

Main APIs
Auth
POST /api/auth/register
POST /api/auth/login
Appointments
GET /api/appointments
POST /api/appointments
PUT /api/appointments/:id
DELETE /api/appointments/:id
Availability
POST /api/availability
GET /api/availability/:instructorId
