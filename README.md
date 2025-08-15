# Multi-Role Portal with CAPTCHA & Data Management

A Flask-based web application that supports **Admin**, **Employee**, **Customer**, and **Student** logins — each with its own dashboard and features.  
Includes **image-based CAPTCHA security** on all login pages, **Excel-based data storage**, and role-specific actions.

---

## 🚀 Features
- **Multi-role authentication**
  - Admin: Can manage employees.
  - Employee: Can register customers and students, and manage daily work.
  - Customer & Student: Secure login with assigned credentials.
- **CAPTCHA Protection** on every login page.
- **Excel Data Storage** using `openpyxl`.
- **User-Friendly UI** with a clean HTML/CSS design.
- **Data Viewing** — Admin can see all records, employees can see their own.

---

## 🛠️ Technologies Used
- **Backend:** Flask (Python)
- **Frontend:** HTML, CSS
- **Security:** Werkzeug password hashing, CAPTCHA images
- **Database:** Excel files via `openpyxl`
- **Hosting:** [Specify your hosting provider, e.g., PythonAnywhere, Railway, VPS, etc.]

---

## 📜 My Learning Journey
Over the past few days, I:
1. Built a **basic Flask app** with login and dashboard pages.
2. Added **role-based authentication** for different user types.
3. Learned how to use **Excel files as a lightweight database**.
4. Implemented **CAPTCHA verification** using the `captcha` Python library.
5. Created **registration forms** for customers and students.
6. Added **data viewing and management features**.
7. Learned how to **host a Flask website online**.
8. Connected everything with **file storage** for persistence.
9. Integrated **CSS styling** for a better user interface.
10. Uploaded the project to **GitHub**.

---



portal/
│-- app.py               # Main Flask application
│-- README.md             # Documentation
│-- portal_data/          # Excel data storage
│-- templates/            # HTML templates (if used)
│-- static/               # Static assets (CSS, images, etc.)


The website is currently online https://csc-hli6.onrender.com/login
