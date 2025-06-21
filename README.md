
# 📝 Flask Todo App (Dockerized)

This is a simple **Flask-based Todo web application** that uses **Flask-SQLAlchemy** and **SQLite** for data storage.  
It has been containerized using **Docker** to simplify setup and deployment.

---

## 🛠 Features

- ✅ Add and delete tasks
- ✅ Uses SQLite database with SQLAlchemy ORM
- ✅ Clean UI with [Semantic UI](https://semantic-ui.com/)
- ✅ Dockerized for easy local setup

---

## 🚀 Quick Start (Using Docker)

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Rahi88/Todo-App.git
cd Todo-App
````

### 2️⃣ Build the Docker Image

```bash
docker build -t flask-todo .
```

### 3️⃣ Run the App

```bash
docker run -p 5000:5000 flask-todo
```

### 4️⃣ Open in Browser

Visit: [http://localhost:5000](http://localhost:5000)

---

## 💡 Run Without Docker

You can also run this app manually:

### 1️⃣ Setup Virtual Environment (Windows)

```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
```

### 2️⃣ Start Flask App

```bash
python app.py
```

---

## 🔧 Technologies Used

* Python 3.9
* Flask
* Flask-SQLAlchemy
* SQLite
* Semantic UI
* Docker

```

Let me know if you’d like a version tailored for GitHub with badges, images, or contribution guidelines.
```
