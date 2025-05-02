# smileapp
This is a call service-based app. Users can book a calling service for a loved one.

Project Structure
public/index.html - Main landing page with service listing and authentication
public/dashboard.html - User dashboard
public/admin/index.html - Admin dashboard
public/css/style.css - Styling for the entire application
public/js/app.js - Frontend functionality for the main application
public/js/dashboard.js - User dashboard functionality
public/admin/js/admin.js - Admin dashboard functionality

Backend:
config/database.php - Database configuration
config/jwt.php - JWT authentication configuration
api/index.php - Main API entry point
api/auth.php - Authentication endpoints
database/schema.sql - Database schema
Features Implemented:
User authentication (login/register)
Service listing and booking
Payment integration (Paystack and Crypto)
User profile management
Wallet system
Admin dashboard with CRUD operations
Booking management
Transaction tracking
Security Features:
JWT authentication
Password hashing
Input validation
Role-based access control

