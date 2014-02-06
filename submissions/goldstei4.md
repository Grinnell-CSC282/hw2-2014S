Environment variables
=====================

* Command Line <sup>[1]</sup>
    * `$ set` prints a list of all environment variables and their values.
    * `$ echo VARIABLE` prints the value of the given environment variable.
* Bash <sup>[1]</sup>
    * `$ export VARIABLE=value` sets the given variable to the given value.
    * `$ VARIABLE=value <command>` sets the given variable to the given value for just the given command invocation.
* C <sup>[2]</sup>
    * `getenv (const char *variable)` returns a string containing the value of the given variable.
    * `putenv (char *string)` adds or removes a variable definition from the environment.
    * `setenv (const char *variable, const char *value, int replace)` adds the definition variable=value to the environment.

Citations
---------

1. [Environment Variable (Wikipedia)](http://en.wikipedia.org/wiki/Environment_variable)
2. [Environment Access (The GNU C Library)](http://www.gnu.org/software/libc/manual/html_node/Environment-Access.html#Environment-Access)
