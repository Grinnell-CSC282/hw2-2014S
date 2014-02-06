Setting Environment Variables 
=============================

Command line
------------
'$ set' displays the current environment variables. 

'$ echo [variable]' displays the settings for that variable. 
  * `$ echo PWD` displays the setting for your working directory, for example. 


Setting the environment variables depends on what shell you're using. You might use Bash, or C, or a number of others.

Bash
----
In Bash, changing a variable takes the format 'export var=value'
  * For example, `export PATH=$PATH:/opt/bin:/usr/local/bin:$HOME/bin`

C
-
C has a library which deals with environment access. The function `char * getenv(const char *name)` returns the environment variable named by `name`.

Citations
---------
http://www.cyberciti.biz/faq/set-environment-variable-unix/

http://www.gnu.org/software/libc/manual/html_node/Environment-Access.html#Environment-Access
