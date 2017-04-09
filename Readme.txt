Sports_Equipment contains the project
SQL Database files contain the database created on SQL server management studio (emailed from Anton)
i put instructions for database table in xampp folder


for myphpadmin the username is sportsadmin, pass: adminpwd (youll have to create it on myphpadmin and give it all privileges. might need to give privileges to the user in database itself)


if migrate does not work try using
composer dump-autoload

or

drop the table that error is referring to and re run migrate command
