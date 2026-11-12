# Hands-on — ALTER TABLE — add, drop and change columns

The lesson with your hands, not only your eyes.

## The repair drill
With the DEPARTMENT/COURSE pair standing, deliberately set C_Department to CHAR(15), then repair it with ALTER COLUMN. Check the relationship holds.

## Add the missed key
Create a small TEACHER table with no key, fill two rows, then add PRIMARY KEY (teacher_id) with ALTER. Try to add a duplicate id and watch Access refuse.
