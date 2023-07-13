

| Command | Description | Example |
|---------|-------------|---------|
| BEGIN TRANSACTION | It is used to start a new transaction. | `BEGIN TRANSACTION;` <br> `UPDATE employee SET salary = salary * 1.1 WHERE name = 'Alice';` <br> `INSERT INTO bonus (name, amount) VALUES ('Alice', 1000);` |
| COMMIT | It is used to save the changes made by a transaction permanently in the database. | `COMMIT;` |
| ROLLBACK | It is used to undo the changes made by a transaction and restore the previous state of the database. | `ROLLBACK;` |
| SAVEPOINT | It is used to create a point within a transaction that can be rolled back to later. | `SAVEPOINT sp1;` <br> `UPDATE employee SET salary = salary * 1.2 WHERE name = 'Bob';` <br> `ROLLBACK TO sp1;` |
