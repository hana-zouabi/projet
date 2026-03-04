📌 Project Description

The E-Commerce Platform is a full-stack web application designed to allow users to browse products, manage their cart, and place orders while providing administrators with tools to manage products, categories, and orders.

The platform aims to combine technical skills (Java, React, REST API) with soft skills like teamwork, project management, and problem-solving in a real-world e-commerce context.

⚡ Key Features

For Users
Browse and search products by category or keyword
Add products to the shopping car
Place orders and view order history
Account management (signup, login, profile update)
For Administrators
Manage products (add, edit, delete)
Manage categories
View and manage customer orders
Dashboard for sales statistics
Additional Features
Responsive design for desktop and mobile
Secure authentication with JWT
File upload for product images
🛠 Technologies

Backend

Java 17+
Spring Boot
Spring Security (JWT)
JPA / Hibernate
MySQL / PostgreSQL
Maven

Frontend

React.js
Axios (API calls)
React Route
Material UI / Bootstrap

ecommerce-platform/
│
├─ backend/ (Spring Boot)
│ ├─ src/main/java/com/ecommerce/
│ │ ├─ controller/ # REST API endpoints
│ │ ├─ service/ # Business logic
│ │ ├─ repository/ # Data access
│ │ └─ model/ # Entities
│ └─ src/main/resources/
│ └─ application.properties # Configuration
│
├─ frontend/ (React)
│ ├─ src/
│ │ ├─ components/ # Reusable components
│ │ ├─ pages/ # Main pages
│ │ ├─ services/ # API calls
│ │ └─ hooks/ # Custom hooks
│ └─ public/ # Static files (index.html, images)
│
└─ README.md
