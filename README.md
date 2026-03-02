# OTP Authentication Fullstack Assignment

This project is a fullstack OTP-based authentication system built using **NestJS (Backend)** and **Next.js (Frontend)**.

## 🚀 Tech Stack

### Backend

* NestJS
* Fastify
* TypeScript
* PostgreSQL
* TypeORM
* JWT Authentication

### Frontend

* Next.js
* TypeScript
* React Query
* Axios
* React Hook Form
* Yup
* shadcn/ui

---

## 📂 Project Structure

```
otp-auth-fullstack
│
├── backend    # NestJS API
└── frontend   # Next.js App
```

---

## 🔐 Features

### Authentication

* Send OTP (Hardcoded OTP: 123456)
* Verify OTP
* JWT-based login
* Session management
* Logout

### Company Management

* Get companies list
* Create company

---

## ⚙️ Backend Setup

```bash
cd backend
npm install
npm run start:dev
```

Backend will run on:

```
http://localhost:4000
```

---

## 💻 Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Frontend will run on:

```
http://localhost:3000
```

---

## 🔑 Test Credentials

OTP is hardcoded:

```
123456
```

Use any phone number.

---

## 📬 API Endpoints

### Auth

* POST /auth/send-otp
* POST /auth/verify-otp
* POST /auth/logout

### Companies

* GET /companies
* POST /companies

---

## ✅ Assignment Requirements Covered

* JWT Authentication
* Session Management
* Protected Routes
* CRUD Operations (Create & Read)
* Clean Architecture
* Validation & Error Handling

---

## 👨‍💻 Author

Vikas
