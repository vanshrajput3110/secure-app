# 🔐 Secure Web Application

A simple but secure web application built using **Flask** that implements core security features like:
- User registration and login
- Password hashing
- Authentication & authorization
- Session management
- Protection against SQL injection (via SQLAlchemy ORM)

---

## 🚀 Features

- ✅ User registration and login system  
- ✅ Passwords hashed using bcrypt  
- ✅ SQLite database integration  
- ✅ Session-based login tracking  
- ✅ Access control for protected routes (dashboard)  
- ✅ Secure coding practices  

---

## 🧰 Technologies Used

- Python (Flask)  
- Flask-Bcrypt  
- Flask-SQLAlchemy  
- HTML (Jinja Templates)  
- SQLite  

---

## 📁 Project Structure

Secure_Web_Application/
├── app.py
├── templates/
│ ├── index.html
│ ├── login.html
│ ├── register.html
│ └── dashboard.html


---

## ⚙️ Setup Instructions

### 1. Install Dependencies
```bash
pip install flask flask-bcrypt flask-sqlalchemy
python app.py
Open in Browser
Visit: http://127.0.0.1:5000
🛡️ Security Highlights
🔒 Passwords hashed using bcrypt, not stored in plain text

🔒 SQL injection prevented via SQLAlchemy ORM

🔒 Protected routes via login decorators

🔒 Session tokens for authentication

Vansh Rajput
📧 vanshrajput5732@gmail.com
🔗 LinkedIn  🔗 https://www.linkedin.com/in/vansh-rajput-260457315/

