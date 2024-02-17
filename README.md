# Simple Notes Django App
A simple note-taking application written using Python's Django web framework.

## Features
- Shortcuts
- Organize notes into notebooks
- Export notes as PDF files
- Share your notes via a unique link
- Multiple themes
- Reminders
- Version Control

# Installation
Clone repo & create .env file from .env.example

```bash
git clone https://github.com/ashavijit/simple-notes-django-app
cd simple-notes-django-app
cp simple_notes/.env.example simple_notes/.env
```

Note: You may want to edit .env file to specify SECRET_KEY and some other information.

Install dependencies with Pipenv: `pipenv install` or with pip: `pip install -r requirements.txt`.

Run database migrations and the project itself:

```bash
./manage.py migrate
./manage.py runserver
# or
gunicorn --chdir simple_notes simple_notes.wsgi --preload
```

## Developer Details
- **Name**: Avijit Sen
- **Username**: ashavijit
- **Prior Experience**: 5+ internships
- **Email**: avijitsen.me@gmail.com

---

## Technologies Used
- Django: Django is a high-level Python web framework that encourages rapid development and clean, pragmatic design. It's great for building web applications quickly and efficiently, with built-in security features, a powerful ORM, and a vibrant community.
- HTML: HTML (Hypertext Markup Language) is the standard markup language for creating web pages and web applications.
- CSS: CSS (Cascading Style Sheets) is a style sheet language used for describing the presentation of a document written in HTML.
- JavaScript: JavaScript is a programming language that enables you to create interactive effects within web browsers.
- SVG Icons: SVG (Scalable Vector Graphics) is an XML-based vector image format for two-dimensional graphics with support for interactivity and animation.

## Why Django?
Django was chosen for this project due to its robustness, scalability, and the rapid development it offers. Here are some reasons why Django is a great choice for building web applications:
- **Batteries-included**: Django comes with a wide range of built-in features, including an ORM, authentication, URL routing, template engine, and more, which accelerates development and reduces the need for third-party libraries.
- **Security**: Django provides built-in protection against common security threats such as SQL injection, cross-site scripting (XSS), cross-site request forgery (CSRF), and clickjacking.
- **Community and Documentation**: Django has a large and active community of developers who contribute plugins, tutorials, and support. The extensive documentation makes it easy for developers to learn and troubleshoot.
- **Scalability**: Django is highly scalable and can handle high traffic loads with ease. Its architecture allows for the efficient deployment of applications on various hosting platforms.
- **ORM**: Django's Object-Relational Mapping (ORM) simplifies database operations by abstracting the underlying database structure, allowing developers to work with database models using Python objects.

