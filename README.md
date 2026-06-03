# AidConnect---Disaster-Resource-and-Relief-Management-System
AidConnect - Disaster Resource and Relief Management System
A comprehensive web-based system for managing disaster relief operations, connecting volunteers, and coordinating resources during emergencies.

Features
User Management
Common Users: Can request relief assistance from disaster zones
Volunteers: Can register, view assignments, and update status
Managers: Manage relief centers and coordinate local operations
Admins: Control system-wide requests and user management
Core Functionality
Disaster zone relief request system
Volunteer management and assignment
Resource tracking and donation management
Analytics dashboard with real-time statistics
Multi-level authentication and authorization
Technology Stack
Frontend: HTML5, CSS3, JavaScript
Backend: PHP 8.0+
Database: MySQL 8.0+
Additional: Bootstrap 5, Chart.js for analytics
Setup Instructions
Database Setup

CREATE DATABASE aidconnect;
USE aidconnect;
Import Database Schema

Run the SQL commands in database/schema.sql
Import sample data from database/sample_data.sql
Configure Database Connection

Update config/database.sample.php with your MySQL credentials
Web Server Configuration

Place files in your web server directory (e.g., htdocs for XAMPP)
Ensure PHP and MySQL are running
Access the System

Navigate to index.php in your browser
Default admin credentials: admin@aidconnect.com / admin123
Directory Structure
aidconnect/
├── assets/          # CSS, JS, images
├── config/          # Database and configuration files
├── database/        # SQL schema and sample data
├── includes/        # PHP includes and functions
├── pages/           # Main application pages
├── uploads/         # File uploads
└── index.php        # Main entry point
Default Users
Admin: admin@aidconnect.com / admin123
Manager: manager@aidconnect.com / manager123
Volunteer: volunteer@aidconnect.com / volunteer123
User: user@aidconnect.com / user123
Security Features
Password hashing with bcrypt
Session management
SQL injection prevention
XSS protection
Role-based access control
License
This project is created for educational and demonstration purposes.
