# Authentication_with_username_password
 Basic authentication system using Node.js, Express, and PostgreSQL. Users can register and log in with email and password.


This repository is part of a step-by-step authentication series implemented using **Node.js**, **Express**, and **PostgreSQL**. Each level adds a layer of security or authentication technique to help learners understand how real-world login systems evolve from basic to more secure practices.

> ⚠️ This project is for educational purposes only. Do **not** use Level 1 in production environments.

---

## 🔢 Project Structure

This repository contains multiple branches or folders, each representing a **progressive level of authentication**.  
You are currently viewing **Level 1: Plain Password Storage**.

Future levels may include:
- Level 2: Hashed Passwords with `bcrypt`
- Level 3: Sessions and Cookies
- Level 4: OAuth Authentication (e.g., Google)
- Level 5: Encryption of Secrets
- Level 6: JWT (JSON Web Tokens)

---

## 🚀 Level 1 Overview

In this level, we implement a basic user registration and login system. User credentials are stored in plain text in a PostgreSQL database.

### ⚠️ Disclaimer

This method is **not secure** and is only intended to demonstrate the initial logic behind authentication.

---


## 🧪 PostgreSQL Setup

CREATE TABLE users (
  id SERIAL PRIMARY KEY,
  email VARCHAR(255) UNIQUE NOT NULL,
  password TEXT NOT NULL
);



## 🛠️ How to Run
node index.js


### 📌 Routes

| Route       | Method | Description              |
|-------------|--------|--------------------------|
| `/`         | GET    | Home page                |
| `/register` | GET    | Registration form page   |
| `/register` | POST   | Handle user registration |
| `/login`    | GET    | Login form page          |
| `/login`    | POST   | Handle login submission  |
| `/secrets`  | GET    | Show protected content   |



⚠️ Do not use Level 1 in production. It is intentionally insecure for teaching purposes.


