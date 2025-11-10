# Scalable-REST-API-with-JWT-Authentication-and-Role-Based-Access-with-React-Frontend
This project implements a secure, scalable REST API with JWT authentication and role-based access control. Users can register, log in, and perform CRUD operations on tasks. A simple React frontend interacts with the API, demonstrating authentication, protected routes, and task management functionality.

# Secure Task Management System

A **secure, scalable REST API** with JWT authentication and role-based access control, paired with a simple React frontend for demonstration. Users can register, log in, and perform CRUD operations on tasks.

## Features

### Backend
- User registration & login with **password hashing** (bcrypt)
- **JWT-based authentication**
- **Role-based access control** (`user` vs `admin`)
- CRUD APIs for tasks
- API versioning (`/api/v1`)
- Input validation & error handling
- MongoDB database

### Frontend
- React.js UI
- User registration & login forms
- Protected dashboard (JWT required)
- CRUD interface for tasks
- Displays API success/error messages

### Security & Scalability
- Secure JWT token handling
- Input sanitization & validation
- Modular project structure for scalability
- Optional: can be extended with Docker, Redis caching, or logging

