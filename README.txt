   
  		   Django Polling System

	      Name: Zakir Hussain (IS-5433)


--------------------------------------------------
PROJECT FEATURES

1. View available poll questions
   The homepage displays all questions stored in the database.

2. View question details
   Users can click a question to see its choices.

3. Vote on a selected choice
   Submitted votes are saved in the database.

4. View poll results
   After voting, users are redirected to a results page showing total votes.

5. Use of templates and static files
   HTML templates and a basic CSS file are used for the interface.

6. Implements Django's MVT (Model View Template) workflow.

7. Admin Dashboard
   The project includes Django’s built in admin panel where questions and choices can be added, edited, or deleted.
   Admin Login:
       Username: admin
       Password: 1234

--------------------------------------------------


TECHNOLOGIES USED

- Python 3
- Django Framework
- SQLite Database
- HTML and CSS (templates + static)  



--------------------------------------------------
HOW TO RUN THE PROJECT

1. Install Python 3 if not installed.

2. Install Django using:
   pip install django

3. Open the terminal and go to the project directory:
   cd "The sample application in Django - Zakir Hussain (IS-5433)"
   cd mysite

4. Start the development server:
   python manage.py runserver

   Note: If port 8000 is already in use, you can run the server on another port by specifying it in the command:
   python manage.py runserver PortNumber

5. Open the application in the browser at:
   http://127.0.0.1:8000/polls/

6. Access Admin Dashboard:
   http://127.0.0.1:8000/admin/




--------------------------------------------------
HOW TO RUN THE TESTS

go to the project directory (if not already there):
cd "The sample application in Django - Zakir Hussain (IS-5433)"
cd mysite

Run the tests:
To run the tests for the project, use the following command:
python manage.py test

This project is intended for educational purposes.