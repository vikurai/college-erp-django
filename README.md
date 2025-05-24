# 🎓 College Enterprise Resource Planner (ERP)

A full-featured **College ERP System** developed using **Python** and the **Django Framework**. This project was created by me and my team as part of our academic curriculum at **SIGCE**. It aims to streamline the management of academic and administrative activities for colleges.

🔗 **Live Demo**: [SIGCE ERP v1.1.0](https://syncx.pythonanywhere.com)

---

## 🧑‍💻 Login Credentials

### 👨‍🎓 Student Login

* **Email:** `student@student.com`
* **Password:** `student@erp`

### 👨‍🏫 Staff Login

* **Email:** `staff@staff.com`
* **Password:** `staff@erp`

---

## 📌 Features

### 🔐 Admin Dashboard

* View summary charts of performance (students/staff)
* Manage:

  * Staff (CRUD)
  * Students (CRUD)
  * Courses (CRUD)
  * Subjects (CRUD)
  * Sessions (CRUD)
* Attendance Management
* Approve/Reject leave applications
* Respond to feedback from students/staff

### 👨‍🏫 Staff/Teachers

* Dashboard with performance and summary stats
* Take and update attendance
* Manage student results (Add/Edit)
* Apply for leave
* Send feedback to HOD

### 👨‍🎓 Students

* Dashboard with subject/attendance stats
* View attendance and results
* Apply for leave
* Send feedback to HOD

---

## 🚀 Installation & Setup

### ✅ Prerequisites

* Git: [Install Git](https://git-scm.com/)
* Python: [Install Python](https://www.python.org/downloads/)
* Pip: [Install Pip](https://pip.pypa.io/en/stable/installing/)

### 📦 Clone and Setup Project

```bash
# Clone the repository
git clone https://github.com/Ansarimajid/College-ERP.git
cd College-ERP
```

### 🌐 Virtual Environment Setup

#### Option 1: Using Conda (If installed)

```bash
conda env create -f college-erp.yml
conda activate Django-env
```

#### Option 2: Using virtualenv

```bash
pip install virtualenv

# Create virtual environment
python -m venv venv  # Windows
python3 -m venv venv # macOS
virtualenv .         # Linux

# Activate it
source venv/Scripts/activate      # Windows
source venv/bin/activate          # macOS/Linux
```

### 📥 Install Dependencies

```bash
pip install -r requirements.txt
```

### ⚙️ Configure Allowed Hosts

Edit the `settings.py` file:

```python
ALLOWED_HOSTS = []
```

*Never use default settings in production—configure securely!*

### ▶️ Run the Development Server

```bash
# Windows
python manage.py runserver

# macOS/Linux
python3 manage.py runserver
```

### 👑 Create Superuser (Admin/HOD)

```bash
python manage.py createsuperuser
```

---

## 📈 Project Progress

* [x] Admin/Staff/Student Logins
* [x] Course/Staff/Student/Subject CRUD
* [x] Upload Profile Pictures
* [x] Sidebar Active State
* [x] ModelForms for Data Entry
* [x] Attendance System
* [x] Result Management
* [x] Leave Application
* [x] Feedback System
* [x] Password Reset & Change
* [x] Google CAPTCHA
* [x] Role-Based Dashboards
* [x] CBVs for Editing
* [x] Dynamic Routing and Links
* [x] Code Restructure & Optimization

---

## 💡 Support the Project

If you find this project helpful:

* 🌟 Star this repo
* 👨‍💻 Follow me on [GitHub](https://github.com/Ansarimajid)
* 💼 Connect on [LinkedIn](https://www.linkedin.com/in/ansarimajid)

---

## 📝 License

This project is for educational purposes. Please contact me for commercial use or contributions.


