# Flask CRUD Template

![Preview](preview.png)

A simple and lightweight template for building CRUD applications with Flask.

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-Framework-000000?style=for-the-badge&logo=flask&logoColor=white)
![Jinja](https://img.shields.io/badge/Jinja-Templates-B41717?style=for-the-badge&logo=jinja&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-ORM-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-Database-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

## ✨ Features

- CRUD with Flask
- SQLite database
- Flask SQLAlchemy integration
- Bootstrap 5 UI
- Jinja templates
- Easy to customize for your own projects

## 🚀 Getting Started

### 1. Create a virtual environment

```bash
python3 -m venv venv
```

### 2. Activate the virtual environment

**Linux/macOS**

```bash
source venv/bin/activate
```

**Windows**

```powershell
.\venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure the application

Edit `app.py`:

- Set your own `app.secret_key`
- Replace the example model with your own
- Rename routes and variables as needed
- Customize the UI using Bootstrap 5
- Before deploying, change:

```python
debug=True
```

to

```python
debug=False
```

### 5. Run the application

```bash
python3 app.py
```

## 📄 License

This project is licensed under the **MIT License**.