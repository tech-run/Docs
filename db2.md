# DB2
## Useful commands
```
db2 connect to <database-name>                # Connect to a database

db2 list tables for all                       # List all tables 
db2 list tables for schema <schema-name>      # List tables for a schema

db2 describe table <schema-name.table-name>  # Describe a table. 

export to <file_name> of del modified by nochardel coldel| <select_statement> # Creating a CSV file on db2 server. 

db2 "select * from DB2EG.BATCH_STARTUP where NAME='customer'"                                   # DB2 select command.
db2 "update DB2IMAGE.BATCH_STARTUP set STAGE = 'move', NUMBER = 1447585 where NAME='customer'"  # DB2 update command.
```
## Database connection
```
1. Download SQuirrel 
2. Create a db2jcc. 
    Driver class: com.ibm.db2.jcc.DB2Driver 
    Locate DB2Driver db2jcc.jar
    Example URL: jdbc:db2://host:port/<alias>
```
