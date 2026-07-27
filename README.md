# Django Authentication System

A simple Django authentication system with:

- User Registration
- User Login
- User Logout
- Dashboard Page
- 
## Technologies Used

- Python 3.x
- Django 5.x
- SQLite3

## Project Structure

```
auth_project/
│
├── auth_app/
│   ├── migrations/
│   ├── templates/
│   │   ├── auth/
│   │   │   ├── login.html
│   │   │   └── register.html
│   │   ├── dashboard.html
│   │   └── layouts/
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── urls.py
│   └── views.py
│
├── auth_project/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── db.sqlite3
├── manage.py
└── README.md
```

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/auth_project.git
```

### 2. Navigate to the project

```bash
cd auth_project
```

### 3. Create a virtual environment

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**Linux / macOS**<img width="856" height="193" alt="a3" src="https://github.com/user-attachments/assets/1c405632-be5c-47aa-847d-1b2e9bf00b27" />
<img width="904" height="356" alt="a2" src="https://github.com/user-attachments/assets/d0f5d203-e441-4365-9824-b451adb63ae6" />
<img width="917" height="452" alt="a1" src="https://github.com/user-attachments/assets/f5de33cc-4af3-4b58-b652-09f721f4681b" />


```bash
python3 -m venv venv
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install django
```

or

```bash
pip install -r requirements.txt
```

### 5. Apply migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 6. Create a superuser (Optional)

```bash
python manage.py createsuperuser
```

### 7. Run the development server

```bash
python manage.py runserver
```

Open your browser and visit:

```
http://127.0.0.1:8000/
```

or if your URLs are configured under the `auth` prefix:

```
http://127.0.0.1:8000/auth/login/
```

---

## Available Routes

| URL | Description |
|------|-------------|
| `/auth/register/` | Register a new user |
| `/auth/login/` | User login |
| `/auth/logout/` | User logout |
| `/auth/dashboard/` | Dashboard |
| `/admin/` | Django Admin |

---

## Features

- User Registration
- User Login
- User Logout
- Dashboard
- Session Authentication
- Django Messages Framework
- SQLite Database

---

## Database

Default database:

```
SQLite3
```

Database file:

```
db.sqlite3
```

---

## Admin Panel

Create an admin account:

```bash
python manage.py createsuperuser
```

Then login at:

```
http://127.0.0.1:8000/admin/
```

---

## Requirements

- Python 3.10+
- Django 5.x

---

## License

This project is intended for learning and educational purposes.
