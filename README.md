# 📝 Flask User Registration App (with SQLAlchemy)

A beginner-friendly Flask app for user registration and login (template), using a database (SQLite) for user info and secure password storage.

---

## ✨ Features

- User registration with username, email, and password
- Passwords are **securely hashed**
- Handles duplicate usernames/emails and incomplete forms
- Stores users in `users.db` using SQLAlchemy
- Simple SQLite database works “out of the box” with no extra setup

---

## 🚀 How to Run

1. **Install requirements:**
    ```
    pip install flask flask_sqlalchemy werkzeug
    ```
2. **Save your code as `app.py` and create `register.html` in a `templates` folder.**
3. **Start the server:**
    ```
    python app.py
    ```
4. In your browser, go to [http://localhost:5000/register](http://localhost:5000/register) to sign up.

---

## 🧑‍💻 Usage

- Fill out username, email, password — hit submit
- Get feedback for duplicate users or missing info
- (Login is a placeholder and can be extended)

---

## 🗂️ How It Works

- Python backend with Flask for routes and forms
- SQLAlchemy manages user database in `users.db`
- Feedback is given with Flask’s `flash` messages

---

## 📄 License

MIT License — free for learning, teaching, tinkering.

---

A clean Python starter for real web registration systems!
