# extract_line_error
convert char indexes  to line indexes 

Suppose that you are writing a compiler and that where you parser generator finds a syntax error returns a couple of indexes (namely where the error begins 
and where the error ends) pointing to the *n*-th and *m*-th  character in the code.
This library converts those indexes in a couple of line indexs (namely the line where the error begins and the line where the error ends) in a human readable
format.





