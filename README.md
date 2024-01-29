# Task Instructions:
# 1. Write an INTERSECT query:
Write a SQL query using the INTERSECT operator to retrieve the common records between the "students" and "teachers" tables. The result should include the columns course_id, student_id, student_name, teacher_id, and teacher_name for the common courses.

# 2. Write an INNER JOIN query:
Write a SQL query using the INNER JOIN operation to retrieve records from both the "students" and "teachers" tables where there is a match based on the common column course_id. Include columns from both tables.

## check the performance of intersect and inner join using explain and analyze

# 3.Write an EXCEPT query:
Write a SQL query using the EXCEPT operator to retrieve records from the "students" table that do not exist in the "teachers" table. Include columns student_id, student_name, and course_id.

# 4. Write a RIGHT OUTER JOIN query:
Write a SQL query using the RIGHT OUTER JOIN operation to retrieve all records from the "teachers" table and the matching records from the "students" table based on the common column course_id. Include columns from both tables.

## check the difference between the result of expect and right outer join as they are not same. 
