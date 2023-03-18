# E-Diary_Management_System
E-Diary_Management_System is a Git repository that contains the source code for an electronic diary management system with login authentication system and database connectivity. The system allows users to create and manage notes, organize them by category, and track the time spent on each note.

#E-Diary Management System E-Diary Management System is an electronic diary management system that allows users to create and manage notes, organize them by category, and track the time spent on each note. The system also has login authentication and database connectivity features.

#Installation and Setup

1.Clone the repository to your local machine.
2.Create a virtual environment and activate it.
3.Run database migrations using python manage.py migrate.
4.Create a superuser account using python manage.py createsuperuser.

#Usage
1.Start the development server using python manage.py runserver.
2.Open a web browser and navigate to http://localhost:8000/.
3.Use the login form to log in to the system.
4.Once logged in, you can create and manage notes, organize them by category, and track the time spent on each note.
5.To modify or delete records, you must be logged in as a superuser.

#Creating a Superuser Account 
1.To create a superuser account, run the following command:

Code : python manage.py createsuperuser

>>>You will be prompted to enter a username, email address, and password. Once the account is created, you can use it to log in to the admin panel and make changes to the database.

#Modifying and Deleting Records

>>>To modify or delete records, you must be logged in as a superuser. Once logged in, navigate to the admin panel (http://localhost:8000/admin/) and use the provided interface to modify or delete records as needed.
