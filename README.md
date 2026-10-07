# Campus Complaint & Issue Management System

Full-stack SDE project for managing campus issues.

Tech Stack:
- Backend: Python (Flask)
- Database: MySQL
- Frontend: React

Features:
- Complaint submission
- Admin tracking
- Status & priority handling
🏫 Campus Complaint Management System
📌 Project Overview

The Campus Complaint Management System is a full-stack web application designed to streamline the process of reporting, tracking, and resolving campus-related issues. The system provides a structured and transparent workflow where students can raise complaints and administrators can manage and resolve them efficiently.

This project focuses on backend development, REST API design, database modeling, and real-world system workflows, making it suitable for Software Development Engineer (SDE) roles.

🎯 Problem Statement

In many colleges, complaints related to academics, hostels, facilities, or administration are handled manually or through unstructured communication channels. This leads to:

Delayed resolution

Lack of tracking and accountability

Poor communication between students and administration

This system addresses these problems by providing a centralized digital platform for complaint management.

🛠️ Tech Stack

Backend: Python (Flask)

Database: MySQL

Frontend: React (planned / modular structure)

Tools: REST APIs, SQL, Git

✨ Key Features

Complaint Submission: Students can raise complaints with details such as category, priority, and description.

Complaint Tracking: Each complaint has a status (Open, In Progress, Resolved) for transparency.

Admin Management: Administrators can view, prioritize, and update complaint statuses.

Structured Database Design: Normalized MySQL schema to ensure data consistency and integrity.

Scalable Architecture: Clear separation of routes, models, and services for future expansion.

🧠 System Workflow

A student submits a complaint through the system.

The complaint is stored in the database with a default status of Open.

An admin reviews the complaint and updates the status to In Progress or Resolved.

The system maintains a complete record of complaints for monitoring and analysis.

🗄️ Database Design

The database includes:

Users Table: Stores student and admin details with role-based identification.

Complaints Table: Stores complaint details such as title, category, priority, status, and timestamps.

This design ensures efficient querying and easy scalability.
