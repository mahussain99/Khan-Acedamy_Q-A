                                                                            ### Khan-Acedamy_Q&A###

What are your favorite books? You can make a database table to store them in! In this first step, create a table to store your list of books. It should have columns for id, name, and rating.

STEP 1: Create Table Books ( id INTEGER PRIMARY KEY,  name TEXT,  rating INTEGER);

STEP 2: INSERT INTO Books Values ( 1, “ Harry Potter”, 5);
	INSERT INTO Books Values ( 2, “ Death Penelty”, 4);
	INSERT INTO Books Values ( 3, “Harry Potter2”, 4);
	INSERT INTO Books Values ( 4, “Polits Corrupted”, 5);
	INSERT INTO Books Values ( 5, “Non-Fictions”, 4);

SQl-Commend 
SELECT*
From Books;

Select them all
This database contains an incomplete list of box office hits and their release year. In this challenge, you're going to get the results back out of the database in different ways! In this first step, just select all the movies.

Step1:CREATE TABLE movies (id INTEGER PRIMARY KEY, name TEXT, release_year INTEGER);
INSERT INTO movies VALUES (1, "Avatar", 2009);
INSERT INTO movies VALUES (2, "Titanic", 1997);
INSERT INTO movies VALUES (3, "Star Wars: Episode IV - A New Hope", 1977);
INSERT INTO movies VALUES (4, "Shrek 2", 2004);
INSERT INTO movies VALUES (5, "The Lion King", 1994);
INSERT INTO movies VALUES (6, "Disney's Up", 2009);
 
In this first step, just select all the movies.
Select *
From Movies;


Select *
From Movies
Where release_year > 2000
Order by release_year ASC;


Here's a table containing a TODO list with the number of minutes it will take to complete each item. Insert another item to your todo list with the estimated minutes it will take.

Step1: CREATE TABLE todo_list (id INTEGER PRIMARY KEY, item TEXT, minutes INTEGER);
INSERT INTO todo_list VALUES (1, "Wash the dishes", 15);
INSERT INTO todo_list VALUES (2, "vacuuming", 20);
INSERT INTO todo_list VALUES (3, "Learn some stuff on KA", 30);
INSERT INTO TODO_LIST Values (4, "Learn how to do the math", 45);

Step 2: Select the SUM of minutes it will take to do all of the items on your TODO list. You should only have one SELECT statement.

Select sum(Minutes)
From todo_List
