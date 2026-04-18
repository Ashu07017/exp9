# 🌐 Experiment 9: Frontend Integration with RBAC (React + Spring Boot)

## 📌 Overview

This experiment extends Experiment 8 by building a **React frontend** that interacts with the backend APIs and implements **role-based UI rendering** using JWT.

---

## 🎯 Objectives

* Build React frontend for authentication
* Integrate backend JWT APIs
* Implement role-based UI rendering
* Manage session using localStorage

---

## 🛠️ Tech Stack

* React.js
* Bootstrap / Material UI
* Axios
* JavaScript (ES6)
* Spring Boot (Backend)

---

## 📂 Project Structure

```
frontend/
│
├── components/
│   ├── Login.js
│   ├── Dashboard.js
│   ├── AdminPanel.js
│   └── UserPanel.js
│
├── services/
│   └── api.js
│
└── App.js
```

---

## 🔑 Features

* Login UI with JWT authentication
* Store token in localStorage
* Role-based dashboard rendering
* Protected routes
* Logout functionality

---

## 🔄 Flow

1. User logs in → receives JWT
2. Token stored in localStorage
3. Token sent in API requests
4. UI renders based on role

---

## ▶️ How to Run

### Backend

```
mvnw.cmd spring-boot:run
```

### Frontend

```
npm install
npm start
```

---

## 🔐 Role-Based UI

| Role  | Access                  |
| ----- | ----------------------- |
| USER  | Dashboard               |
| ADMIN | Admin Panel + Dashboard |

---

## 🧪 Testing

* Login with different roles
* Verify UI changes
* Check API authorization

---

## 📚 Learning Outcomes

* Connected frontend with secure backend
* Understood JWT flow in real apps
* Implemented RBAC in UI
* Learned API integration using Axios

---

## 🚀 Future Improvements

* Add refresh tokens
* Use Redux for state management
* Improve UI/UX animations
* Deploy full-stack app

---
