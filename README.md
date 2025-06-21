# 📝 Flask Todo App (Dockerized)

This is a simple **Flask-based Todo web application** that uses **Flask-SQLAlchemy** and **SQLite** for data storage.  
It has been containerized using **Docker** to simplify setup and deployment.

### 🛠 Features

- Add and delete tasks
- Uses SQLite database with SQLAlchemy ORM
- Clean UI with [Semantic UI](https://semantic-ui.com/)
- Dockerized for easy local setup

---

## 🚀 Quick Start (Using Docker)

### 1️⃣ Clone this repository
```bash
git clone https://github.com/Rahi88/Todo-App.git
cd Todo-App
### 2️⃣ Build the Docker image
docker build -t flask-todo .
###3️⃣ Run the app
docker run -p 5000:5000 flask-todo
###4️⃣ Open in Browser
Visit: http://localhost:5000

Technologies Used
 --Python 3.9
 --Flask
 --Flask-SQLAlchemy
 --SQLite
 --Semantic UI
 --Docker
#💡 To Run Without Docker 

You can also run this app manually:
Setup virtual environment (Windows)

--python -m venv venv
--venv\Scripts\activate
--pip install -r requirements.txt

#Start Flask app
--python app.py


