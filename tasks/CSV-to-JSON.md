Task: Turn a CSV into a JSON
============================

* Given a CSV File, create a JSON File with similar formatting.
* Example:

A CSV like this:
>`R1Column1,R1Column2,R1Column3`<br>
`R2Column1,R2Column2,R2Column3`

Might become:
>`[` <br>
`[R1Column1, R1Column2, R1Column3],`<br>
`[R2Column1, R2Column2, R2Column3]`<br>
`]`

* Then one could add arguments allowing certain columns or rows to be ignored or overridden.
* Alternatively, one column could be used as the key and the other(s) could be used as the value.
* For example:

A CSV like this:
>`R1Column1,R1Column2`<br>
`R2Column1,R2Column2`

Might become:
>`{` <br>
`R1Column1 : R1Column2,`<br>
`R2Column1 : R2Column2`<br>
`}`

And a CSV like this:
>`R1Column1,R1Column2,R1Column3`<br>
`R2Column1,R2Column2,R2Column3`

Might become:
>`{` <br>
`R1Column1 : [R1Column2, R1Column2],`<br>
`R2Column1 : [R2Column2, R2Column2]`<br>
`}`