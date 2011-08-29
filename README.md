
runhistory - Re-run previously entered commands
===============================================
runhistory is a small Python script that allows you to search and execute
shell commands you entered before. It searches your BASH history file for
matching commands and lists them.


Usage
-----
This script is used as follows:

  runhistory [keyword1] [keyword2] ...

This searches your ~/.bash_history for any matching keywords. If it finds 
matches, it lists them and allows you to chose a command to run.  Put the 
script somewhere in your $PATH and rename it to e.g. 'rh' for easy access.


Dependencies
------------
* Python (Tested with v2.6.6), expected to be located at "/usr/bin/python"
* Bash (Tested with 4.1.5)


TODO
----
* Support for multiple shells if requested 

