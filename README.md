# 📋 To-Do Pro — Simple Django To-Do Application

A sleek, modern task management web application built with **Django** and **Bootstrap**. Stay organized, stay productive!

---

## ✨ Features

- ➕ **Add Tasks** — Quickly add new tasks using the input field
- ✅ **Mark as Done** — Mark tasks as completed with a single click
- ↩️ **Undo Tasks** — Revert completed tasks back to pending
- 🗑️ **Delete Tasks** — Remove tasks you no longer need
- 📊 **Task Statistics** — View total, completed, and pending task counts at a glance
- 🌙☀️ **Dark / Light Mode Toggle** — Switch between dark and light themes with a single click
- 🎨 **Modern UI** — Beautiful gradient accents and smooth styling in both themes

---

## 🛠️ Tech Stack

- **Python 3** — Backend language
- **Django** — Web framework
- **SQLite3** — Database
- **Bootstrap** — Frontend styling
- **HTML/CSS/JS** — Templates, custom styles, and theme switching

---

## 📁 Project Structure

    Simple Django To-Do/
    ├── static/
    │   └── style.css
    ├── todo/
    │   ├── migrations/
    │   │   ├── __init__.py
    │   │   └── 0001_initial.py
    │   ├── templates/todo/
    │   │   └── index.html
    │   ├── __init__.py
    │   ├── admin.py
    │   ├── apps.py
    │   ├── models.py
    │   ├── tests.py
    │   └── views.py
    ├── todo_project/
    │   ├── __init__.py
    │   ├── asgi.py
    │   ├── settings.py
    │   ├── urls.py
    │   └── wsgi.py
    ├── db.sqlite3
    ├── manage.py
    └── README.md

---

## 🚀 Getting Started

1. **Clone the repository**

       git clone https://github.com/yourusername/simple-django-todo.git
       cd simple-django-todo

2. **Create a virtual environment**

       python -m venv venv
       source venv/bin/activate        # macOS/Linux
       venv\Scripts\activate           # Windows

3. **Install dependencies**

       pip install django

4. **Apply migrations**

       python manage.py makemigrations
       python manage.py migrate

5. **Run the server**

       python manage.py runserver

6. **Open your browser** and go to `http://127.0.0.1:8000/`

---

## 📖 Usage

- **Add a task** — Type a task name and click **+ Add Task**
- **Complete a task** — Click **✔ Done** next to a pending task
- **Undo a task** — Click **↩ Undo** next to a completed task
- **Delete a task** — Click **🗑 Delete** to remove a task permanently
- **Toggle theme** — Click the ☀️/🌙 icon in the top-right corner to switch between **light** and **dark** mode
- Completed tasks show a ~~strikethrough~~ style with a green indicator
- Pending tasks show an orange indicator
- The statistics bar updates automatically

---

## 🎨 Themes

| Mode | Description |
|------|-------------|
| 🌙 **Dark Mode** | Deep purple-blue gradient background with vibrant accents — easy on the eyes |
| ☀️ **Light Mode** | Clean, bright interface for daytime productivity |

Your theme preference is preserved during your session for a seamless experience.

---

## 📄 License

This project is open source and available under the MIT License.

---

❤️ Made with Django & Bootstrap — © 2024 To-Do Pro. Stay productive!
