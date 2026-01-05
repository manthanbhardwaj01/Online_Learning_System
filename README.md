# Online Learning Management System (LMS)
## 3rd Semester SCSE – Live Project

## Project Overview
The Online Learning Management System (LMS) is a Java-based application designed to manage online courses using role-based access control. The system supports three user roles: Admin, Instructor, and Student, each with a dedicated dashboard and defined functionalities. The project demonstrates modular design, proper integration of components, data validation, and clean implementation of a real-world academic system.

## System Working
1. Authentication & Role Management: Admin creates user accounts and assigns roles. Secure login enforces role-based access to dashboards.
2. Admin Workflow: Manage users and courses, configure system settings, and monitor performance analytics and system activity.
3. Instructor Workflow: Create and manage courses, create assignments, evaluate submissions, and track student performance.
4. Student Workflow: Enroll in courses, access learning materials, submit assignments, and track progress and grades.

## User Roles & Functionalities
Admin: User Management, Course Management, Performance Analytics, System Settings  
Instructor: Course Creation, Assignment Grading, Student Performance Monitoring  
Student: Course Enrollment, Material Access, Assignment Submission, Progress Tracking  

## Project Structure
LMS/
├── src/
│   ├── admin/          # Admin module logic
│   ├── instructor/     # Instructor module logic
│   ├── student/        # Student module logic
│   ├── database/       # Database connectivity
│   ├── validation/     # Input validation & error handling
│   └── ui/             # GUI components
├── docs/
│   └── project_report.pdf
└── README.md

## Student Contribution Details
Student Name: Manthan
Admission Number: 24SCSE1410173
Primary Module Ownership: Admin Module & Backend Core  
Secondary Contributions: System integration  

Student Name: Ayush rai
Admission Number: 24SCSE1180055
Primary Module Ownership: Instructor Module & Database  
Secondary Contributions: Validation & grading.
Primary Module Ownership: Student Module & UI Design  
Secondary Contributions: Documentation & testing  

Each student had full ownership of one core module and contributed to supporting components to ensure complete system integration.

## Validation & Error Handling
All user inputs are validated before processing. Role-based access prevents unauthorized actions. Proper error messages are displayed for invalid operations, and the system handles failures without crashing.

## How to Run the Project
Clone the repository, open it in a Java IDE (Eclipse, IntelliJ, or NetBeans), configure database settings if required, and run the main application file.

## Documentation
Project documentation is included in the docs folder. The code is modular, readable, and commented. This README explains the system structure and individual contributions clearly.

© 2024 GUVI Geek Network Pvt. Ltd. All rights reserved. No part of this project may be reproduced or distributed without prior written permission.
