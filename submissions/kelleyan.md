Display Environment Variables
=============================
Using a few different commands:
$ set
$ printenv
$ env
all give the same result of the current system variables and settings.

Set Environment Variables
=========================
For the Bourne shell (sh and bash):
export var=value

to set a path:
export PATH=$PATH:/opt/bin:/usr/local/bin:$HOME/bin

Set your text editor:
=====================
setenv EDITOR vim/emacs/"whatever other editor you want"

The previous information was found at:
http://www.cyberciti.biz/faq/set-environment-variable-unix/


