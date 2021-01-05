# movie_ticket
Online Movie ticket booking system php project
Steps to execute the program
1. Install Xampp Stack
2. clone the Application from the Master Branch
3. Place the Application inside Following Folder Structure 
	c:/xampp/htdocs/<project_here>
	
Start the Xampp Server 
and Make a Request to Following Url: Using Any Browser like Google Chrome
localhost:80/phpmyadmin
Create a Database with db_movie 
and Goto Import Option and Import db_movie.sql file place inside project/database/ folder in the cloned 
project
Goto the Config.php File 
set up the Credentials 
with 
$host="localhost" or 127.0.0.1
$username = "root"
$password = ""
$dbname = "db_movies"

Make a Request to Url:
localhost:80/localhost/movie_application

SignUp as User and You can Enjoy All the Application
You can Also Login as Admin 
And Theatre Admin in Following Url

Admin : localhost:80/localhost/movie_application/admin
Theatre : Admin : localhost:80/localhost/movie_application/theatre :

In Order to Create Your Own Admin
goto PHPMYADMIN and goto db_movie database search table tbl_login
for Admin Make a Entry
set username and Password with user_type = 0
for Theatre Admin Make a Entry
set username and Password with user_type = 2


Following Are the Assumption Taken To build the Application
Application is Robust to Multi Screen System
Application is Can be Accessed through Web Online Mode 
UI has been kept simple as it is.

