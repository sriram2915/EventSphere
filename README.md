# EventSphere

**EventSphere** is a full-stack event management application built with **React (Vite)** on the frontend, **Node.js + Express** on the backend, and **MySQL** as the database. It provides user role-based dashboards (Admin, Faculty, Student) for managing events, user accounts, and registrations.

---

## 📂 Project Structure

```
EventSphere/
├── client/                 # Frontend (React + Vite)
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── contexts/       # Auth context
│   │   ├── pages/          # Page components (Dashboard, Login, etc.)
│   │   ├── App.jsx         # Main App component
│   │   └── main.jsx        # React entry point
│   └── package.json        # Frontend dependencies
│
├── server/                 # Backend (Node.js + Express)
│   ├── models/             # Sequelize models (User, Event)
│   ├── routes/             # API routes
│   ├── controllers/        # Request handling logic
│   ├── config/             # Database connection settings
│   ├── server.js           # Backend entry point
│   └── package.json        # Backend dependencies
│
└── README.md               # Project documentation
```

---

## 🚀 Tech Stack

**Frontend:**

* React + Vite
* TailwindCSS
* Axios (API calls)
* React Router DOM

**Backend:**

* Node.js
* Express.js
* Sequelize ORM
* bcrypt (Password hashing)
* jsonwebtoken (JWT authentication)

**Database:**

* MySQL

---

## 🔑 Features

* **Role-based authentication** (Admin, Faculty, Student)
* Admin: Manage all events and users
* Faculty: Create and manage own events
* Student: View and register for events
* Secure authentication using JWT and hashed passwords
* RESTful API integration

---

## 📦 Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/EventSphere.git
cd EventSphere
```

### 2️⃣ Setup Backend

```bash
cd server
npm install
# Configure .env for DB connection
npm run dev
```

### 3️⃣ Setup Frontend

```bash
cd ../client
npm install
npm run dev
```

---

## 🗝️ Environment Variables

**Backend `.env`**

```
DB_HOST=localhost
DB_USER=root
DB_PASS=yourpassword
DB_NAME=eventsphere
JWT_SECRET=your_secret_key
```

---

## 📌 Usage

* **Admin Dashboard**: Manage events & users
* **Faculty Dashboard**: Create & edit events
* **Student Dashboard**: Browse & register for events

---

