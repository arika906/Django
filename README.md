Django Rest Api

```diff

### Environment setup

- text in red
+ text in green
! text in orange
# text in gray

! Download Anaconda for Python 3.7
! Download Git Bash for using the git command on windows
! Download Sublime Text for coding
! Download postman for data entry

# install anaconda and create a new environment. Open python terminal from the environment.

## download django framework and rest-api by using these command

+   python -m pip install Django
+   pip install djangorestframework
+   pip install markdown
+   pip install django-filter

Now you can start your work with django :)

### source activate virtualenvironment

+ mkdir projectFolderName && cd projectFolderName
+ django-admin startproject projectName
+ python manage.py startapp appName

### after model setup then migration this model

+ python manage.py makemigrations
+ python manage.py migrate

### want a superuser for this project and app like (admin)

- python manage.py createsuperuser

#### For running the server

+ python manage.py runserver

I'm Done :)
