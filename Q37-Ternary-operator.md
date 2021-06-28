# How can the ternary operators be used in python?

Also known as `conditional expressions`. It is used to return a value based on the result of a binary condition. It takes binary value(condition) as an input, so it looks similar to an `if-else` condition block. However, it also returns a value so behaving similar to a function.

`Example` - Using ternary operator:

```python
x= 5
y = 6
print("x" if x > y else "y")

# Output:
y
```

With ternary operator, `we are able to write code in one line`. So python basically first evaluates the condition, `if true` evaluate the first expression `else` evaluates the second condition.

`Other example:`

```python
a, b = 30, 20
# Copy value of a if a < b else copy b
min = a if a < b else b
print(min)

# Output:
20
```

`Example` - Using python if-else statement:

```python
x, y = 10, 6
if x > y:
    print(" 'x' is grater than 'y', x =", x)
else:
    print("y =", y)

# Output:
'x' is grater than 'y', x = 10
```

## Reference

[Ternary operator](https://www.geeksforgeeks.org/ternary-operator-in-python/)

[Ternary operator examples](https://www.tutorialspoint.com/ternary-operator-in-python)
