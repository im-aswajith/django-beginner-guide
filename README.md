# 🐍 Python & Django: Zero to Hero
### *The Complete Beginner-Friendly Course — From Your First Line of Code to a Real Website*

> **Who is this for?** Absolute beginners. No experience needed. If you've never written a single line of code in your life — this is your starting point. Even kids can follow along!

---

## 📚 Table of Contents

| # | Topic | Level |
|---|-------|-------|
| 01 | [What is Python? Why Python?](#-chapter-1-what-is-python-why-python) | 🟢 Beginner |
| 02 | [Installing Python & Your First Program](#-chapter-2-installing-python--your-first-program) | 🟢 Beginner |
| 03 | [Variables, Data Types & How Computers Think](#-chapter-3-variables-data-types--how-computers-think) | 🟢 Beginner |
| 04 | [Making Decisions — If, Else, Elif](#-chapter-4-making-decisions--if-else-elif) | 🟢 Beginner |
| 05 | [Loops — Doing Things Over and Over](#-chapter-5-loops--doing-things-over-and-over) | 🟢 Beginner |
| 06 | [Functions — Your Own Superpowers](#-chapter-6-functions--your-own-superpowers) | 🟡 Intermediate |
| 07 | [Lists, Tuples, Dictionaries & Sets](#-chapter-7-lists-tuples-dictionaries--sets) | 🟡 Intermediate |
| 08 | [Object-Oriented Programming (OOP)](#-chapter-8-object-oriented-programming-oop) | 🟡 Intermediate |
| 09 | [File Handling & Working with Data](#-chapter-9-file-handling--working-with-data) | 🟡 Intermediate |
| 10 | [What is Django? The Web Framework](#-chapter-10-what-is-django-the-web-framework) | 🟡 Intermediate |
| 11 | [Setting Up Django — Your First Project](#-chapter-11-setting-up-django--your-first-project) | 🟡 Intermediate |
| 12 | [Django URLs, Views & Templates](#-chapter-12-django-urls-views--templates) | 🟠 Advanced |
| 13 | [Django Models & Databases](#-chapter-13-django-models--databases) | 🟠 Advanced |
| 14 | [Django Forms & User Input](#-chapter-14-django-forms--user-input) | 🟠 Advanced |
| 15 | [Django Admin Panel](#-chapter-15-django-admin-panel) | 🟠 Advanced |
| 16 | [User Authentication — Login & Register](#-chapter-16-user-authentication--login--register) | 🟠 Advanced |
| 17 | [Static Files, CSS & Media](#-chapter-17-static-files-css--media) | 🟠 Advanced |
| 18 | [🌟 REAL PROJECT — Restaurant Website with ThemeWagon](#-chapter-18-real-project--restaurant-website-with-themewagon) | 🔴 Professional |
| 19 | [Deploying Your Website to the Internet](#-chapter-19-deploying-your-website-to-the-internet) | 🔴 Professional |
| 20 | [What's Next? Your Learning Path](#-chapter-20-whats-next-your-learning-path) | 🔴 Professional |

---

## 🌟 Chapter 1: What is Python? Why Python?

### 🧠 Think of it this way...

Imagine you want to tell a robot to make you a sandwich. You need to give it **exact instructions** in a language it understands. Python is that language — but instead of a robot, you're talking to your computer.

Python is:
- 📖 **Easy to read** — it looks almost like English sentences
- 🚀 **Powerful** — used by NASA, Google, Netflix, Instagram
- 🆓 **Free** — 100% open source, always
- 🌍 **In demand** — one of the most hired skills in the world

### 🗺️ What can you build with Python?

```
🌐 Websites & Web Apps        → Django, Flask
🤖 Artificial Intelligence    → TensorFlow, PyTorch
📊 Data Science & Analysis    → Pandas, NumPy
🎮 Games                      → Pygame
🔧 Automation & Bots          → Selenium, Scrapy
📱 Desktop Apps               → Tkinter, PyQt
```

### 💡 Real-Life Analogy

> Python is like a **universal remote control**. You point it at any problem, press the right buttons (write the right code), and it solves it. Learning Python is like learning to drive — once you know it, you can drive any car (solve any problem).

---

## 💻 Chapter 2: Installing Python & Your First Program

### Step 1 — Download Python

1. Go to **https://www.python.org/downloads/**
2. Click the big yellow button **"Download Python 3.x.x"**
3. Run the installer
4. ✅ **VERY IMPORTANT**: Check the box that says **"Add Python to PATH"** before clicking Install

### Step 2 — Verify Installation

Open your **Terminal** (Mac/Linux) or **Command Prompt** (Windows) and type:

```bash
python --version
```

You should see something like:
```
Python 3.12.0
```

🎉 **Congratulations!** Python is installed.

### Step 3 — Install VS Code (Your Code Editor)

Download from: **https://code.visualstudio.com/**

This is where you'll write all your code. Think of it as Microsoft Word, but for programming.

### Step 4 — Your Very First Program

Create a new file called `hello.py` and type:

```python
print("Hello, World!")
print("I am learning Python!")
print("My name is Alex")
```

Run it in your terminal:

```bash
python hello.py
```

**Output:**
```
Hello, World!
I am learning Python!
My name is Alex
```

### 🧒 Kid-Friendly Explanation

> `print()` is like your computer's **speaker**. Whatever you put inside the parentheses with quotes, the computer will say it back to you on screen. The quotes tell Python "this is text, not a command."

---

## 🧠 Chapter 3: Variables, Data Types & How Computers Think

### What is a Variable?

A variable is like a **labeled box** where you store information.

```
📦 Box label: "age"       → contains → 10
📦 Box label: "name"      → contains → "Sarah"
📦 Box label: "height"    → contains → 1.65
📦 Box label: "is_happy"  → contains → True
```

### Creating Variables in Python

```python
name = "Sarah"
age = 10
height = 1.65
is_happy = True

print(name)
print(age)
print(height)
print(is_happy)
```

**Output:**
```
Sarah
10
1.65
True
```

### The 4 Main Data Types

| Type | What it stores | Example |
|------|----------------|---------|
| `str` (String) | Text / Words | `"Hello"`, `"Python"` |
| `int` (Integer) | Whole numbers | `5`, `100`, `-3` |
| `float` | Decimal numbers | `3.14`, `9.99` |
| `bool` (Boolean) | True or False only | `True`, `False` |

### Checking the Type

```python
name = "Sarah"
age = 10
price = 9.99
is_student = True

print(type(name))      # <class 'str'>
print(type(age))       # <class 'int'>
print(type(price))     # <class 'float'>
print(type(is_student))# <class 'bool'>
```

### Math with Variables

```python
apples = 5
oranges = 3

total_fruit = apples + oranges
print("I have", total_fruit, "fruits")

price_per_apple = 0.50
total_cost = apples * price_per_apple
print("Apples cost $", total_cost)
```

**Output:**
```
I have 8 fruits
Apples cost $ 2.5
```

### String Magic (f-strings)

```python
name = "Jake"
age = 12

message = f"Hi! My name is {name} and I am {age} years old."
print(message)
```

**Output:**
```
Hi! My name is Jake and I am 12 years old.
```

> 💡 **The `f` before the string** stands for "formatted". The `{}` curly braces are like windows where you can insert any variable's value.

### Getting Input from the User

```python
name = input("What is your name? ")
print(f"Nice to meet you, {name}!")
```

When you run this, the program **waits for you to type**. If you type "Emma":
```
What is your name? Emma
Nice to meet you, Emma!
```

---

## 🔀 Chapter 4: Making Decisions — If, Else, Elif

### The Real World Logic

Every day you make decisions:
- **IF** it's raining → take an umbrella
- **ELSE** → leave it home

Python works the same way!

### Basic If Statement

```python
age = 15

if age >= 18:
    print("You can vote!")
else:
    print("You're too young to vote.")
```

**Output:**
```
You're too young to vote.
```

### The `elif` (Else If) — Multiple Choices

```python
score = 75

if score >= 90:
    print("Grade: A — Excellent!")
elif score >= 80:
    print("Grade: B — Great!")
elif score >= 70:
    print("Grade: C — Good!")
elif score >= 60:
    print("Grade: D — Keep trying!")
else:
    print("Grade: F — Study harder!")
```

**Output:**
```
Grade: C — Good!
```

### 🧒 Real-Life Example — A Simple Traffic Light

```python
light_color = input("What color is the traffic light? ")

if light_color == "green":
    print("Go! 🟢")
elif light_color == "yellow":
    print("Slow down! 🟡")
elif light_color == "red":
    print("Stop! 🔴")
else:
    print("That's not a valid traffic light color!")
```

### Comparison Operators Cheat Sheet

| Operator | Meaning | Example |
|----------|---------|---------|
| `==` | Equal to | `5 == 5` → True |
| `!=` | Not equal to | `5 != 3` → True |
| `>` | Greater than | `10 > 5` → True |
| `<` | Less than | `3 < 7` → True |
| `>=` | Greater than or equal | `5 >= 5` → True |
| `<=` | Less than or equal | `4 <= 6` → True |

### Combining Conditions with `and` / `or`

```python
age = 20
has_ticket = True

if age >= 18 and has_ticket:
    print("Welcome to the concert! 🎵")
else:
    print("Sorry, you cannot enter.")
```

---

## 🔁 Chapter 5: Loops — Doing Things Over and Over

### Why Do We Need Loops?

Without loops:
```python
print("Hello!")
print("Hello!")
print("Hello!")
print("Hello!")
print("Hello!")
```

With a loop — much smarter:
```python
for i in range(5):
    print("Hello!")
```

Both do the exact same thing! 🎉

### The `for` Loop

```python
fruits = ["apple", "banana", "cherry"]

for fruit in fruits:
    print(f"I love {fruit}!")
```

**Output:**
```
I love apple!
I love banana!
I love cherry!
```

### `range()` — Counting Numbers

```python
for number in range(1, 6):
    print(f"Number: {number}")
```

**Output:**
```
Number: 1
Number: 2
Number: 3
Number: 4
Number: 5
```

> 💡 `range(1, 6)` means: start at 1, stop BEFORE 6. So it gives us 1, 2, 3, 4, 5.

### The `while` Loop

A `while` loop keeps running **as long as a condition is True**.

```python
countdown = 5

while countdown > 0:
    print(f"Launching in {countdown}...")
    countdown = countdown - 1

print("🚀 Blast off!")
```

**Output:**
```
Launching in 5...
Launching in 4...
Launching in 3...
Launching in 2...
Launching in 1...
🚀 Blast off!
```

### Real-Life Example — A Guessing Game

```python
secret_number = 7
guess = 0

print("Guess a number between 1 and 10!")

while guess != secret_number:
    guess = int(input("Your guess: "))
    
    if guess < secret_number:
        print("Too low! Try higher.")
    elif guess > secret_number:
        print("Too high! Try lower.")

print("🎉 You got it! The number was 7!")
```

---

## ⚡ Chapter 6: Functions — Your Own Superpowers

### What is a Function?

A function is a **reusable block of code** that does a specific job. Think of it like a recipe — you write it once, and you can use it as many times as you want.

### Creating a Basic Function

```python
def say_hello():
    print("Hello, everyone!")
    print("Welcome to Python!")

say_hello()
say_hello()
say_hello()
```

**Output:**
```
Hello, everyone!
Welcome to Python!
Hello, everyone!
Welcome to Python!
Hello, everyone!
Welcome to Python!
```

> 💡 `def` means **define**. You're defining (creating) a new function.

### Functions with Parameters (Inputs)

```python
def greet_person(name, age):
    print(f"Hi {name}! You are {age} years old.")

greet_person("Alice", 10)
greet_person("Bob", 25)
greet_person("Charlie", 8)
```

**Output:**
```
Hi Alice! You are 10 years old.
Hi Bob! You are 25 years old.
Hi Charlie! You are 8 years old.
```

### Functions that Return Values

```python
def add_numbers(a, b):
    result = a + b
    return result

sum1 = add_numbers(5, 3)
sum2 = add_numbers(100, 200)

print(f"5 + 3 = {sum1}")
print(f"100 + 200 = {sum2}")
```

**Output:**
```
5 + 3 = 8
100 + 200 = 300
```

### Real-Life Function — Pizza Price Calculator

```python
def calculate_pizza_price(size, extra_toppings):
    base_prices = {
        "small": 8.99,
        "medium": 12.99,
        "large": 16.99
    }
    
    base = base_prices[size]
    topping_cost = extra_toppings * 1.50
    total = base + topping_cost
    
    return total

my_pizza = calculate_pizza_price("large", 3)
print(f"Your pizza costs: ${my_pizza:.2f}")
```

**Output:**
```
Your pizza costs: $21.49
```

---

## 📦 Chapter 7: Lists, Tuples, Dictionaries & Sets

### Lists — Ordered Collections

A list is like a **shopping cart**. You can add items, remove items, and change what's inside.

```python
shopping_cart = ["apples", "bread", "milk", "eggs"]

print(shopping_cart[0])    # apples  (first item)
print(shopping_cart[2])    # milk    (third item)
print(shopping_cart[-1])   # eggs    (last item)
```

#### List Operations

```python
fruits = ["apple", "banana", "cherry"]

fruits.append("mango")       # Add to end
fruits.insert(1, "kiwi")     # Add at position 1
fruits.remove("banana")      # Remove by value
popped = fruits.pop()        # Remove & return last item

print(fruits)
print(f"Removed: {popped}")
print(f"Total fruits: {len(fruits)}")
```

### Tuples — Unchangeable Lists

A tuple is like a list, but **locked** — you can't change it after creating it. Good for data that should never change (like coordinates, colors).

```python
coordinates = (40.7128, -74.0060)   # New York City location
rgb_red = (255, 0, 0)               # Red color in RGB

print(f"New York: {coordinates}")
print(f"Red color: {rgb_red}")
```

### Dictionaries — Key-Value Pairs

A dictionary is like a **real dictionary** — you look up a word (key) and get its meaning (value).

```python
student = {
    "name": "Emma",
    "age": 15,
    "grade": "10th",
    "favorite_subject": "Math",
    "gpa": 3.8
}

print(student["name"])
print(student["gpa"])

student["age"] = 16
student["hobby"] = "painting"

print(student)
```

**Output:**
```
Emma
3.8
{'name': 'Emma', 'age': 16, 'grade': '10th', 'favorite_subject': 'Math', 'gpa': 3.8, 'hobby': 'painting'}
```

#### Real-Life Dictionary — A Menu System

```python
restaurant_menu = {
    "burger": 8.99,
    "pizza": 12.50,
    "pasta": 10.99,
    "salad": 7.50,
    "soda": 2.99
}

order = input("What would you like to order? ").lower()

if order in restaurant_menu:
    price = restaurant_menu[order]
    print(f"✅ {order.title()} costs ${price:.2f}")
else:
    print("❌ Sorry, that item is not on our menu.")
```

---

## 🏗️ Chapter 8: Object-Oriented Programming (OOP)

### What is OOP? (The Simple Explanation)

Think about a **Dog**. Every dog has:
- **Attributes** (characteristics): name, breed, age, color
- **Methods** (things it can do): bark, sit, run, eat

OOP lets you create a **blueprint (class)** for things, then create as many copies (objects) as you want.

### Creating Your First Class

```python
class Dog:
    def __init__(self, name, breed, age):
        self.name = name
        self.breed = breed
        self.age = age
    
    def bark(self):
        print(f"{self.name} says: Woof! Woof! 🐕")
    
    def introduce(self):
        print(f"Hi! I'm {self.name}, a {self.age}-year-old {self.breed}.")
    
    def birthday(self):
        self.age += 1
        print(f"Happy birthday {self.name}! You are now {self.age}! 🎂")


dog1 = Dog("Buddy", "Golden Retriever", 3)
dog2 = Dog("Max", "German Shepherd", 5)
dog3 = Dog("Luna", "Poodle", 1)

dog1.bark()
dog2.introduce()
dog3.birthday()
```

**Output:**
```
Buddy says: Woof! Woof! 🐕
Hi! I'm Max, a 5-year-old German Shepherd.
Happy birthday Luna! You are now 2! 🎂
```

### Inheritance — Classes Building on Classes

```python
class Animal:
    def __init__(self, name, age):
        self.name = name
        self.age = age
    
    def eat(self):
        print(f"{self.name} is eating 🍽️")
    
    def sleep(self):
        print(f"{self.name} is sleeping 😴")


class Cat(Animal):
    def __init__(self, name, age, indoor):
        super().__init__(name, age)
        self.indoor = indoor
    
    def meow(self):
        print(f"{self.name} says: Meow! 🐱")
    
    def purr(self):
        print(f"{self.name} is purring... 😻")


class Bird(Animal):
    def __init__(self, name, age, can_fly):
        super().__init__(name, age)
        self.can_fly = can_fly
    
    def chirp(self):
        print(f"{self.name} says: Tweet tweet! 🐦")


my_cat = Cat("Whiskers", 3, True)
my_bird = Bird("Tweety", 1, True)

my_cat.eat()
my_cat.meow()
my_cat.purr()
my_bird.sleep()
my_bird.chirp()
```

---

## 📁 Chapter 9: File Handling & Working with Data

### Reading & Writing Files

```python
with open("my_notes.txt", "w") as file:
    file.write("Python is awesome!\n")
    file.write("I love coding!\n")
    file.write("This is my first file.\n")

print("File written successfully!")

with open("my_notes.txt", "r") as file:
    content = file.read()
    print(content)
```

### Working with JSON (The Internet's Language)

```python
import json

student_data = {
    "name": "Alice",
    "age": 15,
    "subjects": ["Math", "Science", "English"],
    "grades": {"Math": 95, "Science": 88, "English": 92}
}

with open("student.json", "w") as file:
    json.dump(student_data, file, indent=4)

with open("student.json", "r") as file:
    loaded_data = json.load(file)

print(f"Student: {loaded_data['name']}")
print(f"Math Grade: {loaded_data['grades']['Math']}")
print(f"Subjects: {', '.join(loaded_data['subjects'])}")
```

**Output:**
```
Student: Alice
Math Grade: 95
Subjects: Math, Science, English
```

---

## 🌐 Chapter 10: What is Django? The Web Framework

### The Big Picture

When you visit a website like YouTube or Instagram, here's what happens:

```
You type youtube.com  →  Your browser sends a REQUEST
                      →  YouTube's server receives it
                      →  Server looks up the right content
                      →  Server sends back a RESPONSE (the webpage)
                      →  Your browser displays it
```

**Django** is the tool that handles all the middle parts — receiving requests, talking to databases, and sending back responses.

### The MVT Architecture (Don't Panic!)

Django uses a pattern called **MVT**:

```
📋 Model   = The DATA (what you store in the database)
🎨 View    = The LOGIC (what to do with the data)
📄 Template = The LOOK (the HTML the user sees)
```

> 💡 **Simple analogy**: Think of a restaurant.
> - **Model** = The kitchen & ingredients (data storage)
> - **View** = The chef (decides what to cook and how)
> - **Template** = The plate presentation (what the customer sees)

---

## 🛠️ Chapter 11: Setting Up Django — Your First Project

### Install Django

```bash
pip install django
```

Verify installation:
```bash
django-admin --version
```

### Create Your First Django Project

```bash
django-admin startproject mywebsite
cd mywebsite
```

Your project structure will look like:
```
mywebsite/
│
├── manage.py           ← Your command center
├── mywebsite/
│   ├── __init__.py
│   ├── settings.py    ← Configuration
│   ├── urls.py        ← URL routing
│   ├── asgi.py
│   └── wsgi.py
```

### Run the Development Server

```bash
python manage.py runserver
```

Open your browser and go to: **http://127.0.0.1:8000/**

🎉 You should see the Django welcome page! Your web server is running!

### Create Your First App

In Django, a **project** is the whole website. An **app** is one feature/section of the website.

```bash
python manage.py startapp pages
```

Register it in `mywebsite/settings.py`:

```python
INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
    'pages',          # ← Add your app here
]
```

---

## 🔗 Chapter 12: Django URLs, Views & Templates

### Step 1 — Create a View

In `pages/views.py`:

```python
from django.shortcuts import render
from django.http import HttpResponse


def home(request):
    return HttpResponse("<h1>Welcome to My Website!</h1>")


def about(request):
    return HttpResponse("<h1>About Us</h1><p>We are awesome!</p>")
```

### Step 2 — Create URLs for Your App

Create a new file `pages/urls.py`:

```python
from django.urls import path
from . import views

urlpatterns = [
    path('', views.home, name='home'),
    path('about/', views.about, name='about'),
]
```

### Step 3 — Connect to the Main URLs

In `mywebsite/urls.py`:

```python
from django.contrib import admin
from django.urls import path, include

urlpatterns = [
    path('admin/', admin.site.urls),
    path('', include('pages.urls')),
]
```

### Step 4 — Using HTML Templates

Create the folder structure:
```
pages/
└── templates/
    └── pages/
        ├── home.html
        └── about.html
```

Create `pages/templates/pages/home.html`:

```html
<!DOCTYPE html>
<html>
<head>
    <title>My Website</title>
</head>
<body>
    <h1>Welcome, {{ name }}!</h1>
    <p>Today we are learning Django.</p>
    <nav>
        <a href="/">Home</a> |
        <a href="/about/">About</a>
    </nav>
</body>
</html>
```

Update your view in `pages/views.py` to use the template:

```python
from django.shortcuts import render


def home(request):
    context = {
        'name': 'World',
        'message': 'Django is amazing!'
    }
    return render(request, 'pages/home.html', context)
```

> 💡 **{{ name }}** in HTML is called a **template variable**. Django replaces it with the actual value from your Python view. This is the magic bridge between Python and HTML!

---

## 🗄️ Chapter 13: Django Models & Databases

### What is a Model?

A **model** is a Python class that represents a database table. Each attribute becomes a column.

```
Python Class  →  Database Table
-----------      --------------
Article       →  articles
  title       →  title (column)
  content     →  content (column)
  date        →  date (column)
  author      →  author (column)
```

### Creating a Model

In `pages/models.py`:

```python
from django.db import models


class Article(models.Model):
    title = models.CharField(max_length=200)
    content = models.TextField()
    author = models.CharField(max_length=100)
    published_date = models.DateTimeField(auto_now_add=True)
    is_published = models.BooleanField(default=False)
    
    def __str__(self):
        return self.title
    
    class Meta:
        ordering = ['-published_date']
```

### Migrations — Telling Django to Create the Table

```bash
python manage.py makemigrations
python manage.py migrate
```

> 💡 **makemigrations** creates instruction files. **migrate** executes them and creates the actual tables in your database. Always run both together!

### Using the Django Shell to Test

```bash
python manage.py shell
```

```python
from pages.models import Article

article1 = Article(
    title="My First Article",
    content="This is the content of my first article.",
    author="Alice",
    is_published=True
)
article1.save()

article2 = Article.objects.create(
    title="Django is Amazing",
    content="Here's why Django is the best web framework...",
    author="Bob",
    is_published=True
)

all_articles = Article.objects.all()
for article in all_articles:
    print(article.title)

alice_articles = Article.objects.filter(author="Alice")
print(alice_articles)

single = Article.objects.get(id=1)
print(single.title)
```

### Displaying Database Data in Views

```python
from django.shortcuts import render
from .models import Article


def article_list(request):
    articles = Article.objects.filter(is_published=True)
    context = {'articles': articles}
    return render(request, 'pages/article_list.html', context)
```

Template `pages/templates/pages/article_list.html`:

```html
<!DOCTYPE html>
<html>
<body>
    <h1>All Articles</h1>
    
    {% for article in articles %}
        <div>
            <h2>{{ article.title }}</h2>
            <p>By {{ article.author }} on {{ article.published_date|date:"F j, Y" }}</p>
            <p>{{ article.content }}</p>
        </div>
    {% empty %}
        <p>No articles found.</p>
    {% endfor %}
</body>
</html>
```

---

## 📝 Chapter 14: Django Forms & User Input

### Creating a Form Class

Create `pages/forms.py`:

```python
from django import forms


class ContactForm(forms.Form):
    name = forms.CharField(
        max_length=100,
        widget=forms.TextInput(attrs={
            'placeholder': 'Your Name',
            'class': 'form-control'
        })
    )
    email = forms.EmailField(
        widget=forms.EmailInput(attrs={
            'placeholder': 'your@email.com',
            'class': 'form-control'
        })
    )
    message = forms.CharField(
        widget=forms.Textarea(attrs={
            'placeholder': 'Your message here...',
            'class': 'form-control',
            'rows': 5
        })
    )
```

### Handling the Form in Views

```python
from django.shortcuts import render, redirect
from .forms import ContactForm


def contact(request):
    if request.method == 'POST':
        form = ContactForm(request.POST)
        if form.is_valid():
            name = form.cleaned_data['name']
            email = form.cleaned_data['email']
            message = form.cleaned_data['message']
            print(f"Message from {name} ({email}): {message}")
            return redirect('contact_success')
    else:
        form = ContactForm()
    
    return render(request, 'pages/contact.html', {'form': form})
```

### The Contact Template

```html
<!DOCTYPE html>
<html>
<body>
    <h1>Contact Us</h1>
    
    <form method="POST">
        {% csrf_token %}
        
        <div>
            <label>Name</label>
            {{ form.name }}
            {% if form.name.errors %}
                <p style="color:red;">{{ form.name.errors }}</p>
            {% endif %}
        </div>
        
        <div>
            <label>Email</label>
            {{ form.email }}
        </div>
        
        <div>
            <label>Message</label>
            {{ form.message }}
        </div>
        
        <button type="submit">Send Message</button>
    </form>
</body>
</html>
```

> 💡 `{% csrf_token %}` is a security protection Django requires on all forms. It prevents hackers from faking form submissions. NEVER forget it!

---

## 👑 Chapter 15: Django Admin Panel

### Create a Superuser

```bash
python manage.py createsuperuser
```

Enter username, email, and password when prompted.

### Register Your Models

In `pages/admin.py`:

```python
from django.contrib import admin
from .models import Article


@admin.register(Article)
class ArticleAdmin(admin.ModelAdmin):
    list_display = ['title', 'author', 'published_date', 'is_published']
    list_filter = ['is_published', 'author']
    search_fields = ['title', 'content']
    list_editable = ['is_published']
    date_hierarchy = 'published_date'
    ordering = ['-published_date']
```

Now go to **http://127.0.0.1:8000/admin/** and log in.

You'll see a powerful dashboard where you can:
- Create, edit, delete articles
- Search and filter
- All without writing a single SQL query!

---

## 🔐 Chapter 16: User Authentication — Login & Register

### Enable Django's Built-in Auth

In `mywebsite/urls.py`:

```python
from django.contrib import admin
from django.urls import path, include

urlpatterns = [
    path('admin/', admin.site.urls),
    path('', include('pages.urls')),
    path('accounts/', include('django.contrib.auth.urls')),
]
```

### Create Registration View

In `pages/views.py`:

```python
from django.shortcuts import render, redirect
from django.contrib.auth.forms import UserCreationForm
from django.contrib.auth import login
from django.contrib.auth.decorators import login_required


def register(request):
    if request.method == 'POST':
        form = UserCreationForm(request.POST)
        if form.is_valid():
            user = form.save()
            login(request, user)
            return redirect('home')
    else:
        form = UserCreationForm()
    return render(request, 'registration/register.html', {'form': form})


@login_required
def dashboard(request):
    return render(request, 'pages/dashboard.html', {'user': request.user})
```

### Settings for Auth Redirects

Add to `settings.py`:

```python
LOGIN_REDIRECT_URL = '/'
LOGOUT_REDIRECT_URL = '/'
LOGIN_URL = '/accounts/login/'
```

---

## 🎨 Chapter 17: Static Files, CSS & Media

### Setting Up Static Files

In `settings.py`:

```python
import os

STATIC_URL = '/static/'
STATICFILES_DIRS = [os.path.join(BASE_DIR, 'static')]
STATIC_ROOT = os.path.join(BASE_DIR, 'staticfiles')

MEDIA_URL = '/media/'
MEDIA_ROOT = os.path.join(BASE_DIR, 'media')
```

Create folder structure:
```
mywebsite/
└── static/
    ├── css/
    │   └── style.css
    ├── js/
    │   └── main.js
    └── images/
        └── logo.png
```

### Using Static Files in Templates

```html
{% load static %}
<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" href="{% static 'css/style.css' %}">
</head>
<body>
    <img src="{% static 'images/logo.png' %}" alt="Logo">
    <script src="{% static 'js/main.js' %}"></script>
</body>
</html>
```

---

## 🌟 Chapter 18: REAL PROJECT — Restaurant Website with ThemeWagon

### 🎯 Project Overview

We'll build a **fully functional restaurant website** using:
- **Django** as the backend
- **[Feane — Free Bootstrap Restaurant Template](https://themewagon.com/themes/feane/)** from ThemeWagon
- A real **menu**, **booking system**, and **contact form**

**Live Demo Preview:** [https://themewagon.github.io/feane/](https://themewagon.github.io/feane/)

---

### 📁 Project Setup

```bash
django-admin startproject restaurant_project
cd restaurant_project
python manage.py startapp restaurant
pip install django pillow
```

Register the app in `settings.py`:
```python
INSTALLED_APPS = [
    ...
    'restaurant',
]
```

---

### 🗄️ Step 1 — Create the Database Models

In `restaurant/models.py`:

```python
from django.db import models


class Category(models.Model):
    name = models.CharField(max_length=100)
    icon = models.CharField(max_length=50, default='🍽️')
    
    class Meta:
        verbose_name_plural = 'Categories'
    
    def __str__(self):
        return self.name


class MenuItem(models.Model):
    category = models.ForeignKey(Category, on_delete=models.CASCADE, related_name='items')
    name = models.CharField(max_length=200)
    description = models.TextField()
    price = models.DecimalField(max_digits=6, decimal_places=2)
    image = models.ImageField(upload_to='menu/', null=True, blank=True)
    is_special = models.BooleanField(default=False)
    is_available = models.BooleanField(default=True)
    created_at = models.DateTimeField(auto_now_add=True)
    
    def __str__(self):
        return f"{self.name} - ${self.price}"


class Booking(models.Model):
    PARTY_SIZE_CHOICES = [(i, str(i)) for i in range(1, 11)]
    
    TIME_CHOICES = [
        ('12:00', '12:00 PM'),
        ('13:00', '1:00 PM'),
        ('14:00', '2:00 PM'),
        ('18:00', '6:00 PM'),
        ('19:00', '7:00 PM'),
        ('20:00', '8:00 PM'),
        ('21:00', '9:00 PM'),
    ]
    
    name = models.CharField(max_length=100)
    email = models.EmailField()
    phone = models.CharField(max_length=20)
    date = models.DateField()
    time = models.CharField(max_length=10, choices=TIME_CHOICES)
    party_size = models.IntegerField(choices=PARTY_SIZE_CHOICES, default=2)
    special_request = models.TextField(blank=True)
    created_at = models.DateTimeField(auto_now_add=True)
    
    def __str__(self):
        return f"{self.name} — {self.date} at {self.time}"


class ContactMessage(models.Model):
    name = models.CharField(max_length=100)
    email = models.EmailField()
    subject = models.CharField(max_length=200)
    message = models.TextField()
    sent_at = models.DateTimeField(auto_now_add=True)
    is_read = models.BooleanField(default=False)
    
    def __str__(self):
        return f"{self.name}: {self.subject}"
```

---

### 📋 Step 2 — Create the Forms

Create `restaurant/forms.py`:

```python
from django import forms
from .models import Booking, ContactMessage
import datetime


class BookingForm(forms.ModelForm):
    date = forms.DateField(
        widget=forms.DateInput(attrs={
            'type': 'date',
            'class': 'form-control',
            'min': datetime.date.today().strftime('%Y-%m-%d')
        })
    )
    
    class Meta:
        model = Booking
        fields = ['name', 'email', 'phone', 'date', 'time', 'party_size', 'special_request']
        widgets = {
            'name': forms.TextInput(attrs={'class': 'form-control', 'placeholder': 'Your Name'}),
            'email': forms.EmailInput(attrs={'class': 'form-control', 'placeholder': 'Email'}),
            'phone': forms.TextInput(attrs={'class': 'form-control', 'placeholder': 'Phone Number'}),
            'time': forms.Select(attrs={'class': 'form-control'}),
            'party_size': forms.Select(attrs={'class': 'form-control'}),
            'special_request': forms.Textarea(attrs={
                'class': 'form-control',
                'rows': 3,
                'placeholder': 'Any special requests or dietary requirements?'
            }),
        }
    
    def clean_date(self):
        date = self.cleaned_data.get('date')
        if date and date < datetime.date.today():
            raise forms.ValidationError("You cannot book a table in the past!")
        return date


class ContactForm(forms.ModelForm):
    class Meta:
        model = ContactMessage
        fields = ['name', 'email', 'subject', 'message']
        widgets = {
            'name': forms.TextInput(attrs={'class': 'form-control', 'placeholder': 'Your Name'}),
            'email': forms.EmailInput(attrs={'class': 'form-control', 'placeholder': 'Email'}),
            'subject': forms.TextInput(attrs={'class': 'form-control', 'placeholder': 'Subject'}),
            'message': forms.Textarea(attrs={
                'class': 'form-control',
                'rows': 5,
                'placeholder': 'Your message...'
            }),
        }
```

---

### 👀 Step 3 — Create the Views

In `restaurant/views.py`:

```python
from django.shortcuts import render, redirect
from django.contrib import messages
from .models import MenuItem, Category, Booking
from .forms import BookingForm, ContactForm


def home(request):
    specials = MenuItem.objects.filter(is_special=True, is_available=True)[:6]
    categories = Category.objects.all()
    
    context = {
        'specials': specials,
        'categories': categories,
    }
    return render(request, 'restaurant/home.html', context)


def menu(request):
    categories = Category.objects.prefetch_related('items').all()
    selected_category = request.GET.get('category', 'all')
    
    if selected_category != 'all':
        menu_items = MenuItem.objects.filter(
            category__name__iexact=selected_category,
            is_available=True
        )
    else:
        menu_items = MenuItem.objects.filter(is_available=True)
    
    context = {
        'categories': categories,
        'menu_items': menu_items,
        'selected_category': selected_category,
    }
    return render(request, 'restaurant/menu.html', context)


def booking(request):
    if request.method == 'POST':
        form = BookingForm(request.POST)
        if form.is_valid():
            booking_obj = form.save()
            messages.success(
                request,
                f"✅ Table booked successfully for {booking_obj.name} on "
                f"{booking_obj.date} at {booking_obj.time}. We'll see you soon!"
            )
            return redirect('booking_success')
        else:
            messages.error(request, "❌ Please correct the errors below.")
    else:
        form = BookingForm()
    
    return render(request, 'restaurant/booking.html', {'form': form})


def booking_success(request):
    return render(request, 'restaurant/booking_success.html')


def contact(request):
    if request.method == 'POST':
        form = ContactForm(request.POST)
        if form.is_valid():
            form.save()
            messages.success(request, "✅ Message sent! We'll get back to you within 24 hours.")
            return redirect('contact')
    else:
        form = ContactForm()
    
    return render(request, 'restaurant/contact.html', {'form': form})
```

---

### 🔗 Step 4 — Configure URLs

Create `restaurant/urls.py`:

```python
from django.urls import path
from . import views

urlpatterns = [
    path('', views.home, name='home'),
    path('menu/', views.menu, name='menu'),
    path('booking/', views.booking, name='booking'),
    path('booking/success/', views.booking_success, name='booking_success'),
    path('contact/', views.contact, name='contact'),
]
```

In `restaurant_project/urls.py`:

```python
from django.contrib import admin
from django.urls import path, include
from django.conf import settings
from django.conf.urls.static import static

urlpatterns = [
    path('admin/', admin.site.urls),
    path('', include('restaurant.urls')),
] + static(settings.MEDIA_URL, document_root=settings.MEDIA_ROOT)
```

---

### 🎨 Step 5 — Download & Integrate ThemeWagon Template

1. Go to **https://themewagon.com/themes/feane/**
2. Click **"Free Download"**
3. Extract the ZIP file
4. Copy all files into your Django static folder:

```
restaurant/
└── static/
    └── restaurant/
        ├── css/
        │   ├── bootstrap.min.css
        │   ├── style.css
        │   └── responsive.css
        ├── js/
        │   ├── jquery.min.js
        │   ├── bootstrap.bundle.min.js
        │   └── custom.js
        └── images/
            ├── hero-bg.jpg
            ├── food1.jpg
            └── ...
```

---

### 🏠 Step 6 — Create the Base Template

Create `restaurant/templates/restaurant/base.html`:

```html
{% load static %}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{% block title %}Feane Restaurant{% endblock %}</title>
    
    <link rel="stylesheet" href="{% static 'restaurant/css/bootstrap.min.css' %}">
    <link rel="stylesheet" href="{% static 'restaurant/css/style.css' %}">
    <link rel="stylesheet" href="{% static 'restaurant/css/responsive.css' %}">
    
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    {% block extra_css %}{% endblock %}
</head>
<body>

    <div class="hero_area">
        <header class="header_section">
            <div class="container-fluid">
                <nav class="navbar navbar-expand-lg custom_nav-container">
                    <a class="navbar-brand" href="{% url 'home' %}">
                        <span>Feane</span>
                    </a>
                    
                    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent">
                        <span class="navbar-toggler-icon"></span>
                    </button>
                    
                    <div class="collapse navbar-collapse" id="navbarSupportedContent">
                        <ul class="navbar-nav ml-auto">
                            <li class="nav-item {% block nav_home %}{% endblock %}">
                                <a class="nav-link" href="{% url 'home' %}">Home</a>
                            </li>
                            <li class="nav-item {% block nav_menu %}{% endblock %}">
                                <a class="nav-link" href="{% url 'menu' %}">Menu</a>
                            </li>
                            <li class="nav-item {% block nav_booking %}{% endblock %}">
                                <a class="nav-link" href="{% url 'booking' %}">Book A Table</a>
                            </li>
                            <li class="nav-item {% block nav_contact %}{% endblock %}">
                                <a class="nav-link" href="{% url 'contact' %}">Contact Us</a>
                            </li>
                        </ul>
                    </div>
                </nav>
            </div>
        </header>
        
        {% block hero %}{% endblock %}
    </div>

    {% if messages %}
    <div class="container mt-3">
        {% for message in messages %}
        <div class="alert alert-{% if message.tags == 'error' %}danger{% else %}{{ message.tags }}{% endif %} alert-dismissible fade show" role="alert">
            {{ message }}
            <button type="button" class="close" data-dismiss="alert">&times;</button>
        </div>
        {% endfor %}
    </div>
    {% endif %}

    {% block content %}{% endblock %}

    <section class="info_section layout_padding2">
        <div class="container">
            <div class="row">
                <div class="col-md-6 col-lg-3 info_col">
                    <div class="info_contact">
                        <h4>Address</h4>
                        <div class="contact_link_box">
                            <a href="#"><i class="fa fa-map-marker" aria-hidden="true"></i>
                                <span>Location</span>
                            </a>
                            <a href="tel:+11234567890"><i class="fa fa-phone" aria-hidden="true"></i>
                                <span>+1 123-456-7890</span>
                            </a>
                            <a href="mailto:info@feane.com"><i class="fa fa-envelope" aria-hidden="true"></i>
                                <span>info@feane.com</span>
                            </a>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-lg-3 info_col">
                    <div class="info_detail">
                        <h4>Info</h4>
                        <p>Welcome to Feane. We serve quality food with love and care.</p>
                    </div>
                </div>
                <div class="col-md-6 col-lg-3 info_col">
                    <div class="info_link_box">
                        <h4>Links</h4>
                        <div class="info_links">
                            <a href="{% url 'home' %}">Home</a>
                            <a href="{% url 'menu' %}">Menu</a>
                            <a href="{% url 'booking' %}">Book A Table</a>
                            <a href="{% url 'contact' %}">Contact</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-lg-3 info_col">
                    <h4>Follow Us</h4>
                    <div class="social_box">
                        <a href="#"><i class="fa-brands fa-facebook-f"></i></a>
                        <a href="#"><i class="fa-brands fa-twitter"></i></a>
                        <a href="#"><i class="fa-brands fa-instagram"></i></a>
                        <a href="#"><i class="fa-brands fa-youtube"></i></a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="footer_section">
        <div class="container">
            <p>&copy; <span id="displayYear"></span> All Rights Reserved — Feane Restaurant</p>
        </div>
    </section>

    <script src="{% static 'restaurant/js/jquery.min.js' %}"></script>
    <script src="{% static 'restaurant/js/bootstrap.bundle.min.js' %}"></script>
    <script>
        document.getElementById('displayYear').textContent = new Date().getFullYear();
    </script>
    {% block extra_js %}{% endblock %}
</body>
</html>
```

---

### 🏠 Step 7 — Create the Home Page

`restaurant/templates/restaurant/home.html`:

```html
{% extends 'restaurant/base.html' %}
{% load static %}

{% block title %}Feane Restaurant — Home{% endblock %}
{% block nav_home %}active{% endblock %}

{% block hero %}
<section class="slider_section">
    <div class="slider_bg_box">
        <img src="{% static 'restaurant/images/hero-bg.jpg' %}" alt="Hero Background">
    </div>
    <div class="container">
        <div class="row">
            <div class="col-md-7 col-lg-6">
                <div class="detail-box">
                    <h1>Fast Food <br>Restaurant</h1>
                    <p>
                        There are many variations of passages of Lorem Ipsum available,
                        but the majority have suffered alteration.
                    </p>
                    <div class="btn-box">
                        <a href="{% url 'menu' %}" class="btn1">Order Now</a>
                        <a href="{% url 'booking' %}" class="btn2">Book A Table</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>
{% endblock %}

{% block content %}

<section class="offer_section layout_padding-bottom">
    <div class="offer_container">
        <div class="container">
            <div class="row">
                <div class="col-lg-7">
                    <div class="detail-box">
                        <div class="heading_container">
                            <h2>We Offer Great Food At Great Prices</h2>
                        </div>
                        <p>
                            Quality is our promise. Every dish is prepared fresh daily
                            with the finest ingredients sourced from local farmers.
                        </p>
                        <a href="{% url 'menu' %}">Read More</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<section class="food_section layout_padding-bottom">
    <div class="container">
        <div class="heading_container heading_center">
            <h2>Our <span>Special</span> Dishes</h2>
        </div>

        <div class="row">
            {% for item in specials %}
            <div class="col-sm-6 col-lg-4">
                <div class="box">
                    <div class="img-box">
                        {% if item.image %}
                            <img src="{{ item.image.url }}" alt="{{ item.name }}">
                        {% else %}
                            <img src="{% static 'restaurant/images/food1.jpg' %}" alt="{{ item.name }}">
                        {% endif %}
                    </div>
                    <div class="detail-box">
                        <div class="detail-top">
                            <h5>{{ item.name }}</h5>
                            <h5>${{ item.price }}</h5>
                        </div>
                        <p>{{ item.description|truncatewords:15 }}</p>
                        <div class="options">
                            <button>
                                <i class="fa fa-shopping-cart" aria-hidden="true"></i>
                            </button>
                            <h6><span>$</span>{{ item.price }}</h6>
                        </div>
                    </div>
                </div>
            </div>
            {% empty %}
            <div class="col-12 text-center">
                <p>No special dishes available at the moment. Check back soon!</p>
            </div>
            {% endfor %}
        </div>

        <div class="btn-box">
            <a href="{% url 'menu' %}">View Full Menu</a>
        </div>
    </div>
</section>

<section class="book_section layout_padding">
    <div class="container">
        <div class="heading_container">
            <h2>Book A Table</h2>
        </div>
        <div class="row">
            <div class="col-md-6">
                <div class="form_container">
                    <form method="POST" action="{% url 'booking' %}">
                        {% csrf_token %}
                        <div class="form-group">
                            <input type="text" name="name" class="form-control" placeholder="Your Name" required>
                        </div>
                        <div class="form-group">
                            <input type="email" name="email" class="form-control" placeholder="Email" required>
                        </div>
                        <div class="form-group">
                            <input type="tel" name="phone" class="form-control" placeholder="Phone Number" required>
                        </div>
                        <div class="form-group">
                            <a href="{% url 'booking' %}" class="btn" style="background:#ffbe33; color:#fff; display:block; text-align:center; padding:10px;">
                                Book Full Reservation →
                            </a>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </div>
</section>

{% endblock %}
```

---

### 📋 Step 8 — Create the Menu Page

`restaurant/templates/restaurant/menu.html`:

```html
{% extends 'restaurant/base.html' %}
{% load static %}

{% block title %}Menu — Feane Restaurant{% endblock %}
{% block nav_menu %}active{% endblock %}

{% block content %}
<section class="food_section layout_padding">
    <div class="container">
        <div class="heading_container heading_center">
            <h2>Our <span>Menu</span></h2>
        </div>

        <ul class="filters_menu">
            <li {% if selected_category == 'all' %}class="active"{% endif %}>
                <a href="{% url 'menu' %}">All</a>
            </li>
            {% for category in categories %}
            <li {% if selected_category == category.name %}class="active"{% endif %}>
                <a href="?category={{ category.name }}">{{ category.name }}</a>
            </li>
            {% endfor %}
        </ul>

        <div class="row">
            {% for item in menu_items %}
            <div class="col-sm-6 col-lg-4">
                <div class="box">
                    <div class="img-box">
                        {% if item.image %}
                            <img src="{{ item.image.url }}" alt="{{ item.name }}">
                        {% else %}
                            <img src="{% static 'restaurant/images/food1.jpg' %}" alt="{{ item.name }}">
                        {% endif %}
                        {% if item.is_special %}
                            <span class="badge" style="position:absolute; top:10px; left:10px; background:#ffbe33; padding:5px 10px; border-radius:15px; color:#fff; font-size:12px;">
                                ⭐ Special
                            </span>
                        {% endif %}
                    </div>
                    <div class="detail-box">
                        <div class="detail-top">
                            <h5>{{ item.name }}</h5>
                            <h5>${{ item.price }}</h5>
                        </div>
                        <p>{{ item.description }}</p>
                        <div class="options">
                            <button>
                                <i class="fa fa-shopping-cart" aria-hidden="true"></i>
                            </button>
                            <h6><span>$</span>{{ item.price }}</h6>
                        </div>
                    </div>
                </div>
            </div>
            {% empty %}
            <div class="col-12 text-center py-5">
                <p style="font-size:18px;">No items found in this category.</p>
                <a href="{% url 'menu' %}" class="btn" style="background:#ffbe33; color:#fff;">View All Items</a>
            </div>
            {% endfor %}
        </div>
    </div>
</section>
{% endblock %}
```

---

### 📅 Step 9 — Create the Booking Page

`restaurant/templates/restaurant/booking.html`:

```html
{% extends 'restaurant/base.html' %}
{% load static %}

{% block title %}Book A Table — Feane Restaurant{% endblock %}
{% block nav_booking %}active{% endblock %}

{% block content %}
<section class="book_section layout_padding">
    <div class="container">
        <div class="heading_container">
            <h2>Book A Table</h2>
            <p>Reserve your table in advance and enjoy a memorable dining experience.</p>
        </div>
        
        <div class="row justify-content-center">
            <div class="col-md-8 col-lg-6">
                <div class="form_container" style="background:#fff; padding:30px; border-radius:10px; box-shadow:0 5px 20px rgba(0,0,0,0.1);">
                    <form method="POST">
                        {% csrf_token %}
                        
                        <div class="form-group">
                            <label>Your Name *</label>
                            {{ form.name }}
                            {% if form.name.errors %}
                                <small class="text-danger">{{ form.name.errors.0 }}</small>
                            {% endif %}
                        </div>
                        
                        <div class="row">
                            <div class="col-md-6">
                                <div class="form-group">
                                    <label>Email *</label>
                                    {{ form.email }}
                                </div>
                            </div>
                            <div class="col-md-6">
                                <div class="form-group">
                                    <label>Phone *</label>
                                    {{ form.phone }}
                                </div>
                            </div>
                        </div>
                        
                        <div class="row">
                            <div class="col-md-6">
                                <div class="form-group">
                                    <label>Date *</label>
                                    {{ form.date }}
                                    {% if form.date.errors %}
                                        <small class="text-danger">{{ form.date.errors.0 }}</small>
                                    {% endif %}
                                </div>
                            </div>
                            <div class="col-md-6">
                                <div class="form-group">
                                    <label>Time *</label>
                                    {{ form.time }}
                                </div>
                            </div>
                        </div>
                        
                        <div class="form-group">
                            <label>Number of Guests *</label>
                            {{ form.party_size }}
                        </div>
                        
                        <div class="form-group">
                            <label>Special Requests</label>
                            {{ form.special_request }}
                        </div>
                        
                        <button type="submit" class="btn" style="background:#ffbe33; color:#fff; width:100%; padding:12px; font-size:16px; border-radius:5px;">
                            Confirm Reservation 🍽️
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </div>
</section>
{% endblock %}
```

---

### ✅ Step 10 — Create the Success Page

`restaurant/templates/restaurant/booking_success.html`:

```html
{% extends 'restaurant/base.html' %}

{% block title %}Booking Confirmed! — Feane Restaurant{% endblock %}

{% block content %}
<section class="layout_padding" style="text-align:center; padding:80px 0;">
    <div class="container">
        <div style="font-size:80px;">🎉</div>
        <h2 style="color:#ffbe33; margin:20px 0;">Booking Confirmed!</h2>
        <p style="font-size:18px; max-width:500px; margin:0 auto 30px;">
            Thank you for your reservation! We've received your booking and 
            can't wait to serve you. You'll receive a confirmation email shortly.
        </p>
        <div>
            <a href="{% url 'home' %}" class="btn" style="background:#ffbe33; color:#fff; padding:12px 30px; margin:5px; border-radius:5px; text-decoration:none;">
                🏠 Back to Home
            </a>
            <a href="{% url 'menu' %}" class="btn" style="background:#333; color:#fff; padding:12px 30px; margin:5px; border-radius:5px; text-decoration:none;">
                🍕 View Menu
            </a>
        </div>
    </div>
</section>
{% endblock %}
```

---

### 👑 Step 11 — Set Up the Admin Panel

In `restaurant/admin.py`:

```python
from django.contrib import admin
from .models import Category, MenuItem, Booking, ContactMessage


@admin.register(Category)
class CategoryAdmin(admin.ModelAdmin):
    list_display = ['name', 'icon']


@admin.register(MenuItem)
class MenuItemAdmin(admin.ModelAdmin):
    list_display = ['name', 'category', 'price', 'is_special', 'is_available']
    list_filter = ['category', 'is_special', 'is_available']
    list_editable = ['price', 'is_special', 'is_available']
    search_fields = ['name', 'description']


@admin.register(Booking)
class BookingAdmin(admin.ModelAdmin):
    list_display = ['name', 'email', 'phone', 'date', 'time', 'party_size', 'created_at']
    list_filter = ['date', 'time', 'party_size']
    search_fields = ['name', 'email', 'phone']
    date_hierarchy = 'created_at'
    ordering = ['-created_at']


@admin.register(ContactMessage)
class ContactMessageAdmin(admin.ModelAdmin):
    list_display = ['name', 'email', 'subject', 'sent_at', 'is_read']
    list_filter = ['is_read']
    list_editable = ['is_read']
    search_fields = ['name', 'email', 'subject']
```

---

### 🚀 Step 12 — Run Migrations & Create Superuser

```bash
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

### 📊 Step 13 — Add Sample Data via Django Shell

```bash
python manage.py shell
```

```python
from restaurant.models import Category, MenuItem

burgers = Category.objects.create(name="Burgers", icon="🍔")
pizza = Category.objects.create(name="Pizza", icon="🍕")
drinks = Category.objects.create(name="Drinks", icon="🥤")
desserts = Category.objects.create(name="Desserts", icon="🍰")

MenuItem.objects.create(
    category=burgers,
    name="Classic Beef Burger",
    description="Juicy beef patty with lettuce, tomato, cheese and our secret sauce",
    price=12.99,
    is_special=True,
    is_available=True
)

MenuItem.objects.create(
    category=pizza,
    name="Margherita Pizza",
    description="Classic tomato sauce with fresh mozzarella and basil leaves",
    price=14.99,
    is_special=True,
    is_available=True
)

MenuItem.objects.create(
    category=drinks,
    name="Fresh Lemonade",
    description="Freshly squeezed lemons with mint and ice",
    price=3.99,
    is_special=False,
    is_available=True
)

MenuItem.objects.create(
    category=desserts,
    name="Chocolate Lava Cake",
    description="Warm chocolate cake with a molten center, served with vanilla ice cream",
    price=6.99,
    is_special=True,
    is_available=True
)

print(f"Created {MenuItem.objects.count()} menu items!")
```

---

### 🎊 Final Project Structure

```
restaurant_project/
│
├── manage.py
├── db.sqlite3
│
├── restaurant_project/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── restaurant/
│   ├── models.py         ← Database models
│   ├── views.py          ← Business logic
│   ├── forms.py          ← Form classes
│   ├── urls.py           ← URL patterns
│   ├── admin.py          ← Admin configuration
│   │
│   ├── templates/
│   │   └── restaurant/
│   │       ├── base.html
│   │       ├── home.html
│   │       ├── menu.html
│   │       ├── booking.html
│   │       ├── booking_success.html
│   │       └── contact.html
│   │
│   └── static/
│       └── restaurant/
│           ├── css/
│           ├── js/
│           └── images/
│
└── media/
    └── menu/             ← Uploaded food images
```

---

## 🌍 Chapter 19: Deploying Your Website to the Internet

### Option 1 — Railway (Easiest, Free Tier)

```bash
pip install gunicorn whitenoise
pip freeze > requirements.txt
```

Create `Procfile` (no extension):
```
web: gunicorn restaurant_project.wsgi
```

Update `settings.py`:

```python
import os
from pathlib import Path

DEBUG = os.environ.get('DEBUG', 'False') == 'True'

ALLOWED_HOSTS = ['*']

MIDDLEWARE = [
    'django.middleware.security.SecurityMiddleware',
    'whitenoise.middleware.WhiteNoiseMiddleware',  # Add this second
    ...
]

STATICFILES_STORAGE = 'whitenoise.storage.CompressedManifestStaticFilesStorage'

SECRET_KEY = os.environ.get('SECRET_KEY', 'your-dev-secret-key')
```

Push to GitHub and deploy on **https://railway.app** — it's free and takes 5 minutes!

### Option 2 — PythonAnywhere (Free Forever)

1. Sign up at **https://www.pythonanywhere.com/**
2. Upload your code
3. Set up a Web App pointing to your Django project
4. Done! Free `.pythonanywhere.com` domain

---

## 🚀 Chapter 20: What's Next? Your Learning Path

### 🗺️ The Full Developer Roadmap

```
📍 YOU ARE HERE — Django Basics
         ↓
🎯 Django REST Framework (Build APIs)
         ↓
⚛️  React + Django (Full-Stack)
         ↓
🐳 Docker + PostgreSQL (Professional Setup)
         ↓
☁️  AWS / GCP / Azure (Cloud Deployment)
         ↓
🤖 Django + AI/ML Integration
         ↓
🏆 Senior Full-Stack Developer
```

### 📚 Continue Learning

| Resource | Link | Cost |
|----------|------|------|
| Official Django Docs | https://docs.djangoproject.com | Free |
| Django for Beginners (Book) | https://djangoforbeginners.com | Paid |
| Python Official Docs | https://docs.python.org/3/ | Free |
| Real Python | https://realpython.com | Free/Paid |
| Django REST Framework | https://www.django-rest-framework.org | Free |

### 🔧 Technologies to Learn Next

```python
next_skills = {
    "Database": ["PostgreSQL", "MySQL", "Redis"],
    "Frontend": ["React", "Vue.js", "HTMX"],
    "DevOps": ["Docker", "CI/CD", "GitHub Actions"],
    "API": ["REST", "GraphQL", "WebSockets"],
    "Testing": ["pytest", "unittest", "Selenium"],
    "Security": ["OWASP", "SSL/TLS", "OAuth2"]
}

for category, skills in next_skills.items():
    print(f"\n{category}:")
    for skill in skills:
        print(f"  ✅ {skill}")
```

---

## 🤝 Contributing

Want to make this course better? Contributions are welcome!

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/add-chapter`
3. Commit your changes: `git commit -m 'Add new chapter on Django REST'`
4. Push to the branch: `git push origin feature/add-chapter`
5. Open a Pull Request

---

## 📜 License

This project is licensed under the **MIT License** — feel free to use it, share it, and build upon it. See `LICENSE` for details.

---

## ⭐ Star This Repo

If this course helped you, please give it a ⭐ star! It helps other beginners find it and keeps me motivated to add more content.

---

<div align="center">

**Made with ❤️ for beginners everywhere**

*"Every expert was once a beginner. Every pro was once an amateur."*

[![Python](https://img.shields.io/badge/Python-3.12+-blue?style=for-the-badge&logo=python)](https://python.org)
[![Django](https://img.shields.io/badge/Django-5.0+-green?style=for-the-badge&logo=django)](https://djangoproject.com)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge)](CONTRIBUTING.md)

</div>
