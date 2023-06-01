Super Bowl Database
This repository contains a SQL database for Super Bowl records. It includes information about the Super Bowl date, the participating teams, the winning and losing scores, the Most Valuable Player (MVP), and the stadium details.

Database Schema
The database has a single table called superbowls with the following columns:

Date: The date of the Super Bowl (primary key).
SB: The Super Bowl number.
Winner: The name of the winning team.
Winner_Pts: The number of points scored by the winning team.
Loser: The name of the losing team.
Loser_Pts: The number of points scored by the losing team.
MVP: The Most Valuable Player of the Super Bowl.
Stadium: The name of the stadium where the Super Bowl was played.
City: The city where the Super Bowl was held.
State: The state where the Super Bowl was held.
Usage
You have been provided with the SQL statements to create the superbowls table and insert data into it. The data includes Super Bowl records from past years.

To query the database using more advanced syntax, you can use SQL statements like SELECT, WHERE, ORDER BY, and more. You can retrieve specific information based on various criteria, such as filtering by the winning team, MVP, or stadium. Feel free to experiment with different queries to extract the desired information.

Examples
Here are a few examples of SQL queries you can run against the database:

Retrieve all Super Bowl records:

sql
Copy code
SELECT * FROM superbowls;
Get the Super Bowl records for a specific year:

sql
Copy code
SELECT * FROM superbowls WHERE Date = 'Feb 2 2020';
Find the Super Bowl(s) won by a specific team:

sql
Copy code
SELECT * FROM superbowls WHERE Winner = 'New England Patriots';
Get the Super Bowl(s) where a specific player was the MVP:

sql
Copy code
SELECT * FROM superbowls WHERE MVP = 'Tom Brady';


Acknowledgments
The Super Bowl data provided in this database is sourced from various reliable and publicly available resources.

Please note that this database is for educational and informational purposes only and does not contain real-time data.

Feel free to explore the data and modify the queries to suit your needs!