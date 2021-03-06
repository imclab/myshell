MyShell
=======

A web-based MySQL administration tool for Hackers. 

The main goal of MyShell is to provide a tool for web professionals to administrate their MySQL database as fast as possible. The minimalistic frontend of MyShell initially shows only a single command input field to get you started.

Features
----

* Command input with tab-based autocompletion
* Basic MySQL administration features (SELECT, INSERT, DELETE)
* Super-fast edit mode (Just type _edit_ _table_ _primarykey_).
* Basic database/table statistics
* Batch-edit mode (use _data_ command and then type _edit_ *)

Ideas
----

* Compare datasets with the _compare_ command

Commands
----

### Show a list of databases

    db

### Select a database

    db <database>

### Show table data

    data <table>

### Insert a new dataset

    insert <table>

### Delete a dataset

    delete <table> <primarykey>

### Edit a dataset

    edit <table> <primarykey>

### Filter a resultset, created by data command

    filter <column> <value>

### Show commands

    help

### Execute custom query

    query <query>
