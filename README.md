# 🍴 Zosh-Food Delivery

[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/username/Zosh-Food-Delivery/blob/main/LICENSE)
[![Java](https://img.shields.io/badge/Java-17-orange)](https://www.oracle.com/java/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3-brightgreen)](https://spring.io/projects/spring-boot)
[![React](https://img.shields.io/badge/React-18-blue)](https://react.dev/)
[![MySQL](https://img.shields.io/badge/MySQL-8-blue)](https://www.mysql.com/)
[![JWT](https://img.shields.io/badge/Auth-JWT-purple)](https://jwt.io/)

Zosh Food is a full-stack online food delivery application that connects restaurants and customers through a modern and user-friendly platform. It allows restaurant owners to register, manage menus, and handle orders, while customers can browse food items, add them to cart, and place orders easily. The system ensures secure data management, efficient order processing, and a seamless user experience using modern web technologies.

## 📸 Screenshots

### Customer Interface
![Home Page](https://github.com/pankajkumarsahpk/Zosh-Food/blob/e3a06ae634bff754c991d7220ce8d08541647ceb/home.jpeg?raw=true)
*Beautiful landing page with hero section and call-to-action*

![Menu Categories](https://github.com/shubheshkumar0/GrabitGo-Food-Delivery-Web-App/blob/main/Screenshot%202026-01-21%20165805.png?raw=true)
*Explore diverse menu categories and discover top dishes near you*


### Admin Dashboard
![Order Management](https://github.com/pankajkumarsahpk/Zosh-Food/blob/e3a06ae634bff754c991d7220ce8d08541647ceb/admin.jpeg?raw=true)
*Real-time order tracking and management dashboard*

## ✨ Key Features

**Multi-restaurant Support:** Enables multiple restaurants to register, manage their menus, and offer a wide variety of food options, giving customers more choices in one platform.

**Admin Dashboard:** Provides dedicated admin panels for managing food items, customer orders, and restaurant data efficiently, ensuring smooth platform operations.

**Secure Authentication:** Implements strong security with password hashing and protected login systems to ensure safe and secure user and admin access.

**Role-based Access Control:** Supports different access levels for customers and administrators, ensuring proper authorization and secure management of the system.

**User-friendly Interface:** Includes essential features such as Add to Cart, Remove from Cart, and easy food browsing to enhance the overall user experience.

**Responsive Design:** Fully optimized for desktop, tablet, and mobile devices to provide a consistent and seamless experience across all screen sizes.

**Efficient Order Management:** Allows users to place and track orders while enabling administrators to update and manage order status in real time.

**High Performance Architecture:** Built using modern full-stack technologies to ensure scalability, reliability, and fast application performance.

## 📁 Project Structure

Zosh-Food/
├── frontend/ # React frontend
│ ├── public/
│ └── src/
│ ├── components/ # Reusable UI components
│ ├── pages/ # Application pages (Home, Login, Cart, etc.)
│ ├── redux/ # State management using Redux
│ ├── router/ # React Router configuration
│ ├── services/ # API service calls
│ └── App.js # Main React component
│
├── backend/ # Spring Boot backend
│ ├── src/main/java/com/zoshfood/
│ │ ├── controller/ # REST controllers
│ │ ├── service/ # Business logic
│ │ ├── repository/ # Database repositories (JPA)
│ │ ├── model/ # Entity classes
│ │ ├── config/ # Security and JWT configuration
│ │ └── ZoshFoodApplication.java
│ │
│ └── src/main/resources/
│ ├── application.properties # Database and app configuration
│
├── database/ # MySQL database scripts (optional)
├── README.md
└── pom.xml # Maven dependencies for Spring Boot

## 🛠️ Tech Stack

**Frontend:**
- React.js 18
- Material UI (MUI)
- Tailwind CSS
- Redux (State Management)
- React Router DOM
- Axios

**Backend:**
- Spring Boot 3
- Spring Security
- JWT Authentication
- RESTful API
- Maven

**Database:**
- MySQL
- Spring Data JPA (Hibernate)

**Security:**
- JWT (JSON Web Token)
- Spring Security
- Password Encryption (BCrypt)

**Tools & Technologies:**
- Git & GitHub
- VS Code
- IntelliJ IDEA
- Postman (API Testing)



