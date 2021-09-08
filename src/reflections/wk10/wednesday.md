# Wednesday

## In a SQL table, what is the difference between information in a row and information in a column?
Columns are properties (title, body, ID,etc.) where rows are complete items or objects (book inlcuding all the needed properties)
## Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.
CREATE TABLE characters(
  id int NOT NULL,
  name VARCHAR(255) NOT NULL,
  description VARCHAR(255) NOT NULL,
  age VARCHAR(255) NOT NULL
);
## What is the difference between the following statements:
DELETE FROM table_name; This deletes an item from the table.
DROP TABLE table_name; This deletes the entire table.

Link:https://john87barker.github.io/knight/