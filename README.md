# 👥 User Management Platform

<p align="center">
A production-ready full-stack user management platform designed to explore authentication, authorization, account management, testing, and modern deployment workflows.
</p>

---

## About The Project

I built this project to gain hands-on experience designing secure user management systems similar to those found in modern SaaS platforms.

The application provides user authentication, role-based access control, profile management, administrative user operations, automated testing, Dockerized environments, and CI/CD automation.

Beyond basic CRUD functionality, the project focuses on production-grade engineering practices including security, scalability, deployment automation, testing, and maintainable architecture.

---

## Features

### 🔐 Authentication

* User Registration
* User Login
* JWT Authentication
* Password Hashing with bcrypt
* Protected Routes

### 👤 User Management

* Profile Management
* Update Personal Information
* Account Ownership Controls
* Secure User Access

### 🛡️ Role-Based Access Control

* User Roles
* Admin Privileges
* Protected Administrative Operations
* Access Restriction Middleware

### ⚙️ Admin Capabilities

* View Users
* Manage User Accounts
* Role Administration
* User Status Management

### 🧪 Quality & Reliability

* Unit Testing
* Integration Testing
* API Validation
* Automated Test Coverage

### 🚀 DevOps & Deployment

* Docker Support
* Docker Compose
* GitHub Actions CI
* Automated Deployments
* Production Environment Configuration

---

## Tech Stack

### Backend

* Node.js
* Express.js
* MongoDB Atlas
* Mongoose
* JWT
* bcrypt

### Frontend

* React
* Vite
* React Router
* Axios
* Context API

### Testing

* Jest
* Supertest

### DevOps

* Docker
* Docker Compose
* GitHub Actions

### Deployment

* Render
* Netlify

---

## Project Structure

```text
user-management-platform
├── backend
│   ├── src
│   │   ├── controllers
│   │   ├── middleware
│   │   ├── models
│   │   ├── routes
│   │   ├── utils
│   │   ├── app.js
│   │   └── server.js
│   ├── tests
│   ├── Dockerfile
│   ├── package.json
│   └── .env.example
│
├── frontend
│   ├── src
│   ├── netlify.toml
│   └── package.json
│
├── docker-compose.yml
└── README.md
```

---

## Core Functionality

### Authentication System

* Secure signup workflow
* Login functionality
* JWT token generation
* Protected API access

### User Profiles

* View profile information
* Update profile details
* Account ownership enforcement

### Administrative Controls

* User management dashboard
* Role assignment
* User monitoring

### Security Features

* Password hashing
* Access control middleware
* Route protection
* Request validation

---

## Installation

### Clone Repository

```bash
git clone <repository-url>

cd user-management-platform
```

### Backend Setup

```bash
cd backend

npm install

cp .env.example .env

npm run dev
```

Backend runs at:

```text
http://localhost:5000/api
```

### Frontend Setup

```bash
cd frontend

npm install

npm run dev
```

Frontend runs at:

```text
http://localhost:5173
```

---

## Running Tests

```bash
cd backend

npm test
```

---

## Docker Setup

```bash
docker compose up --build
```

---

## Sample API Endpoints

| Method | Endpoint         | Description           |
| ------ | ---------------- | --------------------- |
| POST   | /api/auth/signup | Register User         |
| POST   | /api/auth/login  | Login User            |
| GET    | /api/users/me    | Get Profile           |
| PATCH  | /api/users/me    | Update Profile        |
| GET    | /api/users       | Admin User Management |

---

## Deployment

### Frontend

Netlify

### Backend

Render

### Health Check

```text
/healthz
```

---

## Engineering Concepts Demonstrated

* Authentication & Authorization
* JWT Security
* Role-Based Access Control
* REST API Development
* MongoDB Data Modeling
* Frontend-Backend Integration
* Automated Testing
* CI/CD Pipelines
* Docker Containerization
* Production Deployment

---

## Future Improvements

* Email Verification
* Password Reset Flow
* OAuth Authentication
* Audit Logging
* Account Activity Tracking
* Multi-Factor Authentication
* User Analytics Dashboard

---

## Learning Outcomes

This project helped me gain practical experience with:

* Building secure authentication systems
* Implementing RBAC architectures
* Writing automated backend tests
* Dockerizing applications
* Creating CI/CD workflows
* Deploying full-stack applications

---

## Author

**Vamshi Kumar**

Software Developer | Backend Engineer | Full-Stack Developer

LinkedIn: https://www.linkedin.com/in/bodavamshikumar

---

## License

MIT License

