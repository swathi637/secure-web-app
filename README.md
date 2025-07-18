# secure-web-app
A secure PHP web application with form validation, role-based user access, and protection against SQL injection using prepared statements (PDO). Includes both client-side and server-side validation for better security and user experience.
# Secure PHP Web Application

A secure PHP-based web application that includes:

-  Prepared statements using PDO (protection from SQL injection)
- Server-side and client-side form validation
-  User roles and role-based access control (e.g., Admin, Editor)

---

## Features

- **User Authentication** – Login and registration with secure password handling  
- **Prepared Statements** – All database queries use PDO for safe execution  
- **Form Validation**  
  - Client-side (HTML/JS)
  - Server-side (PHP)
- **User Roles** – Admin and Editor roles with different access levels  
- **Clean UI** – Simple and responsive user interface

---

##  Project Structure

students/
│
├── index.php
├── login.php
├── register.php
├── logout.php
