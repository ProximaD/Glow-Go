# Glow-Go
Online Salon Booking System using PHP and MySQL.
Core Features
✅ User Registration & Login
✅ Booking System (Select service, date, and time)
✅ Admin Dashboard (Manage bookings & services)
✅ Service Listings (Haircuts, facials, etc.)
✅ Appointment Confirmation & Status

#Tech Stack
Frontend: HTML, CSS, JavaScript (optional: Bootstrap for styling)
Backend: PHP, MySQL
Database: MySQL (Tables for users, services, and bookings)

#Project Breakdown
   #Database Setup

users table (id, name, email, password)
services table (id, name, price, duration)
bookings table (id, user_id, service_id, date, time, status)
User Authentication

# Registration & login system with hashed passwords
User session management
Booking Functionality

# Display available services
Form to select service, date, and time
Insert booking into the database
Admin Panel

# View & manage appointments
Approve or cancel bookings
Add/edit salon services
Email/SMS Notifications (Optional)

Send booking confirmation via email
Notify users about appointment status
