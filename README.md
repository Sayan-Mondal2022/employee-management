# Employee Management Tool

A simple web-based Employee Management System built using **Django**.
This tool allows you to **add, modify, and delete** employees, making it easy to manage employee records in an organization.

---

## 🚀 Features

1. ➕ Add Employee – Register a new employee with details.
2. ✏️ Modify Employee – Update existing employee information.
3. ❌ Delete Employee – Remove employees from the system.
4. 🖼️ Employee Image Upload – Supports image display using Pillow.

---

## 🛠️ Tech Stack

- Backend: Django (Python)
- Frontend: HTML, CSS (Django templates)
- Database: MongoDb
- Image Handling: Pillow

---

## ⚙️ Installation & Setup

1. Clone the repository
```bash
git clone https://github.com/your-username/employee-management.git
cd employee-management-tool
```

2. Create and activate a virtual environment
```bash
python -m venv .venv
source venv/bin/activate   # For Linux/Mac
venv\Scripts\activate      # For Windows
```

3. Install the requirements
```bash
pip install django pillow pymongo
```

4. Run database migrations
```bash
python manage.py migrate
```

5. Start the development server
```bash
python manage.py runserver
```

6. Open in browser
```bash
http://127.0.0.1:8000/
```

---

## 📦 Requirements

- Python 3.x
- Django
- Pillow
- pymongo
