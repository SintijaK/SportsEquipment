Sports_Equipment contains the project
SQL Database files contain the database created on SQL server management studio (emailed from Anton)
i put instructions for database table in xampp folder


for myphpadmin the username is sportsadmin, pass: adminpwd 
Steps:
*before make sure you copy the xampp files since they contain the database
*if you cant access myphpadmin you might have to enable it by running xampp-control.exe and start up Apache and Mysql
*create the sportsadmin user and give it privileges 
*check if user has all privileges to the database
*database connection can also be tested by migrate (check laravel practical 2)

if migrate does not work try using
composer dump-autoload

or

drop the table that error is referring to and re run migrate command
