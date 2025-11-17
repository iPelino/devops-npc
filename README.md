# Django Blog Application

A full-featured blog application built with Django, featuring user authentication, post management, and a public-facing interface.

## 📋 Project Overview

This is a Django-based blog application that allows users to create, read, update, and delete blog posts. The application includes user authentication, an admin interface, and a clean, responsive design for visitors to browse content.

## ✨ Features

### Current Features
- Django project structure with `blog` app
- Basic project setup and configuration
- Virtual environment setup
- Dependency management

### Planned Features (See Issues)
- **Epic 1: Basic Project Setup & Core Functionality**
  - Data models for blog posts
  - Database migrations
  
- **Epic 2: Public-Facing Blog Interface**
  - Homepage with list of all blog posts
  - Individual post detail pages
  
- **Epic 3: User Authentication & Management**
  - Django admin interface for post management
  - User registration functionality
  - Login/logout functionality
  
- **Epic 4: Blog Post Management for Authenticated Users**
  - Create new blog posts
  - Edit existing posts (author only)
  - Delete posts (author only)

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- pip
- virtualenv (recommended)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/iPelino/devops-npc.git
   cd devops-npc
   ```

2. **Create and activate virtual environment**
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run migrations**
   ```bash
   python manage.py migrate
   ```

5. **Create a superuser (for admin access)**
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server**
   ```bash
   python manage.py runserver
   ```

7. **Access the application**
   - Main site: http://127.0.0.1:8000/
   - Admin panel: http://127.0.0.1:8000/admin/

## 📦 Dependencies

- Django 5.2.8
- asgiref 3.10.0
- sqlparse 0.5.3

See `requirements.txt` for the complete list.

## 🏗️ Project Structure

```
devops-npc/
├── blog/                 # Main blog application
│   ├── migrations/      # Database migrations
│   ├── admin.py        # Admin interface configuration
│   ├── apps.py         # App configuration
│   ├── models.py       # Data models
│   ├── tests.py        # Unit tests
│   └── views.py        # View functions
├── blogApp/             # Project configuration
│   ├── settings.py     # Project settings
│   ├── urls.py         # URL routing
│   ├── wsgi.py         # WSGI configuration
│   └── asgi.py         # ASGI configuration
├── manage.py           # Django management script
├── requirements.txt    # Python dependencies
└── README.md          # This file
```

## 🛠️ Development

### Running Tests
```bash
python manage.py test
```

### Code Quality
```bash
ruff check .
```

### Making Migrations
```bash
python manage.py makemigrations
python manage.py migrate
```

## 📝 Contributing

1. Check the [Issues](https://github.com/iPelino/devops-npc/issues) page for current user stories and tasks
2. Create a feature branch from `develop`
3. Make your changes
4. Submit a pull request

## 📄 License

This project is part of a learning exercise for DevOps and Django development.

## 🔗 Links

- [GitHub Repository](https://github.com/iPelino/devops-npc)
- [Issues & User Stories](https://github.com/iPelino/devops-npc/issues)

## 👥 Author

iPelino

---

*Built with Django 5.2.8*