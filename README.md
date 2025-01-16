First we have to install some packages for running the backend
   pip install django channels
   python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows

django-admin startproject djangochat
cd djangochat
python manage.py runserver  # This will run our server and we can see our app

I have created an django chat app where user can chat. There is an admin panel which can make chat groups can see user,group on the app.
Only admin can go to admin panel by /admin its username:admin password:1 setted by me.There is also user sign in,sign up functionality present where new user can sign up and login easily.

