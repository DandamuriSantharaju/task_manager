# 📝 Task Manager - Django Web App

A simple yet elegant task management application built with Django. This app lets users add, view, complete, and delete daily tasks—helping you stay organized and productive throughout the day.

---

## 🚀 Features

- ✅ Add new tasks
- ✔️ Mark tasks as completed
- 🗑️ Delete tasks
- 🔄 Auto-updating task list
- 🎨 Attractive and responsive UI using HTML5 & CSS3

---

## 🔧 Tech Stack

- **Backend:** Django (Python)
- **Frontend:** HTML5, CSS3
- **Database:** SQLite (default in Django)
- **Design:** Minimal UI with custom CSS

---

## 📁 Project Structure
task_manager/
│
├── manage.py
├── db.sqlite3
├── task_manager/
│ ├── init.py
│ ├── settings.py
│ ├── urls.py
│ └── wsgi.py
│
├── tasks/
│ ├── admin.py
│ ├── apps.py
│ ├── models.py
│ ├── views.py
│ ├── urls.py
│ ├── templates/
│ │ └── tasks/
│ │ └── home.html
│ └── static/
│ └── css/
│ └── styles.css


---

## 🛠️ Installation Guide

Follow these steps to set up and run the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/DandamuriSantharaju/task_manager.git
cd task_manager
## 🛠️ Installation Guide

Follow these steps to set up and run the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/DandamuriSantharaju/task_manager.git
cd task_manager

python -m venv venv
source venv/bin/activate     # For Windows: venv\Scripts\activate

pip install django

python manage.py makemigrations
python manage.py migrate

python manage.py runserver

🧠 How It Works
Task model stores each task with a title and completed status.

Tasks are displayed on the homepage in a list format.

Users can:

➕ Add a new task using the form

✅ Mark a task as completed

🗑️ Delete any task from the list

📌 Future Improvements
🔐 Add user authentication (login/signup)

📅 Add task deadlines and priority levels

✏️ Enable task editing

📱 Responsive design for mobile devices

👤 Author
Santharaju Dandamuri
📧 LinkedIn: https://www.linkedin.com/in/santharaju-dandamuri/
🔗 GitHub Repository : https://github.com/DandamuriSantharaju
