# Saarthi Bank – Full Stack Banking Application

Saarthi Bank is a **full-stack banking application** built to demonstrate real-world backend and frontend development practices such as secure authentication, transaction handling, and clean separation of concerns.

The project is designed with a **frontend–backend architecture**, similar to industry-level applications, and is split into two independent repositories for better scalability and maintainability.

---

## 🧩 How Saarthi Bank Is Built

### Backend (Spring Boot)
The backend is responsible for all **business logic and security**, including:
- User authentication using JWT
- Secure REST APIs
- Account operations (deposit, withdraw, transfer)
- Transaction history management
- Database interaction using JPA/Hibernate

**Backend Repository**  
👉 https://github.com/Shivansh5906/saarthi-bank-backend

---

### Frontend (React)
The frontend provides the **user interface and user experience**, including:
- Authentication flow (login/signup)
- Account dashboard
- Transaction actions and history
- API integration with the backend using Axios
- Environment-based configuration for backend connectivity

**Frontend Repository**  
👉 https://github.com/Shivansh5906/saarthi-frontend

---

## 🏗 Architecture Overview

- Frontend and backend are maintained as **separate repositories**
- Communication happens via **REST APIs**
- Configuration is handled using **environment variables**
- Sensitive data is excluded from version control
- Project structure follows **industry best practices**



git clone https://github.com/Shivansh5906/saarthi-bank-backend
cd saarthi-bank-backend
