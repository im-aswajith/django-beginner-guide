# 🐍 Django for Beginners — Step-by-Step Guide

> A practical, beginner-friendly manual to help you get started with Django on Windows.  
> **This is Part 1** — more steps are on the way. Stay tuned for **Part 2**! 🚧

---

## 📌 What is Django?

Django is a high-level Python web framework that encourages rapid development and clean, pragmatic design. It's perfect for beginners who want to build real web applications without reinventing the wheel.

---

## ✅ Prerequisites

Before you begin, make sure you have the following installed on your Windows machine:

| Tool | Download Link |
|------|--------------|
| Python 3.x | [python.org](https://www.python.org/downloads/) |
| pip (comes with Python) | — |
| VS Code | [code.visualstudio.com](https://code.visualstudio.com/) |
| Git (optional but recommended) | [git-scm.com](https://git-scm.com/) |

To verify Python is installed, open Command Prompt and run:

```bash
python --version
```

To install Django, run:

```bash
pip install django
```

---

## 🚀 Part 1 — Coming Soon

Part 1 will cover the very basics:

- What Django is and how it works
- Understanding the MVC/MVT pattern
- Setting up your Python environment
- Installing Django and verifying your installation

> ⏳ **Part 1 is currently being prepared. Please check back soon!**

---

## 🛠️ Part 2 — Project Setup (Windows)

### Step 1 — Create Your Project Folder

Open File Explorer, decide where you want your project to live (e.g., `C:\Projects`), then open Command Prompt inside that folder.

> **Tip:** You can right-click inside the folder in File Explorer and choose **"Open in Terminal"** or **"Open Command Prompt here"**.

Now run:

```bash
python -m django startproject <projectname>_python
```

> Replace `<projectname>` with your desired project name, e.g., `myblog`.

This creates a new folder with your Django project structure inside your current directory.

---

### Step 2 — Navigate Into Your Project

```bash
cd <new_folder_name>
```

> Replace `<new_folder_name>` with the folder that was just created (e.g., `myblog_python`).

---

### Step 3 — Create a Django App

```bash
python -m django startapp <app_name>_app
```

> Replace `<app_name>` with your desired app name, e.g., `blog`.

---

### Step 4 — Open the Project in VS Code

```bash
code .
```

This opens your entire project folder in Visual Studio Code.

---

### Step 5 — Configure `settings.py`

In VS Code, open `settings.py` (located inside the project folder, not the app folder).

#### 5a — Add `os` Import

At the very top of `settings.py`, you'll see:

```python
from pathlib import Path
```

Update it to:

```python
import os
from pathlib import Path
```

---

#### 5b — Register Your App

Find the `INSTALLED_APPS` list and add your app at the bottom:

```python
INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
    'app_name_app',  # 👈 Add your app here
]
```

> Replace `app_name_app` with your actual app name (e.g., `blog_app`).

---

#### 5c — Configure Static and Media Files

Scroll down to the `STATIC_URL` section and replace it with the following:

```python
STATIC_URL = '/static/'
STATICFILES_DIRS = [
    os.path.join(BASE_DIR, 'static')
]

STATIC_ROOT = os.path.join(BASE_DIR, 'staticfiles')
MEDIA_URL = '/media/'
MEDIA_ROOT = os.path.join(BASE_DIR, 'media')
```

---

### Step 6 — Create the Static Folder

In VS Code, create a new folder at the root of your project called:

```
static
```

Your project structure should now look like this:

```
myblog_python/
├── myblog_python/
│   ├── settings.py
│   ├── urls.py
│   └── ...
├── blog_app/
│   └── ...
├── static/        ✅ (newly created)
└── manage.py
```

---

## ⏭️ What's Next?

**Part 3** will cover:

- Creating templates and views
- Setting up URLs
- Connecting your app to the database
- Running the development server

> 🔔 **Star this repository** to get notified when new parts are released!

---

## 🤝 Contributing

Found an error or want to improve this guide? Feel free to open an issue or submit a pull request. All contributions are welcome!

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

<p align="center">Made with ❤️ for Python beginners</p>
