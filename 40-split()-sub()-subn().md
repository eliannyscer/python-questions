# Explain split(), sub(), subn() methods of “re” module in Python

## split()

This function splits the string.The split method should be imported before using it in the program.

`Example-1:`

```python
from re import split
print(split("\W+", "Words, words , Words"))

# Output:
['Words', 'words', 'Words']
```

`Example-2:` - Error

```python
from re import split
# If ypu don't use this "\W+" 
# you will have a error 
# because is part of the function
print(split("Words, words , Words"))

# Output:
TypeError: split() missing 1 required positional argument: 'string'
```

## Sub()

This function stands for the substring in which a certain regular expression pattern is searched in the given string (3rdparameter). When it finds the substring, the pattern is replaced by repl (2ndparameter). The count checks and maintains the number of times this has occurred.

## subn()

This function is similar to `sub()` but the output is different. It returns a tuple with count of total of all the replacements.

## References

[Official python documentation](https://docs.python.org/3/library/re.html?highlight=sub#re.sub)

[Subn](https://www.quora.com/What-are-split-sub-and-subn-methods-in-Python?share=1)

[](https://www.i2tutorials.com/explain-split-sub-subn-methods-of-re-module-in-python/)
