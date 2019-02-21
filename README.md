# Django-Authentication-using-django-crispy-forms
This is the simple project based on Django authentication. In this project the python build in library crispy-forms is used. in this project bootstrap4 is used for basic template development. 
# For Database setup:
The postgresql database technique is used for this project.
<br/>
first of all you have to install postrgresql from following link: https://www.postgresql.org/download/windows/ 
<br/>
<h3>Command line in cmd as</h3>
	>>pip install psycopg2 <br/>
	>>pip install psycopg2-binary <br/>
	>>python manage.py migrate <br/><br/>
<h3>And in setting file you have to add database system as : </h3>
	DATABASES = { <br/>
    'default': { <br/>
        'ENGINE': 'django.db.backends.postgresql', <br/>
        'NAME': 'authen', <br/>
        'HOST': 'localhost', <br/>
        'PASSWORD': 'admin', <br/>
        'USER': 'postgres' <br/>
    } <br/>
} <br/>

# For adding django-crispy-forms:
>> pip install django-crispy-forms
<h3> In setting.py file</h3>
	CRISPY_TEMPLATE_PACK = 'bootstrap4'


<h6> <a href = 'https://www.techiediaries.com/django-authentication/'>Click here to visit the official training site</a>
