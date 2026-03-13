# Smart Web-Based Attendance & Machinery Management System

A comprehensive web-based attendance and workforce management system designed to help organizations efficiently track staff attendance, manage equipment, and generate operational reports.

This system provides real-time monitoring of staff activities, attendance logging, machinery inventory tracking, and administrative analytics through an intuitive dashboard.

## 🚀 Tech Stack

Frontend
- React.js
- Axios
- TailwindCSS / Material UI (optional)

Backend
- Django
- Django REST Framework

Database
- MongoDB

DevOps & Infrastructure
- Docker
- Docker Compose
- Git & GitHub
- CI/CD Ready

## ✨ Key Features

### User & Authentication
- Secure user authentication
- Role-based access control (Admin & Staff)
- JWT authentication

### Staff Attendance
- Check-in / Check-out system
- Attendance history tracking
- Real-time attendance monitoring
- Daily, weekly, and monthly logs

### Machinery & Equipment Management
- Equipment registration
- Equipment assignment to staff
- Maintenance tracking
- Usage history

### Dashboard & Reports
- Admin analytics dashboard
- Staff attendance reports
- Equipment usage reports
- Exportable data (CSV / PDF)

### Notifications
- Real-time alerts
- Activity updates

## 📊 System Architecture

Frontend (React)
⬇ API Requests
Backend (Django REST API)
⬇
MongoDB Database

All services are containerized using Docker for easy deployment and scalability.

## 🐳 Docker Support

The project supports containerized deployment using Docker.

Services:
- React Frontend
- Django Backend
- MongoDB Database

Run the project easily using:

```bash
docker-compose up --build