Getting and Setting Environment Variables
=========================================


### Command line
To get all environment varibales, simply type:
	`$set`
To get a specific environment variable, such as `$HOME`, use `echo` like this:
	`$echo $HOME` <br>
To add a path to a set of paths stored in an environment variable, you can use the `export` command like this:
	`$export PATH=${PATH}:/this/is/a/new/path` 


### Bash
Bash settings can be editted using a text editor such as vi or emacs:
	`$vi ~/.bash_profile`
Other bash settings can be editted using the same tools as above in the command line section.

### C (get only)
The `export` command will get environment variables for C as well, since C "programs executed from the shell inherit all of the environment variables from the shell" [2][(2)].
C also has a variety of functions that allow you to get or set aspects of the environment. A list from the GNU documenatiaon can be found at citation [3][3]. Some highlights:
- `char ** environ` 
	- An array of strings representing the environment.
- `char * getenv (const char *name)`
	- A function returning the named environment variable


### Citations
1. [1][http://www.cyberciti.biz/faq/set-environment-variable-linux/]
2. [2][http://www.gnu.org/software/libc/manual/html_node/Environment-Variables.html]
3. [3][http://www.gnu.org/software/libc/manual/html_node/Environment-Access.html#Environment-Access]


[1]: http://www.cyberciti.biz/faq/set-environment-variable-linux/
[2]: http://www.gnu.org/software/libc/manual/html_node/Environment-Variables.html
[3]: http://www.gnu.org/software/libc/manual/html_node/Environment-Access.html#Environment-Access