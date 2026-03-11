# ☕ Cafe Finder API & Web App (Flask + SQLAlchemy)

A simple **Cafe Finder Web Application and REST API** built using **Flask, SQLAlchemy, and SQLite**.
The application allows users to explore cafes with good coffee and WiFi, search by location, and add new cafes to the database.

This project is part of my **Python Backend Development learning journey**.

---

# 🚀 Features

* View a list of cafes on a webpage
* Add new cafes through a form
* Get a random cafe using an API
* View all cafes in JSON format
* Search cafes by location
* SQLite database integration
* Flask + SQLAlchemy ORM

---

# 🛠 Tech Stack

* Python
* Flask
* SQLAlchemy
* SQLite
* HTML
* Jinja Templates

---

# 📂 Project Structure

```
project-folder
│
├── main.py
├── cafes.db
│
├── templates
│   ├── index.html
│   └── add_cafe.html
│
└── README.md
```

---

# ▶️ How to Run the Project

### 1. Clone the repository

```
git clone https://github.com/yourusername/cafe-finder.git
```

### 2. Move into the project folder

```
cd cafe-finder
```

### 3. Install dependencies

```
pip install flask flask_sqlalchemy
```

### 4. Run the application

```
python main.py
```

The server will start at:

```
http://127.0.0.1:5000
```

---

# 🌐 Web Pages

### Home Page

Displays a list of cafes with information such as:

* Cafe name
* Location
* WiFi availability
* Seats
* Coffee price

### Add Cafe Page

Users can add a new cafe to the database.

```
http://127.0.0.1:5000/add
```

---

# 📡 API Endpoints

### Get Random Cafe

```
/random
```

Returns a random cafe in JSON format.

---

### Get All Cafes

```
/all
```

Returns all cafes in the database.

---

### Search Cafe by Location

```
/search?loc=Clerkenwell
```

Example:

```
http://127.0.0.1:5000/search?loc=Clerkenwell
```

---

# 🎯 Learning Outcomes

Through this project I learned:

* Building REST APIs with Flask
* Working with SQLite databases
* Using SQLAlchemy ORM
* Rendering data using Jinja templates
* Creating sim

