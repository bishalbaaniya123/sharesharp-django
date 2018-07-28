# facial-recognition-python-django
Face detection and facial recognition along with recognized persons information fetched from database.

General Languages and versions

    •	Python version: 2.7.14
    •	Django version: 1.11.9
    •	OpenCV version: 3.4.0
    •	Sklearn version: 0.19.1
    •	Mysql Database

Run -

    python manage.py runserver --nothreading --noreload

Demo Video
https://www.youtube.com/watch?v=p70srlZvyvQ&feature=youtu.be

Config steps:
1. Download and install mySQL server 5.5 (latest one will not work)
    imp: specify the port 8889
2. Then open MySQL 5.5 Command Line Client
    enter this command
    CREATE DATABASE django_project;
3. pip install matplotlib
4. pip install opencv-contrib-python
5. python manage.py makemigrations
   python manage.py migrate
6. python manage.py runserver