Environment Variables
=====================

### Command line

  * Use the `set` command to read and write environment variables
  * Use the `echo` command to display the value of a variable
  * Use the `export` command to set an environment variable
    * Example: `$ export PATH=${PATH}:${HOME}/bin`

### Bash

### C

  * `getenv (const char *variable)` returns a string containing the value of the given variable.
  * `putenv (char *string)` adds or removes a variable definition from the environment.
  * `setenv (const char *variable, const char *value, int replace)` adds the definition variable=value to the environment.

References
==========

  * [Wikipedia page on Markdown](http://en.wikipedia.org/wiki/Markdown)
  * [Article on Linux environment variables](http://www.cyberciti.biz/faq/set-environment-variable-linux/)
