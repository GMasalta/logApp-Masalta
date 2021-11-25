# *__logApp__*

## __Description:pencil:__
___
This repository is for Practice Set 5-06. This user-friendly logApp repository will help you with data insertion. it will automatically links data once you registered your information like your fullname and address.

The "guestbook-list.php" displays the list of persons or users based on the registration. This project has been designed for logging in. User simply enter their Firstname, Lastname and address in the registration page in the appropriate fields. Then, Admin will see the list of names registered as well as the moment they registered after registration.

## __Visuals:sunglasses:__
___
<img src="https://github.com/GMasalta/logApp-Masalta/blob/main/registration.gif?raw=true"  alt="alt text">

~/Geraline Masalta/logApp-Masalta

## __Setting Up PHPmyAdmin :exclamation:__
___
* I am using 
[freesqldatabase](https://www.freesqldatabase.com/) to host my database online.
* Setting up the database:
    1. Log in and create a database. Then click the "Follow this link for phpMyAdmin"
    2. Creating two tables:
       * PERSON(pid, lastname, firstname, address, logdt
       * USERACCOUNT(uid, username, password)
    3. I add atleast one row in USERACCOUNT table so that I can test the Log In page.
* Then set up the database connection, Open the file config.php in the project, and define the value set for DB_HOST, DB_USER, DB_PASS, DB_NAME according to the Database details in [freesqldatabase](https://www.freesqldatabase.com/) account. Something like this:


>define('DB_HOST', 'sql6.freesqldatabase.com');

>define('DB_USER', 'sql6447240');

>define('DB_PASS', 'EaHclNXz2B');

>define('DB_NAME', 'sql6447240');

## __A Word From the Author :bust_in_silhouette:__
___
*<p><img src="https://github.com/GMasalta/logApp-Masalta/blob/main/Gline.jpg?raw=true" width="200" height="200" alt="alt text"  ><h1>Masalta, Geraline T.</h1></p>*

*"Sometimes to solve just a small problem, it takes a lot of brainstorming and can take hours or even months to solve a problem. However, the important thing is that the Programmer must enjoy their Programming Journey."*