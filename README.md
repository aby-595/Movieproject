# 🎬 Movie Listing Web App (Django)

A Django-based web application that allows users to view, add, and manage movie listings. This project was built to practice Django’s MVC structure, form handling, and dynamic content rendering.

---

## 🔧 Features

- Home page displaying a list of movies
- Add/edit movie entries via Django admin
- Dynamic templates and routing using Django views
- Admin panel to manage data (CRUD operations)

---

## 🚀 Technologies Used

- Python 3.x
- Django
- HTML, CSS (Basic styling)
- SQLite (Default Django database)

---

## 📁 Folder Overview

- `movieproject/` – Django project folder (settings, urls, wsgi, etc.)
- `movies/` – App folder (views, models, templates assumed here)
- `templates/` – HTML templates for rendering movie data
- `static/` – CSS/JS (if applicable)

---

## ▶️ How to Run This Project

> Make sure Python and Django are installed.

```bash
# 1. Clone the repo
git clone https://github.com/aby-595/Movieproject.git
cd Movieproject

# 2. Create virtual environment (optional)
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# 3. Install Django
pip install django

# 4. Migrate and run
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
