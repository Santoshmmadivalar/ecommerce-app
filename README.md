# 🛍️ ShopHub – Full Stack E-Commerce Web Application

<p align="center">
  <img src="https://img.shields.io/badge/PHP-Backend-blue?style=for-the-badge&logo=php">
  <img src="https://img.shields.io/badge/MySQL-Database-orange?style=for-the-badge&logo=mysql">
  <img src="https://img.shields.io/badge/Bootstrap-Frontend-purple?style=for-the-badge&logo=bootstrap">
  <img src="https://img.shields.io/badge/XAMPP-Server-red?style=for-the-badge&logo=xampp">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">
</p>

<p align="center">
  A modern and fully responsive <b>Full Stack E-Commerce Website</b> built using <b>PHP, MySQL, HTML, CSS, JavaScript, Bootstrap 5</b>, and <b>jQuery</b>.
</p>

---

# ✨ Project Overview

**ShopHub** is a dynamic e-commerce platform designed to simulate a real-world online shopping experience.
The application provides secure authentication, product management, shopping cart functionality, order handling, and an admin dashboard.

The project focuses on:

* Responsive UI/UX
* Secure backend architecture
* Real-time cart interactions
* Database-driven product management
* Modern web technologies

---

# 🚀 Features

## 👤 User Features

* User Registration & Login
* Secure Authentication System
* Category-Based Product Browsing
* Product Search & Filtering
* Product Detail Page
* Add to Cart Functionality
* Quantity Update & Remove Cart Items
* Checkout System
* Order History
* User Dashboard
* Responsive Design for Mobile & Desktop

---

## 🛠️ Admin Features

* Secure Admin Login
* Admin Dashboard
* Product Management

  * Add Products
  * Edit Products
  * Delete Products
* Order Management
* User Management
* Sales Statistics Dashboard
* Image Upload Support

---

# 🧰 Tech Stack

| Technology  | Usage                    |
| ----------- | ------------------------ |
| HTML5       | Structure                |
| CSS3        | Styling                  |
| JavaScript  | Frontend Interactivity   |
| jQuery      | Dynamic UI               |
| Bootstrap 5 | Responsive Design        |
| MDBootstrap | UI Components            |
| PHP         | Backend Development      |
| MySQL       | Database                 |
| Chart.js    | Analytics Dashboard      |
| XAMPP       | Local Server Environment |

---

# 📁 Project Structure

```bash
ecommerce-App/
│
├── admin/                  # Admin panel files
├── user/                   # User account pages
├── includes/               # Shared PHP components
├── assets/
│   ├── css/                # Stylesheets
│   ├── js/                 # JavaScript files
│   └── images/             # Product images
│
├── database/               # SQL database files
├── index.php               # Home page
├── shop.php                # Shop page
├── product.php             # Product details
├── cart.php                # Cart page
├── checkout.php            # Checkout page
└── database.sql            # Database schema
```

---

# 🔐 Security Features

* SQL Injection Prevention using Prepared Statements
* Password Hashing using `password_hash()`
* Session-Based Authentication
* Input Sanitization
* File Upload Validation
* XSS Protection

---

# 📸 Website Preview

## 🏠 Home Page

<img width="100%" src="https://github.com/user-attachments/assets/47fbf715-0801-41c1-b285-26bd151bc86a">

<img width="100%" src="https://github.com/user-attachments/assets/75f063ad-912c-49c6-b6c6-bde295104b93">

---

## 🛒 Shop Page

<img width="100%" src="https://github.com/user-attachments/assets/2b154024-7194-43c1-9dd3-0bc475e28d6d">

<img width="100%" src="https://github.com/user-attachments/assets/5aff1d8b-8a7e-4da4-b302-f7205a320090">

---

## 🔐 Authentication Pages

### Signup Page

<img width="100%" src="https://github.com/user-attachments/assets/15876b7f-398f-448d-9ddd-7e7b69bfbb01">

### Login Page

<img width="100%" src="https://github.com/user-attachments/assets/a3a7a1ed-e4c3-4cfb-8b6a-4cbcc559b81e">

---

## 🛠️ Admin Dashboard

<img width="100%" src="https://github.com/user-attachments/assets/940122fc-e418-4259-92cb-3e869ef3d700">

---

## 🛒 Cart Page

<img width="100%" src="https://github.com/user-attachments/assets/b25fe167-9dda-44b0-b5bd-6f38c2dc6ab3">

---

## 📞 Contact Page

<img width="100%" src="https://github.com/user-attachments/assets/6e01c353-26e6-4e77-b29f-739fde75ffc5">

<img width="100%" src="https://github.com/user-attachments/assets/006a6f69-23ce-478f-8af1-96b32bf0f3f7">

---

## ℹ️ About Page

<img width="100%" src="https://github.com/user-attachments/assets/44a8fd5e-ee37-4775-8524-5e358065d68b">

<img width="100%" src="https://github.com/user-attachments/assets/8d6535a9-515a-425e-9591-1ae5b9a399d8">

---

# 🎥 Demo Videos

## ▶️ Website Demo

https://github.com/user-attachments/assets/ab9c82a3-1615-4feb-b0be-3dc80b82d424

---

## ▶️ Product & Cart Demo

https://github.com/user-attachments/assets/79c2ef82-3346-43e9-97a2-976c7132cc34

---

## ▶️ Admin Panel Demo

https://github.com/user-attachments/assets/a4c6ed4a-1762-40d8-9119-6c40de41d5e1

---

# ⚙️ Installation Guide

## 📌 Prerequisites

Make sure you have installed:

* XAMPP / WAMP / LAMP
* PHP 8+
* MySQL
* Modern Web Browser

---

# 🛠️ Setup Instructions

## 1️⃣ Clone Repository

```bash
git clone <repository-url>
cd ecommerce-App
```

---

## 2️⃣ Move Project to XAMPP

Move the project folder into:

```bash
C:/xampp/htdocs/
```

---

## 3️⃣ Start Apache & MySQL

Open **XAMPP Control Panel** and start:

* Apache
* MySQL

---

## 4️⃣ Create Database

* Open `phpMyAdmin`
* Create a database named:

```sql
ecommerce
```

* Import:

```bash
database.sql
```

---

## 5️⃣ Configure Database

Open:

```bash
includes/db_connect.php
```

Update credentials if required:

```php
$host = 'localhost';
$dbname = 'ecommerce';
$username = 'root';
$password = '';
```

---

## 6️⃣ Run Project

Open browser and visit:

```bash
http://localhost/ecommerce-App/
```

---

# 🔑 Default Admin Credentials

| Role  | Username | Password |
| ----- | -------- | -------- |
| Admin | admin    | admin123 |

---

# 📊 Database Modules

The system contains the following tables:

* users
* admin_users
* products
* categories
* orders
* order_items
* reviews
* cart

---

# 📱 Responsive Design

The application is fully responsive and works across:

* Desktop 💻
* Tablet 📱
* Mobile 📲

---

# 🌟 Future Enhancements

* Online Payment Gateway Integration
* Wishlist Feature
* Email Notifications
* Invoice Generation
* Product Ratings & Reviews
* AI-Based Recommendations
* Multi-Vendor Support

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create your feature branch
3. Commit changes
4. Push to branch
5. Open a Pull Request

---

# 📄 License

This project is created for educational purposes.

You are free to use and modify it.

---

# 👨‍💻 Developer

Developed with ❤️ using PHP & MySQL

---

# ⭐ Support

If you like this project:

* Give it a ⭐ on GitHub
* Share with others
* Fork & contribute

---

<p align="center">
  <b>🛒 ShopHub – Making Online Shopping Simple & Modern</b>
</p>
