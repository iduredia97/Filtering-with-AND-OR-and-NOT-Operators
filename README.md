# Filtering-with-AND-OR-and-NOT-Operators
## Objective
Use ```AND```, ```OR```, and ```NOT``` operators to filter log in attempts in the Maria Database.
## Tasks
* Retrieve all failed login attempts after business hours.
* Retrieve all log in attempts that occurred on dates: ```2022-05-08``` and ```2022-05-09```.
* Retrieve logins that didn't originate in ```MEXICO```.
* Retrieve information about certain employees in the ```Marketing``` department.
* Retrieve information about employees in the ```Sales``` and ```Finance``` departments.
* Obtain information about employees who are not in the ```Information Technology``` department.
## Steps Taken
Investigated the login_time and success columns of the **log_in_attempts** table for failed **login attempts** made after business hours. ```success = 0``` indicates the login attempt was unsuccessful in this scenario.
