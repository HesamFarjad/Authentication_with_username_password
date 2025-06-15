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


<img width="1439" alt="1" src="https://github.com/user-attachments/assets/5f0446d2-0de4-463e-868b-d3693bdfbb74" />


![2](https://github.com/user-attachments/assets/b31ec8a6-aa5b-49e8-af25-93da5504f660)


<img width="1122" alt="3" src="https://github.com/user-attachments/assets/219d635f-88a7-468f-b08b-3141ba6fc0be" />


![4](https://github.com/user-attachments/assets/7cd85994-cf21-4c1b-886f-ee747185fc0f)


![5](https://github.com/user-attachments/assets/4a5265a1-8435-419e-84f3-39e7eb5fe65b)
