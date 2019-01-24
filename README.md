blog_project

A basic Blog Application.

Installation

Clone or download the repository.

Create a new virtual environment for the project.

virtualenv venv

source venv/bin/activate

Install required python libraries giving in the requirements.txt file.

pip install -r requirements.txt

Run Django migrations.

python manage.py makemigrations

python manage.py migrate


Start the application.
python manage.py runserver
