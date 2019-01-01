## Django Web Development

install python 3.x

PowerShell : Set-ExecutionPolicy Unrestircted

python -V

pip -V

pip freeze - shows what is install on our system

create virtual environment into specific folder

    mkdir code
    ls
    pip install virtualenv
    virtualenv .
    ls
    ./Scripts/activate
    deactivate
    ./Scripts/activate
    pip freeze
    pip install django 
    pip install django==2.0.4
    mkdir djangoproject
    cd djangoproject
    ls
    django-admin.py startproject mysite

navigate to the project folder


create a migration

push the migration

    python manage.py migrate
    python manage.py startapp mypages
