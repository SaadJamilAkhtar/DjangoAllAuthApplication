# DJANGO ALLAUTH MODULE TEST APP
The App is buit for testing django-allauth module  
The app currently support signup using GOOGLE and FACEBOOK accounts  
[Here's a link](https://www.google.com) to AllAuth documentation  
Follow steps in documentation for AllAuth installation   

## How To Run App
1. Install all dependencies using "Run pip install -r requirements.tx"
2. create super user by running "python manage.py createsuperuser"
3. Add auth apps (Google auth and Facebook) by logging into /admin
4. run server using "python manage.py runserver"  
5. your site will be at "http://localhost:8000"

In case you want to run https on server:
1. Install all dependencies using "Run pip install -r requirements.tx"
2. create super user by running "python manage.py createsuperuser"
3. Add auth apps (Google auth and Facebook) by logging into /admin
4. run server using "python manage.py runserver_plus --cert cert"  
5. your site will be at "https://localhost:8000"


**Note :**  
For facebook you may need an HTTPS server.   
To enable HTTPS on your django test server follow steps:  
I) first install packages with:
1. pip install django-extensions
2. pip install Werkzeug
3. pip install pyOpenSSL

II) add 'django_extensions' in INSTALLED_APPS in settings.py

III) run command "python manage.py runserver_plus --cert cert"
 **Above steps are already done in the project and project has ability to use https server**

