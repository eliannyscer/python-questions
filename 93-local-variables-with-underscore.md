# Why are local variable names beginning with an underscore discouraged?

`A)` They are used to indicate a private variables of a class.

`B)` they confuse the interpreter.

`C)` they are used to indicate global variables.

`D)` they slow down execution.

`Answer:` A. They are used to indicate a private variable of a class.

As Python has no concept of private variables, leading underscores are used to indicate variables that must not be accessed from outside the class.

## Additional information

`What mean to use underscore before the variable name?`

```python
_name = "Hello"
```

It doesn't mean anything. It is a common [naming convention](https://docs.python.org/2/tutorial/classes.html#private-variables-and-class-local-references) for private member variables to keep them separated from methods and public properties.

## References

[Private variables](https://brainly.in/question/2835258)

[Underscore for private variables](https://stackoverflow.com/questions/6903022/why-do-we-use-in-variable-names)
