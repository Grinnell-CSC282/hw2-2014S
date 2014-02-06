Learn about how you set and get environment variables. Put your explanations in the submissions directory, with a file named after you.


Command line
printenv / env -- view env vars
Echo $NAME -- view env var name

Export NAME=1 -- set env var path to 1
export NAME=$PATH:/home/hardtmad/example/ -- append new path to var name

unset NAME -- removes var name

From http://www.thegeekstuff.com/2012/07/linux-export-command-examples/


Bash

export NAME=value
Save and use shell command source .bashrc to get shell to update

From https://marylou.byu.edu/documentation/unix-tutorial/unix9.php


C (get only)

value = getenv(varName);

From http://www.lemoda.net/c/set-get-env/

