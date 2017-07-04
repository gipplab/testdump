# testdump
Previous test dump application.

Make sure to set the appropriate permissions in the database specified in the [config file](src/main/resources/config/application.yaml).
For example:
```SQL
GRANT ALL ON `testdump`.* TO 'vincent'@'localhost' WITH GRANT OPTION;
FLUSH PRIVILEGES;
```
