CONSOLE COMMANDS 

    HOW TO SET UP DJANGO SERVER
        *Install python3*
        *Install pip*

    Use Python3 core package Venv to create virtual environment.
        python -m venv 'name virtual environment'

    Activate Virtual Environment.
        cd 'folder containing virtual environment name'
        source 'virtual environment name'/bin/activate
        
    Install DAWLAB_SITE Dependencies in virtual environment.
        pip install -r requirements/local.txt 
        OR
        pip install -r requirements/production.txt


    HOW TO RUN SERVER
        cd 'folder containing virtual environment name'
        source 'virtual environment name'/bin/activate
        cd 'folder containing DAWLAB_SITE manage.py'
        python manage.py runserver


HOW TO LOG IN TO HIDDEN ADMIN PAGE

url: 
    'http://127.0.0.1:8000'/admin ['localhost_url/admin']

admin credentials:
    username: brandon
    email: s@s.com
    password: brandonsersion


SECURITY WARNINGS

BEWARE admin credentials are public.
Change admin credentials before setting up production server.

BEWARE database key in settings.py is public.
Change database key before setting up production server.


