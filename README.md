# LMS Project - Django REST API - with React FrontEnd

# Django-React LMS

A full-stack Learning Management System (LMS) built using Django REST Framework for the backend and React.js (with Vite) for the frontend.


## Overview

This backend provides a comprehensive API for managing courses, students, instructors, and learning materials in an educational platform. It handles authentication, course management, content delivery, and user interactions.

## Project Structure

- **api/** - API endpoints and serializers
- **backend/** - Django project settings
- **core/** - Core application functionality
- **env/** - Environment configuration
- **media/** - User-uploaded files
- **static/** - Static assets
- **templates/email/** - Email templates
- **userauths/** - User authentication and authorization


## 🚀 Features

- User authentication (student/instructor, Admin)
- Course creation and enrollment
- Lessons and plugin architecture
- RESTful APIs with JWT support
- Modern React UI (Vite + Hooks + Context + JSX)
- Modular and scalable frontend and backend
- Course Management
- Content Management
- User Management
- Email Notifications
- File Upload/Download
- API Documentation

---

## 🔧 Tech Stack

### Backend
- Python
- Django
- Django REST Framework
- JWT Authentication
- SQLite (or plug in PostgreSQL/MySQL)


## Setup and Installation

### Prerequisites
- Python 3.8+
- pip
- virtualenv (recommended)
- Django 4.x
- Django REST Framework
- PostgreSQL/MySQL/SQLite (choose based on your needs)SQLite3 (Development)
- JWT Authentication
- Other libraries such as `django-cors-headers`, `django-environ`, etc.

### Installation

1. Clone the repository
```bash
git clone https://github.com/csenazmul/django-react-lms-project.git
cd django-react-lms/backend
```

## 📦 Running the Project

### 1. Backend (Django)
```bash
cd backend
python -m venv env
source env/bin/activate  # use `env\Scripts\activate` on Windows
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```


## Running the Application

- Run the development server using:
```bash
python manage.py runserver
```

You should now be able to access the API at http://127.0.0.1:8000/.

## API Endpoints

Here are some example endpoints:

    User Authentication: /api/v1/user/login/, /api/v1/user/register/
    Resource Operations: /api/v1/items/, /api/v1/items/<id>/
    Documentation: /api/docs/ (if Swagger or another docs tool is set up)

    Note: Review the API documentation (if applicable) for a complete list of endpoints and their usage.

## Testing

-To run the test suite:
```bash
python manage.py test
```
Ensure your tests pass before making any PRs or pushing changes.


### Frontend README.md

```markdown
# LMS Frontend - React Application

A modern, responsive Learning Management System frontend built with React.

## Overview

This frontend provides an intuitive interface for students and instructors to interact with the LMS platform. It features course browsing, enrollment, content consumption, and instructor tools.

## Project Structure

- **public/** - Static assets and HTML template
- **src/** - Source code
  - **assets/** - Images, icons, and other assets
  - **layouts/** - Page layout components
  - **store/** - Redux store configuration
  - **utils/** - Utility functions
  - **views/** - UI components organized by feature
    - **auth/** - Authentication views
    - **base/** - Common components
    - **instructor/** - Instructor dashboard and tools
    - **partials/** - Reusable UI components
    - **plugin/** - Third-party integrations
    - **student/** - Student dashboard and learning - - interface

## Setup and Installation

### Prerequisites
- Node.js 16+
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/django-react-lms.git
cd django-react-lms/frontend
```


### Usage

   - Access the Django admin interface at http://localhost:8000/admin.
   - The React frontend will be available at http://localhost:5173.




### License

MIT License
