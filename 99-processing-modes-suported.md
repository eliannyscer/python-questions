# Explain all file processing modes supported in Python?

Python has various file processing modes.

1.For opening files, there are three modes:

- read-only mode `(r)`
- write-only mode `(w)`
- read–write mode `(rw)`

2.For opening a text file using the above modes, we will have to append ‘t’ with them as follows:

- read-only mode `(rt)`
- write-only mode `(wt)`
- read–write mode `(rwt)`

3.Similarly, a binary file can be opened by appending ‘b’ with them as follows:

- read-only mode `(rb)`
- write-only mode `(wb)`
- read–write mode `(rwb)`

4.To append the content in the files, we can use the append mode (a):

- For text files, the mode would be `at`
- For binary files, it would be `ab`

## Additional information

A file is some information or data which is stored (save) in the computer storage devices. Python provides basic functions and methods necessary to manipulate files by default.

You can do most of the file manipulation using a file object. Python language supports two types of files. First one is text file that store data in the form of text file and readable by human and computer, second one is binary file that store binary data and readable by computer only.

## References

[Python file processing modes](http://net-informations.com/python/iq/modes.htm)

[3 modes that allow you to process files](https://www.interviewgig.com/Ask-a-Question/can-you-explain-all-the-file-processing-modes-supported-by-python/)

[Deep explanation - Official web side](https://docs.python.org/3/library/functions.html#open)
