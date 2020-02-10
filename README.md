Backup_mysql Script's features:

*Backup multiple databases.
*Compress backup files.
*Create logfile.
*Check failed databases

To use this script you must enter your sql server host, port, user, password. 
If there are databases that you don’t want to backup then you need to write them 
in this field of the script: grep -v 'database_name\|database_name2'). 
For exp.: grep -v 'information_schema\|performance_schema\|sys') .

