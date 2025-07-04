# AMFLO
# 🕒 Attendance, Top-Up & Leave Management System

A full-stack web application to manage employee attendance, top-up requests, and leave approvals. The system provides detailed analytics, admin dashboards, and approval workflows.

---

## ⚙️ Tech Stack

**Backend:**
- Java 21
- Spring Boot 3.4.4
- JPA, Hibernate
- MySQL
- RESTful APIs
- Actuator (Health Monitoring)
- Logging (Spring Boot Logs)
- Json Web Tokens (JWT)
- Unit Testing with JUnit & Mockito

**Frontend:**
- React (with Vite)
- JavaScript
- HTML/CSS
- Recharts
- Bootstrap

---

## ✅ Features

- 👤 Employee login and attendance tracking (Check-in/Check-out)
- 📊 View weekly and monthly analytics using charts
- 👤 JWT-based authentication with secure login
- 🧑‍💼 Role-based dashboards: Admin & Employee views
- 📩 Submit Top-Up and Leave requests
- ✅ Admin dashboard to Approve/Reject requests
- 🔍 REST API support for extensibility
- 📈 Actuator endpoints for system health checks
- 🧪 Unit tested backend for reliability
- Compatible with VSCode and IntelliJ idea (Extension : spring boot dashboard usage is recommended)

---

## 🛠️ Project Setup

### 📌 Prerequisites

- Java 17 or above
- Node.js & npm
- MySQL Workbench (running locally)
- Maven
- Git

---

## 🚀 Backend Setup (Spring Boot)

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-repo/attendance-system.git
   cd attendance-system/backend

2. **Configure MySQL**
     Create a database, e.g., attendance_dbOpen
     MySQL Workbench and execute:
     ```sql
    CREATE DATABASE attendance_db;

3. **Update DB credentials in application.properties**
    ```properties
    spring.datasource.url=jdbc:mysql://localhost:3306/attendance_db
    spring.datasource.username=your_mysql_username
    spring.datasource.password=your_mysql_password

4. **Run the Spring Boot application**
     ```bash
    ./mvnw spring-boot:run

5. **Access actuator endpoint**
    ```bash
    http://localhost:8080/actuator/health
🌐 Frontend Setup (React + Vite)
1. *Navigate to frontend directory*

2. *Install Node modules*
    ```bash
    npm install

3. *Run the frontend*
    ```bash
    npm run dev
    
4. *Access the app*
    ```arduino
    http://localhost:5173
📊 Demo Snapshots
(Optional: Add screenshots of dashboard, check-in UI, admin approval UI, analytics charts etc.)

🔍 Testing
JUnit and Mockito are used for backend service and repository layer testing.

6. *Example command:*
   ```bash
    ./mvnw test
7. 📁 Project Structure
    ```adruino
    backend/
    ├── src/main/java/com/example
    ├── resources/application.properties
    └── ...
    frontend/
     ├── src/
     ├── public/
     └── vite.config.js
🧠 Future Enhancements
*Export reports (PDF/Excel)*
*Email notifications for request status*

🙌 Contributors
Aditya Jha (Backend + System Design)
