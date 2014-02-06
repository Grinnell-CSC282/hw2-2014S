Homework 2 - Maijid Moujaled
=====

### Getting and Setting environment variables. 

You can check all the current environment variables by using either one of these

### From the command line
            set
            printenv

### From a bash script

            #!/bin/bash          
            STR="Hello World!"
            echo $STR 

### In C.

We can use the getenv function declared in stdlib.h
It returns a string of that variable, when we pass in the variable name as a string. 

    char * getenv (const char *nam