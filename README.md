<p align="center">
  <a href="https://laravel.com" target="_blank">
    <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="380" alt="Laravel Logo">
  </a>
  <span style="margin: 0 20px;"></span>
  <a href="https://postman.com" target="_blank">
    <img src="https://uxwing.com/wp-content/themes/uxwing/download/brands-and-social-media/postman-icon.svg" width="80" alt="Postman Logo">
  </a>
</p>

---

# 🔐 Laravel JWT Authentication API

A secure **RESTful API** built with Laravel using **JWT (JSON Web Token)** for authentication.  
Tested using **Postman**, the API allows login, registration, and protects routes using token-based authentication.

---

## ✅ Features

- 🧾 User Registration
- 🔑 Token-based Login
- 🛡️ Protected API routes with middleware
- ❌ Logout & Token Invalidation
- ✔️ Tested with Postman

---

## 🛠 Tools & Technologies

- Laravel 10+
- PHP 8.1+
- Composer
- SQLite / MySQL
- [tymon/jwt-auth](https://github.com/tymondesigns/jwt-auth)
- Postman

---

## 🚀 Getting Started

### 1️⃣ create new project
### 2️⃣ Install Dependencies
First setup api then JWT
### 3️⃣🔧 Install JWT Package
composer require tymon/jwt-auth
#### 1. Publish the config:
php artisan vendor:publish --provider="Tymon\JWTAuth\Providers\LaravelServiceProvider"

#### 2. Generate JWT secret key:
php artisan jwt:secret
#### 3. 🧑‍💻 Auth Routes


