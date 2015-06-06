Basic Usage
===

To **show databases or schemas**:

    show databases;
    
Which shows you a list of databases. (Example below)

    +--------------------+
    | Database           |
    +--------------------+
    | information_schema |
    | c9                 |
    | mysql              |
    | performance_schema |
    +--------------------+
    4 rows in set (0.00 sec)
    
    mysql>
    
To **switch and use the database**, you do:

    use mysql;

Results to:

    Database changed
    
Or sometimes in Read-Only state:

    Reading table information for a completion of table and column names
    You can turn this feature to get a quicker startup with -A
    
    Database changed
    
    mysql>
    
To show your current tables from the current database, do:

    show tables;
    
You will get a result of tables:

    +---------------------------+
    | Tables_in_mysql           |
    +---------------------------+
    | db                        |
    | event                     |
    | func                      |
    | general_log               |
    +---------------------------+
    4 rows in set (0.00 sec)
    
    mysql>