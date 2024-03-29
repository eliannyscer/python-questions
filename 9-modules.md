# What are python modules? Name some commonly used built-in modules in Python.

A Python module is a `.py` file containing executable code or a set of functions you want to include in your application. In short words It is a Python file containing Python statements and definitions.

Some of the commonly used modules are:

* os
* sys
* math
* random
* data time
* JSON

## Additional information

### Create a Module

To create a module just save the code you want in a file with the file extension `.py`:

```python
def greeting(name):
  print("Hello, " + name) 
```

### Use a Module

we can use the module we already created, by using the import statement:

```python
import my_module

my_module.greeting("Ellie")
```

`Note:` When you are using a function from a module, use the syntax: module_name.function_name.

### Some modules

* `os`: It provides functions `for interacting` with the `operating system`.

```python
import os
cwd= os.getcwd()
print("Current working directory:", cwd)

Output:
Current working directory: /media/eli/Data/workplace/Git/Git/Top-100-Python-Interview
```
  
* `sys`: This module  provides various functions and variables that are used `to manipulate` different parts of the Python `runtime environment`.

```python
import sys
print(sys.version)

Output:
3.8.5 (default, May 27 2021, 13:30:53) 
[GCC 9.3.0]
```

* `math`: You can use this module for `mathematical tasks`. It have different methods.

math.pi provides a more precise value for the pi:

```python
import math 
# Print the value of pi 
print (math.pi)

Output:
3.141592653589793
```
  
* `random`: With this module we can `produce anything randomly`.  You can use this module in applications like tic-tac-toe, rock-paper-scissor, etc.

Here a example of a simple program to generate random integers from a range:

```python
import random

# generating a random number from the range 1-100
print(random.randint(1, 100)) 
```

* `data time`: It is `date` and `time` object `combinations`.

```python
import datetime

x = datetime.datetime.now()
print(x) 
```

* `JSON`: It can be used to work with `JSON data`.

```python
import JSON
```

### Runtime and compile runtime

* `Compile-time`: Is the moment where the code you entered is `converted to executable`.
* `Run-time`: Is the moment where `the executable code is running`.

References:

[Python modules](https://www.w3schools.com/python/python_modules.asp)
[Sys module](https://www.geeksforgeeks.org/python-sys-module/)
[Data time module](https://duckduckgo.com/?t=ffab&q=data+time+module+in+python&ia=web)
[JSON module](https://www.w3schools.com/python/python_json.asp)
[Os module](https://www.geeksforgeeks.org/os-module-python-examples/)
[Math module](https://www.w3schools.com/python/module_math.asp)
[Random module](https://www.educba.com/random-module-in-python/)
