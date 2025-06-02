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

📁 Project Structure (Descriptive Format)
The project is organized into a main root directory called todo_project, which contains essential files like manage.py for Django’s command-line utilities and the default SQLite database file db.sqlite3.

There are two main Django apps:

todo_app – This is the core application responsible for managing tasks. It includes:

models.py to define the Task model.

views.py for handling task-related logic such as listing, creating, updating, and deleting tasks.

forms.py for Django forms related to task input.

urls.py to define routes specific to the task operations.

users – This app manages user authentication. It contains:

views.py for login, logout, and registration logic.

forms.py for user-related forms like sign-up and login.

urls.py for user-specific routing.

The project also includes a templates directory for storing HTML templates and a static directory to hold static files like CSS and JavaScript.


