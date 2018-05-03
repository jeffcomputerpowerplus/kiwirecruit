# The Kiwirecruit Django Web Application

INSTALLATION INSTRUCTIONS

1. Clone or download this repository to your computer, and then unzip the folder.

2. Open a command line and cd.. to the root directory of the app.

3. Create and run the migrations like this =>
   <br>python manage.py migrate
   <br>You should see messages starting:
   <br>Applying contenttypes.0001_initial... OK
   <br>Applying auth.0001_initial... OK (... etc.)

3. Load the app users and app data like this =>
   <br>python manage.py load_userprofile_data
   <br>You should see these messages:
   <br>Loading User data for the user profile...
   <br>Loading users...

4. Run the server =>
   <br>python manage.py runserver

5. Open a browser and go to http://127.0.0.1:8000/
   <br>You should see the home page of the kiwirecruit.

6. Use the login credentials below to explore the app!

USER LOGIN USERNAMES AND PASSWORDS
<br>regt	regt1234
<br>zach	zach1234
<br>austf	aust1234
<br>howiec	howi1234
<br>sandieg	sand1234
<br>philr	phil1234
<br>krysv	krys1234

ADMIN LOGIN FOR DJANGO (OPTIONAL!)

If you want access to the Django admin then you first need to create a superuser. Follow the instructions below:

1. Open a command line and cd.. to the root directory of the app.

2. Create a superuser like this =>
   <br>python manage.py createsuperuser

3. Follow the prompts to enter a new username and password.

4. To login to the django admin, open a browser and go to http://127.0.0.1:8000/admin/
