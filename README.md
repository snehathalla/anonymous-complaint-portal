# Ragging Complaint Management System

A web-based complaint tracking and management system designed to handle and monitor ragging complaints.

## Features

- **User Complaint Submission**: Users can submit complaints through the system
- **Complaint Tracking**: Track the status of submitted complaints
- **Admin Dashboard**: Administrative panel for managing and reviewing complaints
- **Admin Authentication**: Secure login system for administrators
- **Complaint Management**: Update and delete complaint records
- **Admin Reset**: Password reset functionality for administrative accounts

## File Structure

- `index.php` - Homepage/landing page
- `submit.php` - Complaint submission form and processing
- `complaint.php` - Complaint viewing and management
- `track.php` - Complaint tracking interface
- `admin-login.php` - Admin login page
- `admin.php` - Admin dashboard
- `update.php` - Update complaint details
- `delete.php` - Delete complaints
- `reset_admin.php` - Admin password reset
- `logout.php` - User/admin logout
- `config.php` - Database configuration and connection

## Installation

1. Clone or download the project to your web server directory
2. Configure your database settings in `config.php`
3. Create the necessary database tables
4. Access the application through your web server

## Usage

### For Users
1. Navigate to the homepage (`index.php`)
2. Click on "Submit Complaint"
3. Fill in the complaint details
4. Use the tracking feature to monitor complaint status

### For Administrators
1. Access the admin login page (`admin-login.php`)
2. Log in with your credentials
3. View and manage complaints from the dashboard (`admin.php`)
4. Update complaint status or delete records as needed

## Requirements

- PHP 5.6+
- MySQL/MariaDB database
- Web server (Apache, Nginx, etc.)

## License

This project is provided as-is for educational purposes.
