# Employee Attendance System

An advanced Employee Attendance Management System using GPS technology for retail employees working at various store branches. This application enables employees to manage their work schedules and ensures attendance can only be marked at designated work locations. The system features multiple user roles, including Super Admin, Admin, Supplier, and SPG.

## Project Structure

### Mobile Application

- **Framework**: React Native
- **Purpose**: Provides mobile access for employees to manage work schedules and mark attendance at their respective branches using GPS validation.

### Frontend Dashboard

- **Framework**: React.js with Material UI
- **Purpose**: Provides a web interface for Super Admin, Admin, and Supplier roles to manage attendance data, schedules, and employee assignments.

### Backend API

- **Framework**: Express.js
- **Language**: TypeScript
- **Purpose**: Serves as the backend API for handling business logic, user authentication, role-based access control, and integration with GPS services for location validation.

## Key Features

1. **Role Management**

   - **Super Admin**: Manages system-wide configurations, users, and branches.
   - **Admin**: Manages branch-specific employees, schedules, and attendance.
   - **Supplier**: Oversees specific operations related to supplier management.
   - **Employee**: Uses the mobile app to manage their schedules and attendance.

2. **GPS-based Attendance**  
   Employees can mark attendance only when they are physically present at their designated branch, verified via GPS, and can register on only one device.

3. **Work Schedule Management**

   - Employees can view and manage their work schedules through the mobile application.
   - Admins can assign schedules to employees from the dashboard.

4. **Branch Management**  
   Super Admins and Admins can manage branch details, including geolocation for attendance validation.

5. **Real-time Notifications**  
   Employees receive notifications regarding work schedule updates or attendance reminders.

6. **Reporting and Analytics**  
   Dashboard provides analytics on attendance patterns, schedule adherence, and branch performance.

## Tech Stack

### 1. Frontend Dashboard

- **Framework**: React.js
- **UI Library**: Material UI
- **State Management**: Context API
- **Libraries**: React Router, Axios

### 2. Backend API

- **Framework**: Express.js
- **Language**: TypeScript
- **Database**: MySQL with Sequelize ORM
- **Authentication**: JSON Web Tokens (JWT)


# Quick Start Guide

### Web Application
Access the web dashboard:  
<a href="https://sistem-absensi-dashboard.web.app" target="_blank">https://sistem-absensi-dashboard.web.app</a>

## Login
- **Username**: `superadmin`  
- **Password**: `qwerty`

Frontend:  
<a href="https://sistem-absensi-demo.web.app/" target="_blank">https://sistem-absensi-demo.web.app</a>

## Login
- **Username**: `superadmin`  
- **Password**: `qwerty`

## User Registration
To log in as a user, registration is required. During registration, the application automatically captures the device ID to bind the account to a specific device. This ensures security and prevents manipulation since the system uses device IDs instead of IMEI numbers.

## Features
1. **Super Admin Login**  
   Access and manage system-wide settings using the provided super admin credentials.

2. **User Registration and Device Binding**  
   - Users must register to create an account.  
   - Registration automatically binds the account to the user's device using the device ID.

3. **Platform Access**  
   - **Dashboard**: Manage attendance data, schedules, and employee details through the web application.  
   - **Frontend**: Employees can mark attendance and manage schedules.

## Notes
- Ensure that the device used for registration is the one intended for system access, as the account is tied to the device ID.  
- For any issues or support, contact the development team.

Enjoy using the Employee Attendance System!
