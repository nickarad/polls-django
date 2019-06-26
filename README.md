## activate the virtual environment using source:

>$  source ./bin/activate

# The development server

## Let’s verify your Django project works. Change into the outer mysite directory, if you haven’t already, and run the following commands:

>$  python manage.py runserver

# Migrations

>$   python manage.py migrate

The migrate command looks at the INSTALLED_APPS setting and creates any necessary database tables according to the database settings in your mysite/settings.py file and the database migrations shipped with the app (we’ll cover those later). You’ll see a message for each migration it applies. If you’re interested, run the command-line client for your database and type \dt (PostgreSQL), SHOW TABLES; (MySQL), .schema (SQLite), or SELECT TABLE_NAME FROM USER_TABLES; (Oracle) to display the tables Django created.



