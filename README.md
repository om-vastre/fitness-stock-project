# 💪 Fitsta - Fitness Gym Management System

A comprehensive full-stack web application for managing gym operations, memberships, equipment, trainers, and customer engagement.

![React](https://img.shields.io/badge/React-18.2.0-61DAFB?logo=react)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.1.3-6DB33F?logo=springboot)
![Java](https://img.shields.io/badge/Java-17-ED8B00?logo=openjdk)
![MySQL](https://img.shields.io/badge/MySQL-Database-4479A1?logo=mysql)
![Docker](https://img.shields.io/badge/Docker-Containerized-2496ED?logo=docker)

## 🚀 Features

### 👤 Multi-Role Dashboard System
- **Admin Dashboard** - Complete gym management with CRUD operations for customers, trainers, equipment, memberships, and purchases
- **Trainer Dashboard** - Manage assigned members, track progress, and assign tasks
- **User Dashboard** - View membership status, track fitness progress, assigned tasks, and purchase history

### 🔐 Authentication & Security
- User registration with OTP verification via email
- Secure login/logout functionality
- Role-based access control (Admin, Trainer, User)

### 🏋️ Core Modules
- **Membership Management** - Create and manage membership plans with payment integration
- **Equipment Store** - Browse, view details, and purchase fitness equipment
- **Trainer Assignment** - Assign trainers to members for personalized guidance
- **Task Management** - Trainers can assign and track workout tasks for members
- **Progress Tracking** - Monitor member fitness progress over time
- **Email Notifications** - Automated OTP and notification emails via SMTP

### 💳 Payment Gateway
- Integrated payment processing for memberships and equipment purchases

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | React 18, React Router DOM, Axios, React Scroll |
| Backend | Java 17, Spring Boot 3.1.3, Spring Data JPA, Spring Mail |
| Database | MySQL |
| Build Tools | Maven, npm |
| Containerization | Docker |

## 📁 Project Structure

```
├── Frontend (React)
│   ├── src/
│   │   ├── api-client/       # API integration modules
│   │   ├── component/        # Reusable UI components (14 components)
│   │   ├── pages/            # Page components (12 pages)
│   │   ├── sections/         # Dashboard section components (10 sections)
│   │   ├── form/             # Form components (6 forms)
│   │   └── css/              # Styling files
│
├── Backend (Spring Boot)
│   ├── src/main/java/com/fitsta/
│   │   ├── controller/       # REST API controllers
│   │   ├── service/          # Business logic layer
│   │   ├── repository/       # Data access layer
│   │   └── model/            # Entity classes
│   └── pom.xml               # Maven dependencies
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v14+)
- Java 17
- MySQL Server
- Maven

### Frontend Setup
```bash
# Clone the repository
git clone https://github.com/soham-shinde/fitness-stock-project.git

# Navigate to project directory
cd fitness-stock-project

# Install dependencies
npm install

# Start development server
npm start
```

### Backend Setup
```bash
# Navigate to backend (api branch or Fitsta repo)
git checkout api

# Configure MySQL database in application.properties

# Build and run
mvn spring-boot:run
```

### Docker Deployment
```bash
# Build Docker image
docker build -t fitsta-api .

# Run container
docker run -p 8080:8080 fitsta-api
```

## 📸 Pages Overview

| Page | Description |
|------|-------------|
| Home | Landing page with gym information |
| Login/SignUp | Authentication with OTP verification |
| Admin Dashboard | Complete gym management interface |
| Trainer Dashboard | Member and task management |
| User Dashboard | Personal fitness tracking |
| Store | Equipment browsing and purchase |
| Payment Gateway | Secure payment processing |
| About Us | Gym information |
| Contact Us | Communication form |

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👥 Authors

- **Om Vastre** - Backend Development
- **Soham Shinde** - Frontend Development

---

⭐ Star this repository if you find it helpful! 
