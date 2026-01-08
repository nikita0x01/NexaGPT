# NexaGPT 

NexaGPT is a **full-stack conversational AI application** powered by GPT-based APIs. It enables users to interact with an intelligent chatbot through a secure and scalable backend built with **Node.js and Express**, and a modern frontend using **React + Vite**.

This repository focuses primarily on the **backend architecture**, including authentication, API routes, and database integration.

---

##  Project Overview

NexaGPT provides conversational AI functionality with secure user authentication and personalized settings. The backend exposes RESTful APIs that manage users, chat sessions, and preferences while integrating seamlessly with the frontend.

---

##  Features

- **JWT Authentication**
  - Secure user registration and login
  - Token-based session management

- **Chat API**
  - GPT-based conversational responses
  - Chat history storage

- **Dark / Light Theme Support**
  - User-specific theme preferences stored in the database

- **RESTful API Architecture**
  - Modular and scalable route handling

- **CI/CD Pipeline**
  - Automated testing and deployment using GitHub Actions

---

##  Technologies Used

### Backend
- **Node.js** – JavaScript runtime
- **Express.js** – REST API framework
- **JWT (JSON Web Tokens)** – Authentication & authorization
- **MongoDB** – Database for users and chat history

### Frontend
- **React** – UI library
- **Vite** – Fast build tool with HMR

### DevOps
- **GitHub Actions** – CI/CD automation

---

##  Authentication (JWT)

### Registration
**POST** `/api/auth/register`  
Registers a new user with username and password.

**Response:**  
- Success message  
- Validation errors (if any)

---

### Login
**POST** `/api/auth/login`

**Request Body:**
```json
{
  "username": "user",
  "password": "password"
}

```
## CI/CD Pipeline
-Automated build and testing
-Continuous deployment using GitHub Actions
-Ensures code quality and reliable deployments

##  Project Screenshots

### NexaGPT Interface
![NexaGPT Interface](https://github.com/user-attachments/assets/6a950743-ef81-474e-81e8-410ef13a9bff)

### Chat Interface
![Chat Interface](https://github.com/user-attachments/assets/c1400651-8c96-4990-9480-ab8c4ba1b03f)

### Theme Toggle
![Theme Toggle](https://github.com/user-attachments/assets/2df668b9-0d5c-4c56-9d3e-7061ad507efa)

### Login / Signup Page
![Login / Signup Page](https://github.com/user-attachments/assets/d1e16874-fff2-4dd2-bee4-c560af72f75f)

