# 🍽️ MenuMaster – Smart Restaurant Management System

**MenuMaster** is a powerful and intuitive web-based platform designed to manage restaurant menus, services, and customer feedback efficiently — all in one place.

[![License](https://img.shields.io/badge/License-MIT-blue)](https://opensource.org/licenses/MIT)

---

## 🌟 Key Features

- 🗂️ **Menu Management** – Easily create, update, or delete food categories and items.
- 🔐 **Secure Login** – Authenticate users using **Google** or **Facebook** accounts.
- 🔁 **CRUD Operations** – Full control over your restaurant’s offerings.
- 🌐 **REST API** – JSON endpoints to fetch menu data for integration or analytics.
- ⚙️ **Sample Data Ready** – Use `lotsofmenus.py` to quickly populate your database.

---

## 🚀 Quick Start

### ✅ Requirements

- Python
- Flask
- Vagrant
- VirtualBox or VMware

---

## 🛠️ Installation Guide

### 1. Clone the Project
```bash
git clone https://github.com/hussienmohaemd/FOODO
cd FOODO
```

### 2. Start Vagrant Environment
```bash
cd vagrant
vagrant up
vagrant ssh
```

### 3. Setup the Database
```bash
cd /vagrant/catalog
python database_setup.py
python lotsofmenus.py
```

### 4. Launch the App
```bash
python project.py
```

Now, open your browser at [http://localhost:5000](http://localhost:5000)

---

## 🔌 API Endpoints

- Get complete catalog:
```
GET /catalog/JSON
```

- Get menu items by category:
```
GET /categories/<int:category_id>/courses/JSON
```

---

## 🔐 User Access

- **Login/Register**: With Google or Facebook  
- **Authorized Users Can**:
  - Add/Edit/Delete categories
  - Manage menu items  
- **Logout**: Secure session termination

---

## 📁 Project Structure

```
MenuMaster/
├── static/             # Styles, scripts, and assets
├── templates/          # HTML files
├── app.py              # Main app launcher
├── database_setup.py   # Database schema setup
├── lotsofmenus.py      # Sample data script
├── project.py          # Main server script
├── README.md           # Project documentation
```

---

## 📬 Contact

- **Developer**: Eng. Hussien Mohamed  
- **Facebook**: [facebook.com/hussein.mohamed](https://www.facebook.com/hussein.mohamed)

---

## 📄 License

MIT License © 2025 Hussien Mohamed

---

> 🧾 *MenuMaster helps restaurants serve smarter – one item at a time.*
