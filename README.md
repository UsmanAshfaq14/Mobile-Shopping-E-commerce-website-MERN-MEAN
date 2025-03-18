# MERN Stack Shopping Cart

## Overview

The **MERN Stack Shopping Cart** is a full-featured e-commerce application built using the **MERN** (MongoDB, Express, React, Node.js) stack. It follows RESTful API design principles and provides a seamless shopping experience with a modern, responsive UI.

The front-end is developed using **Material-UI** with **Redux** for state management, while the back-end is powered by **Node.js & Express**, with **MongoDB** as the database. The application supports **Docker**, enabling easy deployment and scalability.

---

## Features

- 🛍 **Product Catalog** – Browse and view all available products.
- 🔐 **User Authentication** – Secure registration and login system.
- 🛒 **Shopping Cart** – Add, remove, and manage products in your cart.
- ✅ **Order Processing** – Complete purchases and manage orders.
- 📦 **RESTful API** – Well-structured API for seamless front-end and back-end communication.
- 🌐 **Responsive UI** – Built with Material-UI for a modern, adaptive interface.
- 🛠 **Docker Support** – Easily deployable with containerized architecture.

---

![image](https://github.com/user-attachments/assets/c3a43fdc-3ab7-4575-a513-54833ce20a58)


## 🛠 Technology Stack

### **Frontend:**
- **React.js** – Front-end framework
- **Redux** – State management
- **Redux-Saga** – Handling side effects
- **Material-UI** – UI components
- **TypeScript** – Strongly-typed JavaScript
- **Webpack** – Module bundler

### **Backend:**
- **Node.js** – JavaScript runtime
- **Express.js** – Web framework for API
- **MongoDB** – NoSQL database
- **Mongoose** – ODM for MongoDB

### **Deployment & DevOps:**
- **Docker** – Containerized deployment
- **Docker Compose** – Multi-container setup

---

## 🚀 Installation & Setup

### **Requirements**
- **Docker** (recommended)  
  OR  
- **Node.js** installed  
- **MongoDB** running locally  

### **Steps to Run the Application**

#### 1️⃣ Clone the repository:

```sh
git clone https://github.com/ivan3123708/fullstack-shopping-cart.git
```

#### 2️⃣ Navigate to the project directory:

```sh
cd fullstack-shopping-cart
```

#### 3️⃣ Run the application using Docker:

```sh
docker-compose up -d
```

This will start three containers for:
- **Frontend** (React) – Runs on `http://localhost:3000`
- **Backend** (Express) – Runs on `http://localhost:5000`
- **Database** (MongoDB) – Runs on `port 27017`

Visit `http://localhost:3000` to access the application.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## ⭐ Contributions & Support

If you find this project useful, feel free to **star ⭐ this repository**. Contributions and feedback are always welcome!
