# python security camera

UNDER CONSTRUCTION. Still working on code.

Only the basics work right now.

`$ pipenv install django==2.1.5 pillow==5.4.1`

Create a new administrator login with `$ python manage.py createsuperuser`. 

`$ python manage.py runserver 0.0.0.0:8000` in the security_camera directory to start. The URL is the local IP address of the device (e.g. 192.128.X.X:8000).

Go to /admin for admin stuff and /home for the live cameras. Each smartphone can go to /post. From there, nothing else needs to be done other than set them to always be awake.
