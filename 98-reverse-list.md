# How will you reverse a list in Python?

 The `reversed()` or `reverse()` methods takes an iterator like `list` as input and returns a reverse iterator.

`Example` - Using reverse():

This method updates the existing list.

```python
list = ["!", "a", "l", "o", "H"]
list.reverse()
print(list)

# Output:
['H', 'o', 'l', 'a', '!']
```

`Example` - Using reversed() with for loop:

```python
list = ["!", "a", "l", "o", "H"]
for l in reversed(list):
    print(l)

# Output:
H
o
l
a
!
```

## References

[Reverse a list with reversed](https://stackoverflow.com/questions/3940128/how-can-i-reverse-a-list-in-python)

[Reverse list with reverse](https://www.pythonforbeginners.com/lists/how-to-reverse-a-list-in-python)

[Python List reverse()](https://www.programiz.com/python-programming/methods/list/reverse)
