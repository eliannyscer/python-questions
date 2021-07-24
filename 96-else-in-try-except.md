# When will the else part of try-except-else be executed?

`A)` Always.

`B)` When an exception occurs.

`C)` When no exception occurs.

`D)` When an exception occurs into except block.

`Answer: C). When no exception occurs.`

## Additional information

`Try:` This block will test the excepted error to occur.

`Except:`  Here you can handle the error.

`Else:` If there is no exception then this block will be executed.

`Finally:` Finally block always gets executed either exception is generated or not.

`Example` - The else keyword define a block of code to be executed if no errors were raised:

```python
try:
  print("Hello!")
except:
  print("Something went wrong!")
else:
  print("Nothing went wrong!")

# Output:
Hello!
Nothing went wrong!
```

## References

[Try, Except, else and Finally in Python](https://www.geeksforgeeks.org/try-except-else-and-finally-in-python/)

[Examples](https://www.w3schools.com/python/python_try_except.asp)

