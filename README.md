# DJANGO 3.0 by example

Django Project Part1
1. start with Django Project part 1
2. 'python -m django --version' output is No module named django
3. to install django type this into the terminal 'python -m pip install Django'
4. now that django is installed, from the terminal run 'django-admin startproject mysite'
5. cd into django3_by_example_env 'cd mysite'
6. run django 'python manage.py runserver'
7. we will create the polls app 'python manage.py startapp polls'
8. change directory into django3_by_example_env/mysite/polls 'cd polls'
9. create urls.py by entering 'touch urls.py'
10. go back a few folders and add this to django3_by_example_env/mysite/polls 'from django.contrib import admin
from django.urls import include, path

urlpatterns = [
    path('polls/', include('polls.urls')),
    path('admin/', admin.site.urls),
]'
11. from the terminal now run 'python manage.py migrate'
12. open the url listed and in the url browswer add '/polls' to the end of the url string hit enter
13. site should display text 'Hello, world. You're at the polls index.'

Django Project Part2
