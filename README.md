# 🛒 Dhami Electronics

![License](https://img.shields.io/badge/license-Proprietary-red)
![Python](https://img.shields.io/badge/Python-3.11%2B-blue)
![Flask](https://img.shields.io/badge/Flask-2.x-green)
![SQLite](https://img.shields.io/badge/Database-SQLite-lightgrey)

**Dhami Electronics** is a full-featured e-commerce web application built with **Flask** and **SQLite**. It provides a complete online shopping experience for electronics with a clean, mobile-responsive interface and a powerful admin panel.

## 📖 Project Background

This project was developed by **Dinesh Singh Dhami** as a complete **online electronics store** tailored for the Nepali market (NPR currency + Nepal Timezone). It includes OTP email verification, real-time stock management, smart shipping logic, and beautiful email notifications.

Built to practice Flask best practices while creating a production-ready e-commerce platform from scratch.

> **⚠️ Note:** This project is **NOT open source**.  
> All source code, designs, email templates, images, and other assets are proprietary and protected by copyright law. Unauthorized copying, modification, distribution, or reuse is strictly prohibited.

---

## 🚀 Key Features

- Secure registration & login with **OTP email verification**
- Product browsing with discounts and reviews
- Shopping cart with real-time stock validation
- Smart shipping (Free above NPR 5000 | Flat NPR 150 otherwise)
- Checkout and order management
- Order cancellation (within 1 hour)
- Beautiful mobile-responsive HTML emails (OTP, order confirmation, status updates)
- Full admin dashboard for product & order management
- Nepal Timezone (NPT) support

---

## 🌐 Live Demo

👉 https://dhamielectronics.pythonanywhere.com/

---

## 🧪 Tech Stack

- **Backend:** Flask (Python)
- **Database:** SQLite + SQLAlchemy
- **Frontend:** HTML, CSS, Jinja2, Bootstrap
- **Authentication:** Flask-Login + Werkzeug
- **Email:** Flask-Mail (Gmail SMTP)
- **Others:** pytz (Asia/Kathmandu), Secure file uploads

---

## 📁 Project Structure

```text
dhami-electronics/
├── app.py
├── static/
│   └── uploads/
├── templates/
│   ├── admin/
│   ├── index.html
│   ├── product_detail.html
│   ├── cart.html
│   ├── checkout.html
│   └── ...
├── ecommerce.db
├── requirements.txt
├── README.md
└── LICENSE.md
```

---

## 🔐 License (Proprietary — All Rights Reserved)

This project is proprietary software. **All rights are reserved by the author.**

You are **NOT permitted** to:

- Copy or reproduce any part of the source code
- Modify or reuse any part of this project
- Redistribute, republish, or upload this project to any platform
- Use the source code, assets, email templates, or designs in personal, academic, or commercial projects
- Reverse-engineer, decompile, or create derivative works

> **⚠️ Unauthorized copying, modification, distribution, publication, or reuse of this project's source code, assets, email templates, or designs constitutes copyright infringement and may result in legal action, including claims for damages, injunctive relief, and any other remedies available under applicable copyright and intellectual property laws.**

No license or permission is granted to use this project without the **prior written consent** of the copyright owner.

For licensing inquiries or special permission, please contact the author directly.

The complete legal terms are available in the [LICENSE](LICENSE.md) file.

---

## 🤝 Contributions

External contributions are **not accepted**.

This project is privately owned and maintained solely by the author.

---

