Here is the **clean, professional, GitHub-ready `README.md` with badges** — regenerated fresh, well-formatted, and polished.

---

# 📘 **Sellora CRM**

### *SME Sales CRM built using Django + AdminLTE + MySQL*

<p align="center">

<img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python" />
<img src="https://img.shields.io/badge/Django-4.x-success?logo=django" />
<img src="https://img.shields.io/badge/AdminLTE-3.2-blue?logo=bootstrap" />
<img src="https://img.shields.io/badge/MySQL-8.0+-blue?logo=mysql" />
<img src="https://img.shields.io/badge/License-MIT-yellow" />
<img src="https://img.shields.io/badge/Status-Active-brightgreen" />

</p>

**Sellora CRM** is a modern, responsive, and easy-to-use Sales CRM system designed for SMEs.
Built using **Django**, styled with **AdminLTE**, and powered by a **MySQL** backend.

---

# 🚀 Features

* Beautiful AdminLTE Dashboard
* User Authentication & Django Admin
* MySQL database integration
* Static & Media File configuration
* Extendable modules (Leads, Deals, Contacts, Team, Reports)
* Lightweight, fast & scalable architecture
* Easy setup and ready for production enhancement

---

# 📦 Tech Stack

| Technology               | Description        |
| ------------------------ | ------------------ |
| **Python 3**             | Backend Language   |
| **Django**               | Web Framework      |
| **AdminLTE**             | UI Dashboard Theme |
| **MySQL**                | Database           |
| **Pillow**               | Image Processing   |
| **Plotly**               | Interactive Charts |
| **Pandas**               | Data Analytics     |
| **Bootstrap Datepicker** | UX Improvements    |

---

# 🛠 Installation Guide

Follow these steps to install Sellora CRM on your local machine.

---

## **1. Create Virtual Environment**

```bash
python -m venv venv
```

---

## **2. Activate Virtual Environment**

### Windows:

```bash
venv\Scripts\activate
```

### Linux/Mac:

```bash
source venv/bin/activate
```

---

## **3. Install Django**

```bash
pip install Django
python -m django --version
```

---

## **4. Create Django Project**

```bash
django-admin startproject yourprojectname
```

---

## **5. Enter Project Folder**

```bash
cd yourprojectname
```

---

## **6. Create Django App**

```bash
python manage.py startapp yourappname
```

---

## **7. Install AdminLTE Packages**

### Option A — Full AdminLTE:

```bash
pip install django-admin-adminlte
```

### Option B — Lightweight AdminLTE 3:

```bash
pip install django-adminlte3
```

---

## **8. Add AdminLTE URL**

In `yourprojectname/urls.py`:

```python
path('', include('admin_adminlte.urls')),
```

---

## **9. Add AdminLTE App**

In `settings.py`:

```python
INSTALLED_APPS += [
    'admin_adminlte.apps.AdminAdminlteConfig',
]
```

---

# 🗄️ MySQL Database Setup

## **10. Install MySQL Dependencies**

```bash
pip install mysql
pip install mysql-client
```

---

## **11. Configure Database in `settings.py`**

```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'adminlte3',
        'USER': 'root',
        'PASSWORD': '',
        'HOST': '127.0.0.1',
        'PORT': '3306',
    }
}
```

---

## **12. Make Migrations**

```bash
python manage.py migrate
```

---

## **13. Create Superuser**

```bash
python manage.py createsuperuser
```

---

## **14. Start Development Server**

```bash
python manage.py runserver
```

---

# ⚙ Additional Configuration

### **settings.py**

```python
STATIC_URL = 'static/'

import os
MEDIA_URL = '/media/'
MEDIA_ROOT = os.path.join(BASE_DIR, 'media')

LOGIN_REDIRECT_URL = '/'
```

---

### **urls.py**

```python
from django.conf import settings
from django.conf.urls.static import static

if settings.DEBUG:
    urlpatterns += static(settings.MEDIA_URL, document_root=settings.MEDIA_ROOT)

if settings.DEBUG:
    urlpatterns += static(settings.STATIC_URL, document_root=settings.STATIC_ROOT)
```

---

# 📚 Optional Libraries

Install additional useful libraries:

```bash
pip install django-bootstrap-datepicker-plus
pip install pillow
pip install mysql
pip install plotly
pip install scipy
pip install pandas
```

---

# 📂 Project Structure

```
sellora-crm/
│
├── yourprojectname/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── yourappname/
│   ├── models.py
│   ├── views.py
│   └── admin.py
│
├── templates/
├── static/
├── media/
├── manage.py
└── requirements.txt
```

---

# ❤️ Credits

Sellora CRM is inspired by modern CRM systems and community-driven Django + AdminLTE tutorials.

---

# 🙏 Thank You

If this guide helped you, please like, share, and subscribe.

**Contact:**
📱 WhatsApp: 
📍 Location:

---

If you want **project badges, screenshots, or Sellora logo**, I can generate those too!
