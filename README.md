# 📝 Django To-Do List App

A simple and functional To-Do List web application built with **Python** and **Django**. This app allows users to **register**, **log in**, and manage their personal to-do tasks with full **CRUD (Create, Read, Update, Delete)** capabilities.

---

## 🚀 Features

- ✅ User registration and login (authentication system)
- 🔒 Each user can see only their own tasks
- ✏️ Create, update, and delete tasks
- 📋 Mark tasks as completed or pending
- 📆 Set due dates and optional descriptions
- 🧼 Clean and minimal UI (Bootstrap/Tailwind optional)
- 📦 Easily deployable to services like Heroku, Render, or Railway

---

## 🛠️ Tech Stack

- **Backend:** Django (Python)
- **Database:** SQLite (default) – easy to switch to PostgreSQL
- **Frontend:** Django Templates + HTML/CSS
- **Auth:** Django built-in authentication system

---

## 📂 Project Structure

todo_project/
│
├── todo_app/ # Main app for task management
│ ├── models.py # Task model
│ ├── views.py # Views for CRUD
│ ├── forms.py # Django forms for tasks
│ └── urls.py # URL routing for the app
│
├── users/ # Handles user registration & login
│ ├── views.py
│ ├── forms.py
│ └── urls.py
│
├── templates/ # HTML templates
├── static/ # Static files (CSS, JS)
├── db.sqlite3 # Default database
└── manage.py


