# Django Todo Application

A complete Todo web application built with Django, featuring a modern UI with Tailwind CSS. This app allows users to efficiently manage their daily tasks with an intuitive interface.

## 🚀 Live Demo

Check out the live application here: **[Django Todo App](https://ostad-batch-10-todo-app.onrender.com)**

## 🚀 Forked Repository Link

Check out the forked repository link: **[Link](https://github.com/shekhmanzurmit05/Ostad_batch-09)**


## ✨ Features

- ✅ **Create Tasks** - Add new tasks with title, description, and due date
- ✅ **Read Tasks** - View all your tasks in a clean, organized interface
- ✅ **Update Tasks** - Edit task details or mark them as complete/incomplete
- ✅ **Delete Tasks** - Remove tasks you no longer need
- ✅ **Filter Tasks** - View All, Active, or Completed tasks with simple tabs
- ✅ **AJAX Toggle** - Mark tasks complete without page reload
- ✅ **Responsive Design** - Works perfectly on desktop, tablet, and mobile
- ✅ **User-friendly Messages** - Django messages framework for feedback

## 🛠️ Technology Stack

- **Backend**: Python 3.11 + Django 5.2
- **Frontend**: Django Templates + Tailwind CSS (via CDN)
- **Database**: SQLite (development) / PostgreSQL (production)
- **Server**: Gunicorn
- **Deployment**: Render

## 📋 Prerequisites

Before running this project locally, make sure you have:

- Python 3.8 or higher installed
- pip (Python package manager)
- Git (for cloning the repository)

## 🔧 Local Installation Guide

Follow these steps to run the project on your local machine:

1. **Clone the Repository:**

```bash
git clone https://github.com/yourusername/Ostad_batch-09.git
cd Ostad_batch-09
```

2. **Create a virtual environment (recommended):**

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run migrations:**
   ```bash
   python manage.py migrate
   ```

5. **Create a superuser (optional, for admin access):**
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server:**
   ```bash
   python manage.py runserver
   ```

7. **Open your browser and navigate to:**
   ```
   http://127.0.0.1:8000/
   ```