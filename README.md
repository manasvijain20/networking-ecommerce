# Task 1: Manage.py 
-> Manage.py file manages how the project runs. 
-> At the top some models and libraries are imported for the project
-> Next we have some dictionaries which contain some sample data for the database
-> We have a function called 'FlaskGroup()' which is used to create commands for managing this application
-> We have functions recrate_db() and seeder() where the recreate_db() deletes and recreates the db and the seeder() function re-enters the sample data into the newly created database

# Task 2: __init__.py
-> init.py initialises the app folder so it can work as a python module
-> At first we are importing the following modules:
CORS: to allow cross origin requests in the application
SQLAlechmy: to simplify SQL code and to write and execute SQL queries in flask
Migrate: It is used to transfer data from an older databse to  the newly construted databse without losing any data
-> create_app() is used to create the flask application
-> the data is initialised with db.init_app() function
-> we are registering our blueprints with register_blueprint() function

# Task 3: views.py and api.py
-> The api and the views folder contain code for routes for APIs and Views

# Task 4: models
->The models folder contains python files for all the tables, that contains the column names and their types
through which the schema of each and every table in our database is defined.
.
