# nyc-guide

New York City Guide Website Pair-Programming Project
by Ramsy Anton (https://github.com/ramsy-anton) & Tyler Langsam (https://github.com/Tylerlangsam)


1. Create a virtual environment

At the root folder of the repository run:

python3 -m venv venv
Make sure to call your virtual environment "venv"

2. Run virtual environment

On Windows:

Windows Powershell users:

venv\Scripts\activate.bat

Bash users:

source venv/Scripts/activate

On Unix or MacOS:

source venv/bin/activate

3. Install Django

pip install django

4. Create requirements.txt file

pip freeze > requirements.txt

5. Run Django

python manage.py runserver
And go to http://localhost:8000