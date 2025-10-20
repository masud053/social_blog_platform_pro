# Social Blog Platform Pro (Django + React + JWT)

A full-stack social blogging platform featuring JWT authentication, personalized feeds, image uploads, and RESTful APIs.

## Features
- User authentication (JWT)
- CRUD for posts, comments, and likes
- Profile system with avatar & bio
- Follow/unfollow functionality
- Personalized feed & pagination
- Notifications for likes/comments/follows
- Optional AWS S3 cloud storage
- Docker + CI/CD ready

## Tech Stack
- Backend: Django REST Framework, JWT
- Frontend: React, Axios
- Database: SQLite / PostgreSQL
- Deployment: Docker, Render, Railway

## Setup (Local)
```bash
git clone https://github.com/masud053/social_blog_platform_pro.git
cd social-blog-platform-pro/backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Frontend:
```bash
cd ../frontend
npm install
npm start
```

## Docker Setup
```bash
docker-compose up --build
```

## Testing
```bash
pytest
```
