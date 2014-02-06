Some Things Every *nix User Should Know
=======================================

*An annotated list by the students of CSC 295 2014S.*

The List
--------

* Every *nix user should know how to write at least a little C.
* Every *nix users should know at least a few of the puns.
* Every *nix user should know some useful utilities like grep and sed.
* Every *nix user should know how to kill a task.
* Every *nix user should know when to use sudo (and when to not use sudo).
* Every *nix user should know how to change their shell prompt.
* Every *nix user should know the rule of silence. 

Some Notes
----------

### Every *nix user should know how to write at least a little C.

C and *nix grew up together.  Many aspects of C are designed specifically
to work with *nix, some aspects of the shell are closely tied to C (although
more the tcsh and csh than the bash shell), and it's really useful to be
able to hack out a quick C program to do something helpful.

### Every *nix user should know at least a few of the puns.

Why is called bash?  Once upon a time, there was just a shell, called
`sh`, because Unix users like to conserve characters.  It was called
the "Bourne shell" because it was written by Bourne.  When someone wanted
to rewrite it, they called it `bash` for the "Bourne again shell".

### Every *nix user should know how to kill a task.

There are a variety of ways to kill a task (A.K.A. a process), including:
* `kill [PID]`
* `kill -SIGTERM PID`
* Using `ctrl` + `c` (only kills the last process)
* Closing your shell (should kill all processes opened by that shell)


### Every *nix user should know how to change their shell prompt.

You can change the shell prompt to whatever string you want by setting the
environment variable PS1 to your desired string. For example, using the
command `PS1=Computer,\ ` will set your shell prompt to `Computer, `
whenever you type in commands. It's mostly for fun. Thanks to Fiona Byrne
for the creative inspiration behind the example.

### Every *nix user should know the rule of silence.

Well done *nix programs have little to no obstacles in doing what they 
are supposed to do. Silence is key.


