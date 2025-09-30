# Online Coffee Shop on Flask ☕

[![Python 3.9+](https://img.shields.io/badge/Python-3.9+-blue?logo=python)](https://python.org)
[![Flask](https://img.shields.io/badge/Flask-2.3+-orange?logo=flask)](https://flask.palletsprojects.com/)
[![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-2.0+-yellow?logo=sqlalchemy)](https://www.sqlalchemy.org/)
[![python-dotenv](https://img.shields.io/badge/python--dotenv-0.21+-green?logo=python)](https://pypi.org/project/python-dotenv/)
[![Flask-Login](https://img.shields.io/badge/Flask--Login-0.6+-blue?logo=flask)](https://flask-login.readthedocs.io/)
[![Flask-WTF](https://img.shields.io/badge/Flask--WTF-1.1+-red?logo=python)](https://flask-wtf.readthedocs.io/)
[![Flask-Caching](https://img.shields.io/badge/Flask--Caching-2.0+-purple?logo=python)](https://flask-caching.readthedocs.io/)

This web application simulates an online coffee shop where users can browse the menu, add items to the cart, and place orders.

The application is built using Flask and popular Python libraries.

## 📌 Features

- Browse the menu with different categories of drinks and desserts.

- Add items to the cart and update quantities.

- Place orders with customer information.

Admin panel for managing menu items and orders.

Responsive design for mobile-friendly use.

## 🛠 Technologies

Backend: Python, Flask

Database: PostgreSQL

Frontend: HTML, CSS, Jinja2 (Flask templates)

Extras: Flask-Login, Flask-WTF

⚡ Installation & Setup

Clone the repository:

```git clone https://github.com/yourusername/online-coffee-shop.git```

```cd online-coffee-shop```



Create and activate a virtual environment:

```python -m venv venv```
# Windows
```venv\Scripts\activate```
# Mac/Linux
```source venv/bin/activate```


Install dependencies:

pip install -r requirements.txt


Configure environment variables in a .env file:

```env
# Database configuration
DATABASE_NAME="your_database_name"
DB_USER="your_db_user"
DB_PASSWORD="your_db_password"

ROOT_DB_USER="your_root_user"
ROOT_DB_PASSWORD="your_root_password"

# Flask secret key
SECRET_KEY="your_secret_key"

Initialize the database:
```


Run the application:

flask run


Open your browser at http://127.0.0.1:5000


📝 Notes

Make sure to set a secure SECRET_KEY for production.

You can switch to PostgreSQL or MySQL by updating DATABASE_URL in .env.

Admin credentials can be configured directly in the database or through an admin registration route.
