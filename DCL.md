

| Command | Syntax | Example |
|---------|--------|---------|
| GRANT | `GRANT privilege [, ...] ON object TO user [WITH GRANT OPTION];` | `GRANT SELECT, UPDATE ON employee TO alice;` |
| REVOKE | `REVOKE privilege [, ...] ON object FROM user [CASCADE];` | `REVOKE UPDATE ON employee FROM alice;` |
