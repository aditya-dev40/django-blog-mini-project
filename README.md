# Django Blog Mini Project

A Django-based mini blog application built as a learning project to understand core Django concepts such as authentication, models, forms, media handling, and template rendering.

---

## Features

- User registration, login, and logout using Django’s built-in authentication system
- Auth-protected post creation (only logged-in users can create posts)
- Blog posts with title, body, slug, author, date, and banner image
- Image upload support using Django media files
- Post listing and individual post detail pages
- Clean, readable URLs using slug-based routing
- Form validation using Django ModelForms
- Template inheritance for reusable layouts
- Custom styling using static CSS files

---

## Tech Stack

- **Backend:** Django
- **Frontend:** HTML, CSS (Django Templates)
- **Database:** SQLite
- **Authentication:** Django Auth System

---

## Concepts Practiced

- Django models, views, and URL routing
- User authentication and authorization (`login_required`)
- Django forms and ModelForms
- File uploads (MEDIA files)
- Template inheritance and context rendering
- CSRF protection
- Basic CRUD operations

---

## Notes

- Static and media files are served only in development (`DEBUG = True`)
- This project is intended for learning purposes and is not production-ready

---

## Future Improvements

- Auto-generate unique slugs from post titles
- Add edit and delete functionality for posts
- Improve UI and responsive design
- Deploy the application

---

