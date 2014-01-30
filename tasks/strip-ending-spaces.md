Task: Strip Ending Spaces
=========================

Given a file, remove the "hidden spaces" from the end of each line.

Solution 1: Use `sed`, the stream editor
----------------------------------------

    sed -e 's/ *$//' < infile > outfile

Solution 2: Write a C program
-----------------------------

Here's a sketch

    While input characters remain
      ch = next character;
      If (ch == space)
        buffer the space
      Else if (ch == newline)
        clear the buffer
        print ch
      Else
        print any buffered spaces
        clear the buffer
        print ch
        
Problem: How do you make sure that your buffer is big enough?

Solution: Since you are only buffering spaces, you don't really need an
array of characters.  You can just have a counter of the number of spaces.
An `int` should suffice for that counter, although you could use a `long`.
(If someone has more than 2^63 spaces at the end of a line, it's their own
damn fault.)
