# php-mysql
Week 4 and 5 PHP Tasks
TASK:

With the provided code skeleton inside the userAuthMySQL folder, your task is to do the following

Open your PHPMyAdmin and create a database called zuriphp.
create a database called zuriphp.
Create a table called Students with the following columns
id
full_names
country
email,
gender
password.
                   3. Import the SQL file called users.sql to have some initial users in your database for testing.

                2. config.php setup your database credentials by specifying your server name(host), username(user), password and database name(db) 

 

INSIDE userauth.php update the following functions

registerUser()  this function should take the full names, email, password, and country and store the data in a database table called Students. If it was successfully stored, the users should receive the message (“User Successfully registered”)
loginUser(). This file is meant to handle user login from the login form, the user inputs email and password from the form, you should check if the email and password provided match that which is in the database table, and if they match, create a session and put the username inside and redirect the user to the dashboard if it does not match, redirect the user back to the login page
resetPassword() this Function is meant to update the user password, the data is received from resetpassword.html, it takes in the email and the new password and searches the database, if there is a match for the email, it should update the password field with the new data from the form, else, it should print out “User does not exist”
logout.php this file is meant to destroy the user's existing session and redirect to the login page 
delete account(): this function deletes the user with the given id from the button on the front-end (the button name is ‘id’ you can access it within the post array when the button is pressed
NB: getUsers function has been implemented, check it out and get tips
