# Django Chat Application

A real-time Django chat application using WebSockets for instant messaging.

## Features:
- User authentication (sign-up & log-in)
- List of all registered users in a collapsible menu
- Real-time chat using WebSockets
- Persistent chat history stored in the database
- User-friendly chat interface

## Installation Guide

```bash


1. Clone the repository

git clone https://github.com/YOUR_USERNAME/django-chat-app.git
cd django-chat-app

2. Create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate     # On Windows

3. Install dependencies
pip install -r requirements.txt

4. Run database migrations
python manage.py makemigrations
python manage.py migrate

5. Create a superuser
python manage.py createsuperuser
user - admin
password - admin

6. Run the development server
python manage.py runserver
Visit http://127.0.0.1:8000/ in your browser.
