# innvotex-corporate-site
A secure, multi-language corporate CMS built with Python Flask &amp; SQLite, deployed on GoDaddy Shared Hosting using Phusion Passenger.
# Innvotex - Corporate Web Application 🏭

A dynamic, secure, and fully responsive corporate website built for a textile machinery and consulting company.

🔗 **Live Demo:** [https://www.innvotex.com](https://www.innvotex.com)

![Project Screenshot](screenshot.png)
*(Note: Replace 'screenshot.png' with an actual screenshot of the landing page)*

## 🚀 Project Overview

This project was developed to provide a strong digital presence for **Innvotex**. Unlike static websites, this application features a **custom-built Content Management System (CMS)** allowing the site owner to manage blogs, media galleries, FAQs, and incoming messages without touching a single line of code.

The application is deployed on a **Shared Hosting environment (cPanel)** using **Phusion Passenger**, demonstrating advanced deployment configuration capabilities beyond standard VPS setups.

## 🛠️ Tech Stack & Key Features

### Backend
* **Python / Flask:** The core framework powering the application.
* **SQLite:** Lightweight yet robust database for storing messages, user data, and blog content.
* **Phusion Passenger:** Used as the application server to run Python on cPanel shared hosting.

### Key Functionalities
* **🔐 Secure Admin Panel:** A protected dashboard for the business owner to manage content.
* **🌍 Multi-Language Support:** Fully integrated localization (TR/EN/FR) using `Flask-Babel`.
* **📧 Advanced Mail Integration:** Custom integration with **Brevo API** for contact forms and secure "Password Reset" functionality (overcoming standard SMTP port blocks).
* **🛡️ Security:**
    * CSRF Protection (`Flask-WTF`).
    * Rate Limiting (`Flask-Limiter`) to prevent abuse.
    * Secure Password Hashing (`Werkzeug`).
    * Automatic HTTPS enforcement.
* **🖼️ Dynamic Media Management:** Admin can upload/delete images and videos for the blog/gallery section.

## 💡 Deployment Challenge

One of the key achievements of this project was successfully deploying a modern Python Flask application on a legacy **GoDaddy Shared Hosting** infrastructure.

* Configured **`.htaccess`** and **`passenger_wsgi.py`** for proper routing.
* Solved complex environment path issues and `pip` dependency conflicts in a restricted environment.
* Implemented custom JSON encoding handling for email APIs to support Turkish character sets flawlessly.

## 👨‍💻 Developer Notes

This repository serves as a portfolio showcase. Due to client confidentiality and proprietary business logic, the full source code is not publicly available.

If you are interested in the technical details or my deployment strategies for Python on Shared Hosting, feel free to contact me!
