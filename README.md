# Basic Web Application Demonstrating Common Vulnerabilities

This project is a simple website created for **HB CyberTech** to demonstrate basic web application vulnerabilities, primarily focusing on **SQL Injection**. The goal is to teach about common security issues that exist in web applications and how they can be exploited if not handled properly.

## Table of Contents

1. [Overview](#overview)
2. [Technologies Used](#technologies-used)
3. [Vulnerabilities Demonstrated](#vulnerabilities-demonstrated)
4. [Setup](#setup)

---

## Overview

This project consists of a **frontend** built using HTML, CSS, and JavaScript, with a **backend** powered by **Node.js** and **SQLite**. The website is intentionally designed with common security vulnerabilities to showcase how attackers can exploit them to gain unauthorized access to the application.

---

## Technologies Used

- **Frontend**:

  - **HTML**: Used to build the basic structure of the website.
  - **CSS**: Used for styling the login page.
  - **JavaScript**: Used for handling requests and manipulating the DOM.

- **Backend**:
  - **Node.js**: JavaScript runtime to create the server and handle HTTP requests.
  - **Express.js**: Web framework for Node.js to simplify routing and handling HTTP requests.
  - **SQLite**: Lightweight SQL database to store user data (like usernames and passwords).
- **Tools**:
  - **Postman** or **Browser**: Used to test and interact with the application.

---

## Vulnerabilities Demonstrated

### 1. **SQL Injection (Authentication Bypass)**

How user input is directly used in SQL queries without validation or sanitization, which allows an attacker to manipulate the query and bypass authentication.

### 2. **Cross-Site Scripting (XSS)**

An attacker can inject malicious scripts into web pages viewed by other users, potentially leading to session hijacking, defacement, or redirection to malicious sites.

---

## Setup

To set up the project locally, follow these steps:

1. **Clone the repository**:

```sh
  git clone https://github.com/sachkeeratb/Vunerable-Website.git
```

2. **Navigate to the client directory and start the frontend server**:

```sh
  cd Vunerable-Website/client
  python3 -m http.server
```

3. **Navigate to the server directory and start the backend server**:

```sh
  cd ../server
  node server.js
```

Now, you can access the website and start exploring.