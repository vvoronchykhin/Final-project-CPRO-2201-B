# Final-project-CPRO-2201-B

STEP 1: Create Virtual Environment
Open Command Prompt or PowerShell in the PROJECT folder and run:

    python -m venv venv
    venv\Scripts\activate


STEP 2: Install Packages
    pip install -r requirements.txt


STEP 3: Setup Database
    cd netflix_project
    python manage.py makemigrations netflix_app
    python manage.py migrate
    python manage.py load_netflix_data

Wait 1-2 minutes for data to load.


STEP 4: Run Website
    python manage.py runserver

Open browser: http://127.0.0.1:8000/

Press CTRL+C to stop the server.
