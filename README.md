# anakinskywalker
important stuff


The interviews are usually focused on practical questions including real life scenarios and what would you to in those cases

 

For example, suppose you are working in a multiserver running app that has 8 servers across the US and 1 of those servers has an error code 500, what would you to do to find out the location of that failed server? What would you do next? Also, what to do when you face a code 401, how to review logs, when to perform a health check in certain scenario and what to look for.

 

Given a basic structure of a relational databases, what querys would you write to get the required information, and such.

 

Unix

Questions about Permission and commands related to finding files, filtering files of logs and searching things into log files (grep, find)

-The different types of permission                 

-How to get the “owner permission” and write the command to do so

-How to kill a process

- Questions about “ls” command

 

Practical questions

-How to check a running log in the app

-How to get information of a current user

-How to delete files of the las X days in the system, and write the command to do so *

-How to find files older than X days and larger than X MBs, and write the command to do so *

-What is the directory permission mode 477, must be able to explain it using your own words

-Ask how one can get a word in a determinate line of code and replace it in another line

*Interviewer asked what conditionals would be necessary to meet those requirements

**There may be also questions about “Grep” command line to review logs and such

 

ITIL

-Questions about incident management (what´s and incident, when to report it)

 

Shell Scripting

What are and how are used the special variables “$!” and “$$”

Questions about logic, for example in an array how to find a 2nd non-repeated character

 

SQL

-Primary and Foreign Keys

-Aggregate functions

-Different types of joints

-Difference between Union vs Unionall

-Questions about group, count, max, join, set constraints to columns

-Questions about what commands would be used to work with constraints

-“Truncation” and “Truncate” command

-Practical exercises, the basic structure of a table will be shared and there will be questions about how to get certain results, for example (studentid, teacher, grades, subjects), and the ask max grade of an student in certain subject or such and the query to get such information

-There may also que questions about PL-SQL

 

General Recommendations:

 

Join with enabled audio and camera
Be prepared to share your screen while solving questions
Make sure you understand the question and what is expected in your answer before responding (you can request the interviewer to write down a specific concept or key word in the chat)
 

Programming

You must be able to read and fix simple defects using any object oriented programming language.

 

For Java, there have been questions regarding collections, the difference between a “linked list” and an “array list”, how “hashmap” works and such.

 

Esta guía no está basada en entrevistas pasadas, puede que los temas varíen según el estilo del entrevistador, pero espero esto te pueda servir!

 

Saludos!

 

 

Francisco Carvajal

TA Specialist | Talent acquisition

 

Capgemini México | Guadalajara

Tel.: (+52)3314885093

Linkedin: www.linkedin.com/in/francisco-carvajal-mora-1b496a183

www.capgemini.com


https://test.imocha.io/AuthenticateKey?id=a0d8157bd9

SQL Interview questions-

Q 1. Query is long running, what steps u will take?  
Q 2. What is a deadlock? How will you go about resolving deadlocks?
Q 3. What is Constraints and its types?
Q 4. Different between Primary Key and Unique Key?
Q 5. Difference between Delete, Truncate and Drop?
Q 6. Types of Statements in SQL?
Q 7. What is TCL and DCL?
Q 8. How many methods, we can use to insert the values in table?
Q 9. Query to insert the values is particular column?
Q 10. Query to create new table from existing table?
Q 11. Query to create new table from existing table without copying the data?
Q 12. Types of functions in SQL. (Particularly Single Row Function- Number, Character(substr & instr), Date Fun., Conversion Function, General Fun (NVL, NVL2))
Q 13.  Print the emp_name, Salary (with the commission) as Total_Income for all the employees. (If there is no commission only Salary Should print)
Q 14. What is Group functions in SQL?
Q 15. Difference between ‘Where’ and ‘Having Clause’ (in which condition, we use having clause).
Q 16. Query to fetch Ename, deptno, Max_Sal from each department from Employee table? 
Q 17. Query to fetch the number of employees, heired every year. ( Columns- ename, hiredate’)
Q 18. Some scenario-based questions from Joins like below. (mainly Equi join & Inner join)
Q 19. From the Employee and Department table, write a query to fetch the departments where number of employees is greater than 8?
Q 20. Types of joines with explanation? 
Q 21. What is Index in SQL and types? (with SYNTAX)
Q 22. Difference between Index Scan and  Full table Scan in SQL?
Q 23. What is view and its types?
Q 24. Query to find 7th highest salary?
Q 25. Query to find duplicate rows in table?
Q 26. Query to delete duplicate rows in table?
Q 27. Query to fetch last record from the table?
Q 28. Query to fetch even/odd rows from the table?
Q 29. Rank and Dense rank concepts?
Q 30. Special operators uses (%, _ with like)

UNIX Interview questions-

Q 1. How to delete empty lines in a file?
Q 2. How to print the hidden files? 
Q 3. How to display the files in a directory, size less than 4 MB?
Q 4. How to transfer files from one application Server to another server?
Q 5. How to connect to DB from Unix Server?
Q 6. What is the first line of the Script (shebang) and what it denotes/indicates?
Q 7. How to run a process in background and what is it’s advantage?
Q 8 . How you will find %memory & %CPU utilization? (TOP command and it’s output)
Q 9. How do you find the number of occurrences of the word in the file? (wc -w)
Q 10. How do you delete the files older than 10 days?
Q 11. How do you find the line count for the matching pattern?
Q 12. Write a command to print the lines that ends with the word "specific_word"?
Q 13. Write a command to print the lines matching with exact word?
Q 14. Match all words starting with “Particular String”.
Q 15. Match all pattern which starts with q and doesn’t follow by u?
Q 16. To show below and above 2 lines of the matching pattern?
Q 17. How to zip and unzip the files?
Q 18. How to display files names which contain given word?
Q 19. How to search for multiple matching string in the file?
Q 20. To delete the file which is having permission 644?
Q 21. How to change the permission of any file?
Q 22. How to set default permission of any file?  
Q 23, What is the default permission newly created file and directory?
Q 24. Create a 0 byte file with 477 permission?
Q 25. If file content is space separated, then how to show only last field of the file?
Q 26. Print all input lines from filename that have more than 4 fields.
Q 27. Print the total number of lines in the filename to the screen.
Q 28. If the files having 4 fields and if any field is blank then delete that particular line?
Q 29. How to replace 4th occurrence of any pattern with given new pattern?
Q 30. How to replace the word from the 11th to 19th line only?
Q 31. How to replace all the occurrences of any word with given word in a file?
Q 32. How to print from 34th to 45th line with repeating the line?
Q 33. Write a command to print the lines that do not contain the word "run"?
Q 34. What is the difference between ‘cmp’ and ‘diff’ commands?
Q 35. How to open the file from 60th line?
Q 36. How to search any ERROR string in VI editor and navigate it? (upward & downward)
Q 37. How to copy and delete any line in VI?
Q 38. How to go into Insert mode from Command mode?
Q 39. How to save the changes and exit from VI?
Q 40. How to go to 56th line in VI?
Q 41. How to replace all occurrences of some specific character? (:%s/oldText/newText/g)
Q 42. How to append a file to current file using VI editor?
Q 43. What is the UNIX command to list files/folders in alphabetical order and sorted with modified time?
Q 44. What ‘more’ command does?
Q 45. How to display 57th line of the file? (with head and tail command)
Q 46. What is Zombie Process and how you get Zombie process in unix?
Q 47. What is the command to find maximum memory taking process on the server?
Q 48. What is the command to find the currently running process in Unix Server?
Q 49. What is the command to find remaining disk space in the UNIX server?
Q 50. What is the UNIX command to confirm a remote host is alive or not?
Q 51. What is the method to see command line history?
Q 52. What is the command to find if the system is 32 bit or 64 bit?
Q 53. What is the purpose of the “echo” command?
Q 54. Write a command to erase all files in the current directory including all its subdirectories.
Q 55. Which command is used for remote login?
Q 56. Which command determines the IP address and domain name?
Q 57. What is the importance of $#? (arguments)
Q 58. How do you find status of the last command executed? (meaning of 0 & 1)
Q 59. Name the command that is used to take the backup?
Q 60. difference between $$ and $!?	
Q 61. If-Else condition in Shell Scripting?
Q 62. How to write a function in BASH Shell?
Q 63. What is the importance of PIPE command in Unix?
Q 64. WHILE & FOR loop and CASE statement in Shell?
Q 65. Why we use Break & Continue is Shell Scripting?
Q 66. Operators in UNIX Shell Scripting?

PLSQL Support Interview questions-
Q 1. What is Procedure?
Q 2. Syntax of writing Procedure and its Parts? (Procedure Specification & Procedure Body)
Q 3. Defining Parameter and Procedure Modes?
Q 4. What is Function in PLSQL?
Q 5. Difference between Procedure and Function? (Important)
Q 6. What is Trigger and it’s Types?
Q 7. Syntax and Components of Database Triggers? (Timing Event  Type  Body)
Q 8. What is Cursor?
Q 9. Types of Cursor with explanation?
Q 10. Basic Syntax of writing Cursor?


JAVA Support Interview questions-

Q 1. What do -Xmx and -Xms parameters mean? (Heap Size)
Q 2. What is the difference between JVM and JRE?
Q 3. What is the difference between JVM and JRE?
Q 4. How do you take a thread dump of a Java process?
Q 5. What is OutOfMemoryError in Java? How do you deal with that?
Q 6. What is the Garbage Collector?
Q 7. What is JDBC?
Q 8. What is the database connection pool?
Q 9. Your Java application is connected to a Database via a connection pool. Suddenly your database goes down? Is that an issue with your Java application? Do you need to restart your Java application?

Q 10. What is the difference between HTTP and HTTPS?

Q 11. Your Java application is connecting to another Java application (server) running on the remote host and listening on port 17865. Now, you don't have access to that remote host to go and see if the process is running. How do you find if the server is up and running? (telnet)

Q 12. What is deadlock? How do you find if your Java program has a deadlock? 
Q 13. How do you send a web service request from Linux? (curl and wget)
Q 14. How do you check how much memory and CPU your Java process is consuming?
Q 15. How do you start and stop Tomcat in Linux?
Q 16. How do you check your Java process is running on Linux? (ps -ef | grep java)


Application Support Questions –


Q 1. Explain the ITIL Process in your Day-to-Day activity? (Service Mgt. Incident Mgt, Problem Mgt, Change Mgt, Knowledge Mgt.)
Q 2. Knowledge of Job scheduler, Alert management & Server monitoring
Q 3. What is PROBLEM ticket?
Q 4. What is the condition of a P1 ticket and how do you handle it?
Q 5. How to create and implement E- change.
Q 6. Prioritizing the issue among (application down, database stuck, batch failure)
Q 7. How do you handle if customer reported that application is not opening?
Q 8. How do you handle if any job (which is loading the data to database) is running for long time than usual? (possibilities)
Q 9. What are the reasons of application stuck/not working and how do you handle it? (What is the possible checks you will do)
Q 10. Tell any priority issue which you have recently resolved



