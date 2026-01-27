# Java Web Application with CI/CD Pipeline (JSP & Maven)

This project is a **Java-based web application** developed using **JSP, Servlets, and Maven**, featuring a **user authentication system** (login, registration, logout) and configured for **CI/CD deployment** using build and deployment scripts.

The application demonstrates **Java web development fundamentals** along with **DevOps CI/CD concepts**, making it suitable for learning and interview demonstration.

---

## 🎯 Project Objective

The objective of this project is to:

- Build a Java web application using JSP
- Implement user authentication functionality
- Understand Java web application folder structure
- Use Maven for dependency management and build
- Configure CI/CD pipeline using YAML and shell scripts
- Prepare a deployment-ready Java application

---

## 🚀 Application Features

### 🔐 User Authentication
- User Registration
- User Login
- Logout functionality
- Welcome page after successful login
- Success page on registration

### 🖥️ Frontend
- JSP pages for UI
- Form-based input handling
- Navigation between pages

### ⚙️ Backend
- Java Servlets (controller logic)
- JSP for view rendering
- Maven-based project structure

### 🔄 CI/CD & DevOps
- `buildspec.yml` for build automation
- `appspec.yml` for deployment
- Shell script for installation (`install.sh`)
- Ready for AWS CodeBuild & CodeDeploy

---

## 🛠️ Technology Stack

| Layer | Technology |
|-----|-----------|
| Language | Java |
| Web Technology | JSP, Servlets |
| Build Tool | Maven |
| Frontend | JSP, HTML |
| CI/CD | AWS CodeBuild, CodeDeploy |
| Server | Apache Tomcat |
| OS | Linux / Windows |

---

## 🏗️ Project Architecture

This application follows the **MVC architecture**:

- **Model** → Java classes (business logic)
- **View** → JSP files
- **Controller** → Servlets handling requests

---

## 📁 Project Structure (Explained)

```text
Java-Application/
│
├── src/main/webapp/          # Web application root
│   ├── WEB-INF/              # Protected resources
│   ├── index.jsp             # Login page
│   ├── register.jsp          # Registration page
│   ├── userRegistration.jsp  # User registration handler
│   ├── success.jsp           # Registration success page
│   ├── welcome.jsp           # Welcome page
│   └── logout.jsp            # Logout page
│
├── appspec.yml               # AWS CodeDeploy configuration
├── buildspec.yml             # Build instructions for CI
├── install.sh                # Deployment shell script
├── pom.xml                   # Maven configuration file
└── README.md
