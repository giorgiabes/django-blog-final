# Django Blog

A simple and customizable blog built with Django.

## Installation

### **Linux/MacOS**

Follow these steps to set up and run the project on Ubuntu:

```
# Clone the repository
git clone https://github.com/giorgiabes/django-blog-final.git

# Navigate into the project directory
cd django-blog

# Create and activate a virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Apply database migrations
python manage.py migrate

# Create a superuser for admin access
python manage.py createsuperuser
```
### **Windows**
If you're using Windows, follow these steps:
```
# Clone the repository
git clone https://github.com/giorgiabes/django-blog-final.git

# Navigate into the project directory
cd django-blog

# Create and activate a virtual environment
python -m venv venv
venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Apply database migrations
python manage.py migrate

# Create a superuser for admin access
python manage.py createsuperuser
```

# **Add Simple Posts**

```
# Run server
python manage.py runserver
```
Go to the admin panel and create some posts: [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)

Then visit the blog homepage: [http://127.0.0.1:8000/](http://127.0.0.1:8000/)


# **Starter Project Pink**
[https://github.com/giorgiabes/django-blog](https://github.com/giorgiabes/django-blog)
