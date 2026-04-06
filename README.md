# 🏡 Airbnb Clone Using MERN

## 📌 Project Description

The **Airbnb Clone Using MERN** is a full-stack web application developed using the **MERN stack (MongoDB, Express.js, React.js, Node.js)**.
This project replicates the core functionalities of the Airbnb platform, allowing users to browse properties, view details, and manage listings.

The application demonstrates real-world full-stack development concepts including REST APIs, authentication, database management, and responsive UI design.

---

## 🚀 Features

* User Registration and Login
* Property Listing Management
* Browse Available Properties
* View Property Details
* Add / Edit / Delete Listings
* Search and Filter Properties
* Responsive User Interface
* RESTful API Integration
* MongoDB Database Storage

---

## 🛠️ Technology Stack

### Frontend

* React.js
* HTML5
* CSS3
* JavaScript
* Bootstrap / Tailwind CSS

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### Tools & Platforms

* Visual Studio Code
* Postman
* Git
* GitHub
* npm
---

## ⚙️ Installation and Setup

### Step 1 — Clone the Repository

```
git clone https://github.com/satish4397/Airbnb_Clone_Using_MERN.git
```

### Step 2 — Navigate to Project Directory

```
cd Airbnb_Clone_Using_MERN
```

### Step 3 — Install Dependencies

For backend:

```
npm install
```

For frontend:

```
cd client
npm install
```

---

### Step 4 — Configure Environment Variables

Create a `.env` file in the root directory.

Example:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

---

### Step 5 — Run the Application

Start backend:

```
npm start
```

Start frontend:

```
cd client
npm start
```

---

## 🌐 Application URLs

Frontend:

```
http://localhost:3000
```

Backend API:

```
http://localhost:5000
```

---

## 📡 API Endpoints

### User Routes

```
POST /api/users/register
POST /api/users/login
GET /api/users/profile
```

### Property Routes

```
GET /api/properties
POST /api/properties
PUT /api/properties/:id
DELETE /api/properties/:id
```

---

## 🧪 Testing

You can test APIs using:

* Postman
* Thunder Client
* Browser

Example:

```
GET http://localhost:5000/api/properties
