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
* Investigated the login_time and success columns of the **log_in_attempts** table for failed **login attempts** made after business hours. ```success = 0``` indicates the login attempt was unsuccessful in this scenario.

![1.png](https://github.com/iduredia97/Filtering-with-AND-OR-and-NOT-Operators/blob/main/1%20(1).png)

* Investigated the **login_date** column of the **log_in_attempts** table for all log in attempts made on ```2022-05-08``` and ```2022-05-09```.

![2.1.png](https://github.com/iduredia97/Filtering-with-AND-OR-and-NOT-Operators/blob/main/2.1.png)

![2.2.png](https://github.com/iduredia97/Filtering-with-AND-OR-and-NOT-Operators/blob/main/2.2.png)

* Investigated the **country** column of the **log_in_attempts** table for all log in attempts outside of ```MEXICO```.

![3.1.png](https://github.com/iduredia97/Filtering-with-AND-OR-and-NOT-Operators/blob/main/3.1.png)

![3.2.png](https://github.com/iduredia97/Filtering-with-AND-OR-and-NOT-Operators/blob/main/3.2.png)

![3.3.png](https://github.com/iduredia97/Filtering-with-AND-OR-and-NOT-Operators/blob/main/3.3.png)

![3.4.png](https://github.com/iduredia97/Filtering-with-AND-OR-and-NOT-Operators/blob/main/3.4.png)

* Investigated the **department** and **office** columns of the **employees** table for all employees in the ```Marketing``` department inside of the ```East``` offices.

![4.png](https://github.com/iduredia97/Filtering-with-AND-OR-and-NOT-Operators/blob/main/4%20(1).png)

* Investigated the **department** column of the **employees** table for all employees within the ```Sales``` and ```Finance``` departments.

![5.1.png](https://github.com/iduredia97/Filtering-with-AND-OR-and-NOT-Operators/blob/main/5.1.png)

![5.2.png](https://github.com/iduredia97/Filtering-with-AND-OR-and-NOT-Operators/blob/main/5.2.png)

* Investigated the **department** column of the **employees** tables for all employees not within the ```Information Technology``` department.

![6.1.png](https://github.com/iduredia97/Filtering-with-AND-OR-and-NOT-Operators/blob/main/6.1.png)

![6.2.png](https://github.com/iduredia97/Filtering-with-AND-OR-and-NOT-Operators/blob/main/6.2.png)

![6.3.png](https://github.com/iduredia97/Filtering-with-AND-OR-and-NOT-Operators/blob/main/6.3.png)

![6.4.png](https://github.com/iduredia97/Filtering-with-AND-OR-and-NOT-Operators/blob/main/6.4.png)
