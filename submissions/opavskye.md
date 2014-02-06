Homework 2
=====
_Erik Opavsky_

Getting and Setting Environment Variables
------------------------------------

### Command Line

	set

	printenv

souce: https://help.ubuntu.com/community/EnvironmentVariables


### Bash
	
	PATH= $PATH:$HOME/bin 
	export PATH 

	echo $PATH

source: https://www.ccs.uky.edu/docs/cluster/env.html


### C (get only)

	char * getenv (const char *name)

source: http://www.gnu.org/software/libc/manual/html_node/Environment-Access.html
