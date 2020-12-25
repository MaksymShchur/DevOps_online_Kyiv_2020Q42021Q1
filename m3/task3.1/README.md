# Results
I deployed the mysql database in a virtual machine, created tables in accordance with the selected subject area and performed some operations on it. These operations included various queries to the database, creating a new user and granting him privileges, as well as creating a backup and restoring the database using it. I also used services such as RDS and DynamoDB to host the database and some of its parts in the cloud.

## Part 1
### Description of the subject area
My subject area is a simple schedule for one day of university studies. It includes teachers, subjects (some teachers may teach several subjects), as well as groups of students and, of course, the schedule of their meetings:

![Sreenshot](/m3/task3.1/screenshots/Picture1.jpg)

### Created and filled tables in the database
![Sreenshot](/m3/task3.1/screenshots/Picture2.jpg)

![Sreenshot](/m3/task3.1/screenshots/Picture3.jpg)

![Sreenshot](/m3/task3.1/screenshots/Picture4.jpg)

![Sreenshot](/m3/task3.1/screenshots/Picture5.jpg)

![Sreenshot](/m3/task3.1/screenshots/Picture6.jpg)

### SELECT operator with WHERE,GROUP BY and ORDER BY
![Sreenshot](/m3/task3.1/screenshots/Picture7.jpg)

![Sreenshot](/m3/task3.1/screenshots/Picture8.jpg)

![Sreenshot](/m3/task3.1/screenshots/Picture9.jpg)

### New user with different privileges
![Sreenshot](/m3/task3.1/screenshots/Picture10.jpg)

![Sreenshot](/m3/task3.1/screenshots/Picture11.jpg)

![Sreenshot](/m3/task3.1/screenshots/Picture12.jpg)

## Part 2
### Make backup, delete the table and restore database
![Sreenshot](/m3/task3.1/screenshots/Picture13.jpg)

![Sreenshot](/m3/task3.1/screenshots/Picture14.jpg)

![Sreenshot](/m3/task3.1/screenshots/Picture15.jpg)

![Sreenshot](/m3/task3.1/screenshots/Picture16.jpg)

### Transfer your local database to RDS AWS
![Sreenshot](/m3/task3.1/screenshots/Picture17.jpg)

### Execute SELECT operator
![Sreenshot](/m3/task3.1/screenshots/Picture18.jpg)

![Sreenshot](/m3/task3.1/screenshots/Picture19.jpg)

![Sreenshot](/m3/task3.1/screenshots/Picture20.jpg)

![Sreenshot](/m3/task3.1/screenshots/Picture21.jpg)

### Create the dump of your database
We can make a dump from the Mysql Workbranch interface or by making a snapshot:

![Sreenshot](/m3/task3.1/screenshots/Picture22.jpg)

## Part 3
### Create and enter data into an Amazon DynamoDB table
![Sreenshot](/m3/task3.1/screenshots/Picture23.jpg)
