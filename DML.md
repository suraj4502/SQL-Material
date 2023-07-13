
| Command | Syntax | Example |
|---------|--------|---------|
| INSERT | `INSERT INTO table_name (column_name [, ...]) VALUES (value [, ...]);` <br> `INSERT INTO table_name VALUES (value [, ...]);` | `INSERT INTO employee (name, email) VALUES ('Alice', 'alice@example.com');` <br> `INSERT INTO employee VALUES ('Bob', 'bob@example.com', '1990-01-01');` |
| UPDATE | `UPDATE table_name SET column_name = value [, ...] WHERE condition;` | `UPDATE employee SET email = 'alice@gmail.com' WHERE name = 'Alice';` |
| DELETE | `DELETE FROM table_name WHERE condition;` | `DELETE FROM employee WHERE name = 'Bob';` |
