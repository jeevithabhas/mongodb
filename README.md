ZenClassProgramme MongoDB Project


This project contains MongoDB scripts for creating and managing a database for a Zen Class Programme. 


The database includes collections for users, topics, tasks, company drives, and more.


It also includes sample queries for retrieving data from the database.



Collections


The database includes the following collections:

1.users: Stores user information, including name, email, mentor information, attendance, and tasks submitted.


2.codekata: Tracks the number of problems solved by each user.


3.attendance: Records user attendance for each session.


4.topics: Lists topics taught in the program with their respective dates.



5.tasks: Stores tasks assigned to users, along with submission dates and statuses.


6.company_drives: Details company drives for placements, including dates and participating students.


7.mentors: Contains information about mentors and the number of mentees they supervise.



Queries Included

Here are some of the queries provided in queries.js:

1.Topics and Tasks in October: Retrieves all topics and tasks taught in October.


2.Company Drives: Finds company drives held between 15-Oct-2020 and 31-Oct-2020.


3.Students Appearing for Placement: Lists company drives along with students who appeared for placements.


4.Codekata Problems Solved: Counts the total problems solved by each user in Codekata.


5.Mentors with Many Mentees: Finds mentors with more than 15 mentees.


6.Absent Users and Incomplete Tasks: Retrieves users who were absent and did not submit tasks between 15-Oct-2020 and 31-Oct-2020.
