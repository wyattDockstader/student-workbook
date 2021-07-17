https://wyattdockstader.github.io/C-KnightsTale/

<b>In a SQL table, what is the difference between information in a row and information in a column?</b>
Columns define what is in the rows, rows are instances of those dfinitions.

<b>Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.</b>
CREATE TABLE characters(
  name VARCHAR(225) COMMENT "Character Name",
  age VARCHAR(225) COMMENT "Character Age",
  description VARCHAR(225) COMMENT "Character Description",
  id INT NOT NULL PRIMARY KEY AUTO_INCREMENT COMMENT "Primary Key"
) default charset utf8 COMMENT '';

<b>What is the difference between the following statements:</b>
<b>DELETE FROM table_name;</b> - Deletes from a table
<b>DROP TABLE table_name;</b> - Deletes a entire table