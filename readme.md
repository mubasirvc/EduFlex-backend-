﻿# EduFlex Backend

The backend API for the EduFlex Online Learning App is built using **Express.js** and **Node.js**, providing functionality for user management, course handling, and more.

---

## Features

### User Management

- **Admin:** Manage users, approve tutors, and oversee the platform.
- **Tutor:** Register with documents, upload video lessons upon approval.
- **End User:** Sign up, purchase courses, and track progress.

### Course Management

- Upload, update, and manage courses and lessons.
- Secure payment integration for course purchases.

### Communication

- Real-time communication using **Socket.IO** for chat and notifications.
- Email notifications using **Nodemailer** for updates and approvals.

### Security

- Authentication and authorization with **JWT**.
- Input validation using **Joi**.

---

## Tech Stack

- **Node.js**: Runtime for building the server-side application.
- **Express.js**: Framework for creating robust backend APIs.
- **MongoDB**: Database for efficient data management.
- **Mongoose**: ORM for schema-based modeling and interaction with MongoDB.
- **Socket.IO**: Enables real-time chat and notifications.
- **Nodemailer**: Handles email notifications.
- **JWT**: Secures routes through authentication.

---

## Project Structure

backend
│
├── src
│ ├── controllers # Route handlers
│ ├── models # Mongoose schemas
│ ├── middlewares # Authentication and validation
│ ├── routes # API route definitions
│ ├── utils # Helper functions
│ ├── config # Environment and database configurations
│ └── server.js # Entry point
│
├── public # Static assets (if any)
└── README.md # Documentation

---

## Setup Instructions

### Prerequisites

- **Node.js >= 16.x**
- **MongoDB**
- **npm or yarn**

### **Installation**

1.  Clone the repository:

    ```bash
    git clone git@github.com:mubasirvc/EduFlex-backend-.git

    ```

2.  Setup environment variables:
    Create a .env file in the root directory with the following:
    ```bash
    PORT=5000
    MONGO_URL=<your-mongodb-url>
    JWT_SECRET=<your-jwt-secret>
    NODE_ENV = <your-node-env>
    key_id = <your-razorpay-key-id>
    key_secret = <your-razorpay-key_secret>

3.  Install dependencies:

    ```bash
    npm install

    ```

4.  Start the development server:

    ```bash
    npm start

    ```

5.  Open your browser and navigate to http://localhost:4000:

## **Contact**

**Mubasir VC**  
[Portfolio](https://my-portfolio-ten-sand-14.vercel.app/) | [LinkedIn](https://www.linkedin.com/in/mubasir-vc/)
