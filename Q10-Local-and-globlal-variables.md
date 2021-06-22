# What are local variables and global variables in Python?

* Global Variables:

Variables declared outside a function or in global space are called global variables. These variables can be accessed by any function in the program.

## Example

We will create a global variable:

```python
e = 30
print(e)

Output: 
30
```

Create a global variable inside the function:

```python
a = 2
def define():
    global b;
    b = 4
def add():
    c = a + b;
    print(c)
define()
add()
```

* Local Variables:

Any variable declared inside a function is known as a local variable. This variable is present in the local space and not in the global space.

```python
def calculation():
    a = 10
    a = a*10
    print(a)
calculation()
```

Note: A local variable can't access to a global variable.
