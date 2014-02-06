Getting and Setting Environmental Variables
===========================================
* Command Line
	Source: http://ss64.com/nt/set.html
	You can get and set environmental variables with the `set` command, simply writing `$ set name` will display all of the environmental variables with that name and any changes made with `set` will remain only for the current session.
* Bash
	Source: http://tldp.org/LDP/Bash-Beginners-Guide/html/sect_03_02.html
	You can get environmental variables with the `env` or `printenv` command.
	You can set local variables with the `set` command. This command will only set the variable within the working directory.
* C
	Source: http://www.gnu.org/software/libc/manual/html_node/Environment-Access.html#Environment-Access
	You can get environmental variables by calling the `char * getenv (const char *name)` function, which will return a string that has the value of the environment variable name.
