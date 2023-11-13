# networking-ecommerce
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
-> 
